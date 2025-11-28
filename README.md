This is a repository for the fifth week assignment of the course 'Introduction to Deep Learning' (5511) of the Master of Data Science at the University of Colorado Boulder.
The subject is 'I'm Something of a Painter Myself' challenge on Kaggle. The objective of the challenge is transform photos of still lifes into images in the style of a Monet painting.
More information can be found on the Kaggle website: https://www.kaggle.com/competitions/gan-getting-started.

- The notebook **5511-pr-week-5-eda.ipynb** contains exploratory data analysis.
- The notebook **5511-pr-week-5-eval.ipynb** contains samples of the generated images.

The architectures I trained are based on the architecture in this notebook: https://www.kaggle.com/code/raninikki/painter-gans.

I trained the following versions of this architecture:

1. A baseline version with 10 epochs.
2. A version with the standard deviation of the normally distributed weights at 0.2 (instead
of 0.02).
3. A version with a learning rate of 0.002 (instead of 0.00002).
4. A version with 20 epochs.

The scores were:

- Architecture 1 | 	62.7996
- Architecture 2 | 	296.4718
- Architecture 3 |	114.3407
- Architecture 4 | 	53.8185

The scoring methodology is explained here: https://www.kaggle.com/competitions/gan-getting-started/overview.
