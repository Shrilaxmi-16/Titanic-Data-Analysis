# 🚢 Titanic Data Analysis and Preprocessing

## 📌 Project Overview
This project focuses on analyzing and preprocessing the Titanic passenger dataset to understand factors influencing survival and prepare the data for predictive modeling. It involves cleaning the dataset, performing exploratory data analysis (EDA), feature engineering, and transforming data to make it suitable for machine learning algorithms.

## Key Objectives
- **Data Understanding**: Explore dataset structure, features, and target variable (`Survived`).
- **Data Cleaning & Preprocessing**: Handle missing values, duplicates, and encode categorical features.
- **Exploratory Data Analysis (EDA)**: Visualize patterns and relationships using bar charts, histograms, violin plots, and boxplots.
- **Feature Engineering**: Create meaningful features (e.g., family size, title extraction) and select relevant attributes.
- **Preparation for Modeling**: Split data into training and testing sets, ensuring clean, usable data for predictive modeling.

## Technologies Used
- **Python**
- **Pandas** – Data manipulation and preprocessing
- **NumPy** – Numerical computations
- **Matplotlib & Seaborn** – Data visualization
- **Jupyter Notebook** – Interactive coding environment

## 📂 Dataset
The dataset used is the Titanic passenger dataset, available from [Titanic Dataset](https://www.kaggle.com/datasets/yasserh/titanic-dataset)). It contains information such as:

- PassengerId
- Survived (target variable)
- Pclass (Passenger class)
- Name
- Sex
- Age
- SibSp (siblings/spouses aboard)
- Parch (parents/children aboard)
- Ticket
- Fare
- Cabin
- Embarked (Port of Embarkation)

## Data Preprocessing Steps
1. Handle missing values (e.g., fill missing Age with median, drop missing Embarked).
2. Encode categorical variables (Sex, Embarked) using label or one-hot encoding.
3. Create new features (e.g., FamilySize = SibSp + Parch + 1, Title from Name).
4. Drop irrelevant columns (e.g., Ticket, Cabin) or transform them as needed.
5. Scale or normalize numerical features if required.

## Exploratory Data Analysis (EDA)
Visualizations help understand data distribution and feature relationships:

- **Survival Distribution**  
  ![Survival Distribution](images/sdistribution.png)

- **Survival by Gender**  
  ![Survival by Gender](images/survivalbygender.png)

- **Survival by Passenger Class**  
  ![Survival by Class](images/Pclass.png)

- **Age Distribution of Passengers**  
  ![Age Distribution](images/4.png)



## Machine learning Models
- **Logistic Regression:** Predicts survival using a linear combination of features.  
- **Decision Tree:** Classifies passengers based on feature splits like age, sex, and class.  
- **Random Forest:** Ensemble model improving accuracy by combining multiple decision trees.  
- **K-Nearest Neighbors (KNN):** Predicts survival based on the majority class of nearest passengers.  
- Model performance (Accuracy, Precision, Recall, F1-score)

## How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/titanic-data-analysis.git
