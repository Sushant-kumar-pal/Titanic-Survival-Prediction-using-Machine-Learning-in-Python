# Titanic-Survival-Prediction-using-Machine-Learning-in-Python
This is the group project mentered by Prof. Dr. Emmanuel S. Pilli, MNIT Jaipur.The group members includes Sushant Kumar Pal(leader),Priyansh Lashwani,Pratham Dani. 
## Problem Statement
Given what we know about a passenger aboard the Titanic, can we predict whether or not this passenger has survived? In other words, we are training a machine learning model to learn the relationship between passenger features and their survival outcome and subsequently make survival predictions on passenger data that our model has not been trained on.

This is a binary classification problem in machine learning as we are classifying the outcomes of passengers as either survived or did not survive the Titanic.

## Evaluation Metric
The evaluation metric of this competition is the percentage of passenger data in the test set that are correctly predicted by our model. This is known as accuracy.

## Data Description
Below are the descriptions of the features in the data:

- **Survival**: 0 = Did not survive, 1 = Survived
- **Pclass**: Ticket class where 1 = First class, 2 = Second class, 3 = Third class. This can also be seen as a proxy for socio-economic status.
- **Sex**: Male or female
- **Age**: Age in years, fractional if less than 1
- **SibSp**: Number of siblings or spouses aboard the Titanic
- **Parch**: Number of parents or children aboard the Titanic
- **Ticket**: Passenger ticket number
- **Fare**: Passenger fare
- **Cabin**: Cabin number
- **Embarked**: Point of embarkation where C = Cherbourg, Q = Queenstown, S = Southampton

## Data Files
- `train.csv`: The training dataset containing features and the survival outcome.
- `test.csv`: The test dataset for which survival predictions need to be made.

## Usage
To work on this problem, you can use Jupyter Notebook or any other Python development environment. The following libraries are commonly used in this task:
- Pandas for data manipulation
- NumPy for numerical operations
- Scikit-Learn for building and evaluating machine learning models
- Matplotlib and Seaborn for data visualization



