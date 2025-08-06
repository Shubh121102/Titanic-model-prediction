# 🚢 **Titanic Survival Prediction – Machine Learning Project**
This project uses a supervised machine learning approach to predict passenger survival on the Titanic. Leveraging the famous Kaggle Titanic dataset, the notebook demonstrates a full data science pipeline from data cleaning to model evaluation.

## 📁 **Files Included**
- Titanic_dataset_prediction.ipynb – Jupyter notebook with full implementation
- titanic_model.pkl – Titanic prediction model saved in a pickel file
- README.md – Project overview and instructions
- (Optional) titanic.csv – Input dataset (linked from Kaggle)

## 📊 **Dataset Overview**
The dataset includes demographic and travel information for Titanic passengers. Key features used:

- Pclass (Passenger Class)
- Sex
- Age
- SibSp (Siblings/Spouses aboard)
- Parch (Parents/Children aboard)
- Fare
- Embarked
- Survived (Target variable)
📌 Dataset Source: Kaggle Titanic Dataset

## 🔍 **Key ML Techniques Used**
- Handling Missing Values
- Exploratory Data Analysis (EDA)
- Feature Engineering:
- Family Size
- IsAlone
- Title Extraction
- Encoding Categorical Variables (Label and One-Hot Encoding)
- Classification Model:
- Logistic Regression
- Evaluation Metrics:
- Accuracy
- Precision
- Recall
- F1-Score

## 📈 **Model Results**
The Logistic Regression model achieved the following performance on the validation set:

- ✅ Accuracy: 82.6%
- ✅ Precision: 79.4%
- ✅ Recall: 78.3%
- ✅ F1-Score: 78.9%
- ✅ Confusion Matrix
  
These results indicate a well-balanced model with good generalization ability for binary classification in this Titanic survival problem.

## 📦 **Requirements**
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn
- jupyter
