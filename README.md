# WineReviewAnalysis


# Project Overview

This project is an Analysis of a wine review dataset from Kaggle (https://www.kaggle.com/zynicide/wine-reviews).
I wanted to try to answer 4 questions
1. Which words to look for in a wine description?
2. Which country offeres the best value for money?
3. Is older wine more expensive and better?
4. Can an algorithm rate your wine?

# Packages

For this jupyter notebook to run you need these common packages: Pyhton 3.6, jupyter notebook, pandas, numpy, matplotlib, sklearn.
Additionally you have to install sklearn_pandas (https://github.com/scikit-learn-contrib/sklearn-pandas) and
scattertext(https://github.com/JasonKessler/scattertext)

# Files

winemag-data-130k-v2.csv : a csv file with 130k winereviews in 10 columns (description, designation, points, price,
                           province, region_1, region_2, variety, winery)

wine review analysis.ipynb: a jupyter notebook with all the analysis of the dataset

winescatter.html: an interactive graph which shows the frequency of words in the description for wines with <90 and >90 points.

# Conclusion, Findings

1. I was able to build one interactive graph to search for words from a wine description, which classify the words as typical for good and bad wines.
2. I built some graphs to show the countries which countries of origin offering the best value for money and this categorized by the wine varieties.
3. I showed that old wine is more expensive and is higher rated. To get the best and oldest wines price rises extraordinary.
4. I constructed a machine learning algorithm which is not yet too much helpful to predict ratings but trained on a more powerful machine than mine the result could be much better

Read insights here: https://medium.com/@hallocomputer3/should-you-use-data-science-to-buy-a-wine-f2ff210dc127

# Licensing, Authors, Acknowledgements

This repository is licensed under the MIT-License. Big thanks to zackthoutt https://www.kaggle.com/zynicide/wine-reviews for scraping, providing  and maintaing the dataset.
