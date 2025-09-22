# 🚢 Titanic Survival Data Analysis & Prediction

## 📌 Project Overview
This project explores the famous **Titanic dataset** to analyze passenger survival patterns and apply preprocessing, visualization, and machine learning techniques.  
The analysis covers **data cleaning, exploratory data analysis (EDA), visualization, and survival prediction models**.

---

## 📂 Dataset Information
- **Source:** [Titanic Dataset](https://www.kaggle.com/datasets/yasserh/titanic-dataset)  
- **Description:** Contains details of 891 passengers including:
  - Passenger ID, Name, Age, Gender
  - Ticket class, Cabin, Fare
  - Embarkation point
  - Survival status (0 = Did not survive, 1 = Survived)

---

## 🎯 Objectives
- Clean and preprocess Titanic dataset  
- Handle missing values & categorical encoding  
- Perform Exploratory Data Analysis (EDA)  
- Visualize trends in survival by **gender, age, class, fare, embarkation**  
- Build machine learning models to predict survival  

---

## 🛠️ Technologies & Libraries Used
- **Language:** Python 3  
- **Libraries:**
  - Data Handling → `pandas`, `numpy`
  - Visualization → `matplotlib`, `seaborn`
  - Machine Learning (optional) → `scikit-learn`

---

## 🔄 Data Preprocessing
Steps performed:
1. Handling **missing values** (Age, Cabin, Embarked)  
2. Encoding **categorical features** (Sex, Embarked)  
3. Creating new **features** (Family Size, Title, etc.)  
4. Scaling and normalizing numerical features  

---

## 📊 Exploratory Data Analysis (EDA)
Some insights discovered:
- **Gender:** Women had a much higher survival rate than men.  
- **Class:** Passengers in **1st class** survived more compared to 3rd class.  
- **Age:** Children had a higher chance of survival than adults.  
- **Embarkation Point:** Passengers from port "C" had higher survival rates.  

### Example Visualizations
- Bar plots of survival by gender and class  
- Violin plots for age distribution across classes  
- Heatmaps of feature correlations  

(Add screenshots of your graphs here 👇)  

---

## 🤖 Modeling (Optional)
If ML models are included, mention:
- Logistic Regression
- Decision Tree
- Random Forest
- Model performance (Accuracy, Precision, Recall, F1-score)

---

## 📂 Project Structure
