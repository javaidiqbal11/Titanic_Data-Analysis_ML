# Titanic Dataset Preprocessing and Modeling

This project preprocesses the Titanic dataset and trains machine learning models for predicting passenger survival.

## Dataset

The Titanic dataset (`titanic_train.csv`) contains information about passengers aboard the Titanic, including features such as passenger class, age, number of siblings/spouses, number of parents/children, fare, sex, and embarked port.

## Preprocessing Steps

1. Load the dataset using pandas.
2. Select features ('Pclass', 'Age', 'SibSp', 'Parch', 'Fare', 'Sex', 'Embarked') and the target variable ('Survived').
3. Encode categorical variables ('Sex' and 'Embarked') using one-hot encoding.
4. Handle missing values in the 'Age' and 'Fare' columns by imputing with the mean.
5. Scale numerical features ('Pclass', 'Age', 'SibSp', 'Parch', 'Fare') using StandardScaler.

## Training Models

The preprocessed data is split into training and testing sets. Three classification models are trained:
- Random Forest
- Support Vector Machine
- Logistic Regression
- Naive Bayes

Model performance is evaluated using accuracy, precision, recall, and F1-score.

## How to Run

1. Clone this repository.
2. Install the required dependencies using `pip install -r requirements.txt`.
3. Run the main script or notebook to preprocess the data and train the models.

## Files

- `titanic_train.csv`: The Titanic dataset.
- `preprocess_and_model.py`: Python script for preprocessing and modeling.
- `requirements.txt`: File containing required dependencies.
- `README.md`: Documentation for the project.

