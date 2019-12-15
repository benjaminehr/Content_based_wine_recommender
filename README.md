# Content-based Wine Recommender

## Table of Contents
1. Installation
2. Project Motivation
3. File Descriptions
4. Results
5. Licensing, Authors, Acknowledgements

## 1. Installation
Necessary libraries to run the code beyond the Anaconda distribution of Python: 
* pandas
* numpy 
* matplotlib
* seaborn 
* re
* nltk
* TfidfVectorizer from sklearn.feature_extraction.text
* rake_nltk
* progressbar
* from IPython.display import HTML

## 2. Project Motivation
For this project, I was interested in using data from my professional background in the beverage retail business. I am currently working as a data analyst in this domain, so the question of recommending wine is a of personal interest to me.

The questions I pose in the analysis are
* How many different Tasters are in the dataset, and how do they rate?
* What kind of information does the written description contain?
* How good is a recommendation engine based on description texts?

The focus of the project lies in this last, central question. I want to experiment with content-based recommendation engines as well as with natural language processing, so this dataset provides a good opportunity to experiment with both aspects.

## 3. File Descriptions
For this post, I use this Kaggle dataset (https://www.kaggle.com/zynicide/wine-reviews), which contains over 130.000 wine reviews containing ratings, prices, and written descriptions. The data was scraped in 2017 from the WineEnthusiasts website.
I used the *winemag-data-130k-v2.csv* file for the analysis because it is the newer version. 

The analysis is carried out in the notebook: **Text Based Recommendation System With Wine Reviews**

## 4. Results
The main findings of the code can be found at the post available here: 
https://medium.com/@benjaminehrensberger/find-similar-wines-to-the-one-you-love-d502e8168f76?source=friends_link&sk=1220fa5a66b7f60f16e0bb995f1044e3

Short:
* There are 19 different Taster overall, which rate on average between 85.86 and 90.56 points.
* The descriptions are comprised of descriptive, assoziative and extra information. 
* It is possible to use this information to recommend wines. 

## 5. Licensing, Authors, Acknowledgements
I must gave credits to Zack Thoutt who provided this amazing dataset on kaggle. 
