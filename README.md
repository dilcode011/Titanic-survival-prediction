# 🚢 Project: Titanic Survival Prediction

## 1. The Goal
The sinking of the Titanic is one of the most infamous shipwrecks in history. On April 15, 1912, the Titanic sank after colliding with an iceberg, killing 1502 out of 2224 passengers and crew.

**Objective:** Build a machine learning model to predict whether a passenger survived or not based on features like age, gender, ticket class, and fare.

## 2. The Dataset
The dataset is available on [Kaggle](https://www.kaggle.com/c/titanic/data).

### Key Features:
* **Pclass:** Ticket class (1 = 1st, 2 = 2nd, 3 = 3rd)
* **Sex:** Gender
* **Age:** Age in years
* **SibSp:** # of siblings / spouses aboard
* **Parch:** # of parents / children aboard
* **Fare:** Passenger fare
* **Embarked:** Port of Embarkation (C = Cherbourg, Q = Queenstown, S = Southampton)

## 3. The Workflow
1.  **Exploratory Data Analysis (EDA):** Visualizing survival rates by gender, class, etc.
2.  **Data Preprocessing:**
    * Handling missing values (Age, Embarked).
    * Encoding categorical variables (Sex: Male/Female -> 0/1).
3.  **Model Building:** Training multiple models.
4.  **Evaluation:** Comparing Accuracy and Confusion Matrices.

## 4. Results
| Model | Accuracy |
| :--- | :--- |
| Logistic Regression | 78% |
| Random Forest | 82% |
| **XGBoost** | **84%** |
