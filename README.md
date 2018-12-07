# WineReviewAnalysis


#Project Overview

This project is an Analysis of a wine review dataset from Kaggle (https://www.kaggle.com/zynicide/wine-reviews).
I wanted to try to answer 4 questions
1. Which words to look for in a wine description?
2. Which country offeres the best value for money?
3. Is older wine more expensive and better?
4. Can an algorithm rate your wine?

#Packages

For this jupyter notebook to run you need these common packages: Pyhton 3.6, jupyter notebook, pandas, numpy, matplotlib, sklearn.
Additionally you have to install sklearn_pandas (https://github.com/scikit-learn-contrib/sklearn-pandas) and
scattertext(https://github.com/JasonKessler/scattertext)

#Files

winemag-data-130k-v2.csv : a csv file with 130k winereviews in 10 columns (description, designation, points, price,
                           province, region_1, region_2, variety, winery)
wine review analysis.ipynb: a jupyter notebook with all the analysis of the dataset
winescatter.html: an interactive graph which shows the frequency of words in the description for wines with <90 and >90 points.

#Conclusion

Read insights here: https://medium.com/@hallocomputer3/should-you-use-data-science-to-buy-a-wine-f2ff210dc127
