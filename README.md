# Titanic Survivors Prediction

## Project Goal
Build a machine learning model to predict whether a passenger survived the Titanic disaster based on features such as age, sex, ticket class, and more.

## Dataset
- **Source:** [Kaggle Titanic Dataset](https://www.kaggle.com/c/titanic)
- Contains passenger information such as age, gender, ticket class, fare, cabin, and more.

## Input Features
- Pclass: Ticket class (1st, 2nd, 3rd)  
- Sex: Gender  
- Age: Age in years  
- SibSp: # of siblings/spouses aboard  
- Parch: # of parents/children aboard  
- Fare: Passenger fare  
- Embarked: Port of Embarkation (C = Cherbourg, Q = Queenstown, S = Southampton)  
- Cabin, Ticket, Name (can be engineered)

## Target Variable
- Survived: 0 or 1

## Project Steps
1. Exploratory Data Analysis (EDA)  
   - Visualize survival rate across different features  
2. Data Preprocessing  
   - Handle missing values and encode categorical features  
   - Feature engineering (e.g., extract title from Name, create Age groups)  
3. Model Building  
   - Models tried: Logistic Regression, Random Forest, XGBoost  
   - Used cross-validation for robust performance  
4. Evaluation  
   - Metrics: accuracy, precision, recall, confusion matrix, ROC curve  
5. Hyperparameter tuning using GridSearchCV  

## Learning Outcomes
- Apply supervised classification techniques  
- Practice data wrangling and feature engineering  
- Evaluate model performance using appropriate metrics  
- Understand how data bias (e.g., gender, class) can affect predictions  

## Setup & Installation
1. **Clone the repository**
```bash
git clone https://github.com/your-username/titanic-survivors-prediction.git
cd titanic-survivors-prediction
```
2. **Create & activate a virtual environment**
```bash
# On Linux/Mac
python -m venv titanic
source titanic/bin/activate

# On Windows (PowerShell)
python -m venv titanic
.\titanic\Scripts\activate
```
3. **Install dependencies**
```bash
pip install -r requirements.txt
```
4. **Run the project**
Open the Jupyter Notebook or Python scripts and follow the workflow for preprocessing, training, and evaluating models.
