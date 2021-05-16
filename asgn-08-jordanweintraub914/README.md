# Our last assignment! It's a contest!

## Some of my favorite things learned:
- My biggest takeaway was the EDA and visualizations. It was great to work with large daasets, learning how to properly explore the dataset and play around with it. We learned how to deal with null values, remove outliers, examine the distribution, and many other. We also worked with merging datasets and different steps that are necessary to efficiently work with your data.

- I also enjoyed the topics on regression. There are major implications that come with running a regression and was happy we got to explore some exercises dealing with it. It is a **very** useful skill to be able to determine how successful X number of variables are at predicting Y. Prediction is a powerful tool that is become more popular in the world of data science. 

- To be honest, I did not learn much from this prediction contest. I wish I put more time into it so that I would learn something. However, looking back at all my previous assignments, I feel that I have learned a ton. 

- I've told you this before bit I am going to be a quantitative research analyst at Hamilton Lane, working within their investments team dealing with portfolio construction, strategy and risk. Half of my job is coding in R, but I believe it's for the most part the same type of work we are doing in this class (working with large datasets, EDA, regression, etc.)




## Your mission

The home prices we've been modeling aren't the only homes in existence. I want to build a model to help me price all homes so I can build a real estate empire. 

The stakes are high! If I spend too much on my acquisitions, well...

![](http://www.shutupandtakemymoney.com/wp-content/uploads/2020/04/im-never-going-to-financially-recover-from-this-joe-exotic-tiger-king-meme.jpg)

## Evaluation

So now we're doing real business. Thus, **the grade for this file is not based on effort, but on results.** Your grade will be based on how far you are from the class leader on the objective (see below). 

## Task

Use your new skills to estimate a model you think will produce the most accurate out-of-sample predictions as possible.
1. Model the **natural log of the sale price** (`np.log`) using the `housing_train.csv` dataset.
1. Your model should focus on optimizing the **R2**.
1. When you settle on your final model, load the `housing_holdout.csv` dataset and predict the log sale price. 
1. Save a csv file in the "submission" folder called "MY_PREDICTIONS.csv".
    - It should have two columns: "parcel" (the row identifier in the holdout dataset) and "prediction" (your predicted LOG price)
	- Look at the "sample_submission" file for an example how this should look. 
1. Not required, but requested: Replace this readme with 
    - a few of your favorite things from class, something you liked learning, or are happy to know now
    - a **short** summary of a sentence or three (for yourself) of what you learned on this assignment
    - if you found out since our beginning-of-semester talks what you'll be doing this summer/after graduation, I'd love to know

## Tips

1. Start by figuring out how to submit. Lazily estimate a model, like the one in the last assignment, then use it on the holdout sample. Once you've done this, you can focus on modeling. 
1. Try as many model types as you want. For each model,
    - preprocess and modify the sample as you please 
    - tune and optimize the models' hyperparameters
    - use folds to generate extra samples as you tune the models

## Assignment outro

OMG, I can't believe we finished the last assignment of this class!

![](https://media.giphy.com/media/iHyVaHfEYXZos8qPX2/giphy.gif)

Congrats on making it this far, friend. Let's graduate, get out into the real world (if quarantine ever ends), and go long on NFTs. 

![](https://media.giphy.com/media/zstmxMkwo3vn3GuTFj/source.gif)

![](https://media.giphy.com/media/oBQZIgNobc7ewVWvCd/source.gif)
