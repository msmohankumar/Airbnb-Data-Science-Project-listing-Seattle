# Airbnb-Data-Science-Project-listing-Seattle
![main page](https://github.com/msmohankumar/Disaster_Rescue_App/assets/153971484/d29bf65c-1ef4-40ac-a536-41d942ed3921)

# Airbnb Data Science Project - Seattle Listings

## Overview

This project investigates factors influencing Airbnb listing prices in Seattle. We leverage data from Kaggle to perform exploratory analysis and build machine learning models for price prediction.

**Key Questions:**

* Which property features and amenities affect listing prices?
* Do specific locations in Seattle command higher prices?
* Does textual data from descriptions and reviews influence pricing?

## Methodology

1. **Exploratory Data Analysis (EDA):**
    * Identify features impacting price through data exploration.
    * Analyze pricing trends across different locations.
    * Examine the influence of textual data (descriptions & reviews).

2. **Machine Learning Models:**
    * Train and evaluate six regression models to predict listing prices.
    * Models include: Linear Regression, Random Forest Regression, XGBoost, CatBoost, Ridge Regression, and Lasso Regression.

3. **Feature Importance Analysis:**
    * Use TreeInterpreter to understand the contribution of each feature towards listing price.
    * Identify the most critical factors influencing price.

## Getting Started

**Prerequisites:**

* Anaconda and Jupyter Notebook (https://www.anaconda.com/)

**Required Packages (Install if not using Anaconda):**

* Graphviz: `pip install graphviz`
* Langdetect: `pip install langdetect`
* Wordcloud: `pip install wordcloud`
* XGBoost: `pip install xgboost`
* CatBoost: `pip install catboost`
* TreeInterpreter: `pip install treeinterpreter`

**Project Structure:**

Airbnb-Data-Science-Project/
├── catboost_info/        # CatBoost model files
│  └── ...
├── data/
│  ├── calendar.zip        # Calendar data from Kaggle
│  ├── listings.zip        # Listings data from Kaggle
│  ├── polarity_reviews.zip  # Polarity results (specific to this project)
│  └── reviews.zip          # Reviews data from Kaggle
├── notebooks/
│  ├── Exploratory_Analysis_Problem_1.ipynb  # Feature/amenity analysis
│  ├── Exploratory_Analysis_Problem_2.ipynb  # Location analysis
│  ├── Exploratory_Analysis_Problem_3.ipynb  # Textual data analysis
│  └── Machine_Learning_Models.ipynb         # Machine learning models
├── README.md              # Project documentation
├── LICENSE                # License information
└── requirements.txt       # Required Python packages

**Run the Analysis:**

1. Clone this repository.
2. Open Jupyter Notebook and navigate to the project directory.
3. Open the Jupyter Notebook files for each analysis step:
    * Exploratory_Analysis_Problem_1.ipynb
    * Exploratory_Analysis_Problem_2.ipynb
    * Exploratory_Analysis_Problem_3.ipynb
    * Machine_Learning_Models.ipynb

## Technologies Used

* **Programming Language:** Python 3 (executed in Jupyter Notebook)
* **Data Manipulation:** Pandas
* **Machine Learning:** scikit-learn
* **Visualization:** Matplotlib
* **Text Analysis:** Python NLTK (used for exploratory data analysis)
* **Gradient Boosting:** XGBoost, CatBoost
* **Feature Contribution Analysis:** TreeInterpreter

## Developers

* M S Mohan Kumar



