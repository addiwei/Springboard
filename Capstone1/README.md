# Project Title:  Predicting Virality of Youtube Videos 

## Features of the Project
1. Supervised learning multiclassification problem to predict whether a youtube video is viral.
2. Includes preprocessing, EDA, feature selection, and modeling of both numeric and text data using feature union / pipelines.
3. Logistic Regression, SVM, Stochastic Gradient Descent, KNN, Random Forest, Gradient Boosting Classifier, XGBoost.
4. Utilizing count and density based features of text data, bag of words, n-grams, stemmed, stop words, and Word2Vec.


### Intended Audience
1. Beginner to intermediate machine learning enthusiasts interested in learning how to tackle a machine learning project from start to finish.  

### Included Files
1. Final Presentation on the Project
2. Final Report on the Project
3. Jupyter notebooks:
    1) Jupyter Notebook 1 - Collecting data via Youtube API
    2) Jupyter Notebook 2 - Numeric data preprocessing, visualization, hypothesis testing on correlation
    3) Jupyter Notebook 3 - Modeling on the numeric data exclusively
    4) Jupyter Notebook 4 - Text data preprorcessing, visualization, feature evaluation / selection
    5) Jupyter Notebook 5 - Modeling on the text data exclusively
    6) Jupyter Notebook 6 - Combined modeling on numeric + text data
4. youtube data file (1000 rows of data) 
5. new-requirements.txt lists the packages and versions utilized for the project

### Getting Started / Requirements
1. Requires Python (at least 3.0), Jupyter Notebook, Python machine learning libraries (Please see new-requirements.txt for a list of packages and versions required) 
2. Copy all of the jupyter notebooks, including youtube data file "youtube1000.csv" on to your local machine into a single folder.
3. Run all of the notebooks in order from 2,3,4,5,6.  Notebook number 1 does not need to be run because it's the API code to collect the data.  You can use notebook 1 to collect more data.  
Note: Notebooks that are labeled "modeling", will take a long time to run - this is normal and run time is dependent on hardware. 

