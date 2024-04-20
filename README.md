# Airbnb-Data-Science-Project-listing-Seattle

Airbnb Data Science Project
Seattle

Here is a quick overview of the project. The full analysis and findings can be viewed here.

📖 Overview
What are the factors and features of a listing that make an Airbnb listing in Seattle more expensive?
That is the question this project aims to answer. We started of by collecting data of listings in Seattle from Kaggle. Then, we cleaned the data to a useful format for data analysis. We then did Exploratory Analysis on the data by focusing on 3 sub-problems:

What are the features/facilities/ammenities of a property that affect its price?
Are there particular locations in Seattle where Airbnb listings fetch higher prices?
Does textual data in the summary and sentiments of reviews affect price?
Afterwards, we did Machine Learning on the data by adopting 6 different Regression models for our regression problem. They were:

Linear Regression
Random Forrest Regression
XGBoost
CatBoost
Ridge Regression
Lasso Regression
We partitioned the data into train and test sets and evaluated the models on their prediction accuracy. Once we found the most accurate prediction model, we used that model in a library called TreeInterpreter which decomposed the prediction into a sum of contributions from each feature: Prediction = Bias + Feature1 x Contribution1 + … + FeatureN x ContributionN. We used this to find the most important features that affected the price of a listing.

🚀 Getting Started
📋 Prerequisites
If you would like to download and run all the data analysis and prediction models on your own machine, it is recommended to use to Anaconda and Jupyter Notebook. If you use Anaconda most of the packages used in this project are pre-installed except the following few:

Graphviz
Langdetect
Wordcloud
XGBoost
CatBoost
TreeInterpreter
⚡️ Installing and running
Install the required packages by running the following commands in your terminal:

pip install graphviz
pip install langdetect
pip install wordcloud
pip install xgboost
pip install catboost
pip install treeinterpreter
Then clone this repo with

git clone https://github.com/mohamedirfansh/Airbnb-Data-Science-Project.git
You can then open the following files with Jupyter Notebook:

Exploratory Analysis Problem 1.ipynb
Exploratory Analysis Problem 2.ipynb
Exploratory Analysis Problem 3.ipynb 
Machine Learning Models.ipynb
🛠️ Built with
Python 3 - Main programming language used, done in Jupyter Notebook.
Pandas - Main library used to manipulate the datasets.
Scikit-learn - Main library used for machine learning.
Matplotlib - Used for graph plots and visualizations.
Python NLTK - Used during exploratory analysis to get further insights into the textual data.
XGBoost - Used to implement gradient boost decision trees.
CatBoost - Used to implement gradient boost decision trees.
TreeInterpreter - Used to decompose predictions into a sum of contributions from each feature.
👨‍💻 Developers
Mohamed Irfan
Dian Wei
Kristy
📄 License
GitHub

This project is licensed under the MIT License - see the LICENSE file for more details.
