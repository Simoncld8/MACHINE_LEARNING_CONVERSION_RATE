# MACHINE_LEARNING_CONVERSION_RATE

# Challenge : predict conversions 🏆🏆

This project was a simulation of a machine learning competition like the ones that are organized by https://www.kaggle.com/.


The data scientists who created the newsletter would like to better understand the behavior of users visiting their website, especially what influences the subscription to the newsletter.

## Goals

Build a model that predicts if a given user will subscribe to the newsletter, by using just a few information about the user. Then, analyze the parameters of the model to highlight features that are important to explain the behaviour of the users, and maybe discover a new lever for action to improve the newsletter's conversion rate.

This project is a competition. To assess the rankings of the different competing teams, they decided to use the f1-score.

## Dataset

Open-source dataset containing some data about the traffic on the website.

conversion_data_train.csv contains labelled data, which means there are both X (explanatory variables) and Y (the target to be predicted). This file is used to train the model : 
 * train/test split
 * preprocessings
 * assess performances
 * try different models,
 * fine-tune hyperparameters 

conversion_data_test.csv contains "new" examples that have not be used to train the model, in the same format as in data_train.csv but it is unlabeled, which means the target Y has been removed from the file. Once the model is trained, use conversion_data_test.csv to make some predictions that you will send to the organizing team. They will then be able to assess the performances of your model in an independent way, by preventing cheating.

## Content

The project will be structured into three main components:

1. **Exploratory Data Analysis (EDA) of the Dataset**
   - Overview of the dataset, including its dimensions and data types.
   - Identification of missing values and consideration of potential implications.
   - Displaying a sample of the dataset and providing basic statistics.

2. **Data Preprocessing**
   - Split data into train and test set.
   - Preprocessing the data, which involves handling categorical and numerical values, and performing encoding.

3. **Model Training, and Performance Analysis**
    * Logistic Regression
    * AdaBoost Logistic Regression
    * Bagging Logistic Regression
    * Random Forest
    * Voting

## Usage

To utilize and explore this project, follow these steps:

1. **Clone the Repository:**

   git clone https://github.com/Simoncld8/MACHINE_LEARNING_CONVERSION_RATE.git


2. **Install Dependencies:**

   pip install -r requirements.txt  

3. **Run the Analysis:**

   You will find all the analysis in the Jupyter Notebook provided (`Conversion_rate_challenge.ipynb`).

## Results

The results of the prediction can be found in the file named 'conversion_data_test_predictions_SIMON-model.csv.'

This leads to an F1 score of 0.756, Precision of 0.844, and Recall of 0.685.


Contributors

Simon Claude

This project was undertaken as part of the "Data Science and Engineering Fullstack" program offered by Jedha. Its aim was to fulfill a component of the "Concepteur Développeur en Science des Données" certification.


