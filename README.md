# 🚢 Titanic Dataset — Data Preprocessing

## 📌 Overview
This project focuses on exploring, cleaning, and preparing the Titanic dataset for Machine Learning.

It covers several data preprocessing techniques, from handling missing values to feature engineering, encoding, and scaling.

## 🛠️ Tools & Libraries
- Python
- Pandas
- Seaborn
- Scikit-learn

## 📊 Project Workflow

### 1. Data Exploration
- Explore dataset structure and information.
- Analyze numerical and categorical features.
- Check missing values.
- Check duplicate records.
- Visualize data distributions.

### 2. Outlier Detection
- Calculate Q1 and Q3.
- Apply the IQR method.
- Identify outliers using a Box Plot.
- Keep the identified outliers.

### 3. Train-Test Split
- Separate features and target variable.
- Split data into training and testing sets.
- Use an 80/20 split.

### 4. Feature Engineering
- Extract passenger titles from names.
- Group similar titles.
- Extract ticket prefixes.
- Create new features from existing columns.

### 5. Categorical Encoding
- Apply Label Encoding.
- Apply One-Hot Encoding.
- Transform categorical features into numerical values.

### 6. Missing Values Handling
- Handle missing values in the Embarked column.
- Fill missing Age values using the median.

### 7. Feature Scaling
- Apply RobustScaler.
- Scale numerical features: Age, SibSp, Parch, and Fare.

### 8. Class Imbalance Analysis
- Analyze the distribution of the target variable (Survived).
- Identify moderate class imbalance.
- Examine the distribution using a count plot.

## 📁 Dataset
Titanic Dataset from Kaggle.

[Dataset Link](https://www.kaggle.com/competitions/titanic/data)

## 📚 Key Learning Outcomes
- Data exploration and cleaning.
- Missing values handling.
- Outlier detection using IQR.
- Feature engineering.
- Label Encoding and One-Hot Encoding.
- Feature scaling using RobustScaler.
- Class imbalance analysis.

## 🚀 Future Work
- Apply Machine Learning classification algorithms.
- Train and evaluate predictive models.
- Compare model performance.

## 👨‍💻 Author
**Abdulaziz Jamal**

[GitHub Profile](https://github.com/AbdulazizJamal)
