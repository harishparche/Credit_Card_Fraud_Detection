# Credit Card Fraud Detection 

## Problem statement 

The problem statement chosen for this project is to predict fraudulent credit card transactions with the help of machine learning models.

In this project, we will analyse customer-level data which has been collected and analysed during a research collaboration of Worldline and the Machine Learning Group. 

The dataset is taken from the [Kaggle Website](https://www.kaggle.com/mlg-ulb/creditcardfraud) website and it has a total of 2,84,807 transactions, out of which 492 are fraudulent. Since the dataset is highly imbalanced, so it needs to be handled before model building.

## Understanding and Defining Fraud

Credit card fraud is any dishonest act and behaviour to obtain information without the proper authorization from the account holder for financial gain. Among different ways of frauds, Skimming is the most common one, which is the way of duplicating of information located on the magnetic strip of the card.  Apart from this, the other ways are:

- Manipulation/alteration of genuine cards
- Creation of counterfeit cards
- Stolen/lost credit cards
- Fraudulent telemarketing 

## Data Dictionary

The dataset can be download using this [link](https://www.kaggle.com/mlg-ulb/creditcardfraud)

## Project Pipeline

The project pipeline can be briefly summarized in the following five steps:

- **Data Understanding:** Here, our fifrst step is to analyze the data and understand the features present in it. This help us to choose the features that required for your final model.
- **Exploratory data analytics (EDA):**  in this step, we need to perform univariate and bivariate analyses of the data, followed by feature transformations, if necessary. 
- **Train/Test Split:**  Now we can perform in order to check the performance of our models with unseen data. Here, for validation, we can use the k-fold cross-validation method. 
- **Model-Building/Hyperparameter Tuning:** This is the final step at which we can try different models and fine-tune their hyperparameters until we get the desired level of performance on the given dataset. We should try and see if we get a better model by the various sampling techniques.
- **Model Evaluation:** We need to evaluate the models using appropriate evaluation metrics. Note that since the data is imbalanced it is is more important to identify which are fraudulent transactions accurately than the non-fraudulent. We need to choose an appropriate evaluation metric which reflects this business goal.
