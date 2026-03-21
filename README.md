# SCT_DS_2
# 🚢 Titanic Data Analysis (EDA)

## 📌 Project Overview
This project performs Exploratory Data Analysis (EDA) on the Titanic dataset to understand the factors influencing passenger survival. The goal is to clean the data, analyze relationships, and extract meaningful insights using visualizations.

---

## 📂 Dataset
- Source: Kaggle Titanic Dataset
- File used: `train.csv`
- Rows: 891 passengers
- Features: Age, Gender, Class, Fare, Survival, etc.

---

## 🛠️ Tools & Libraries
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
-google colab
---

## 🔍 Data Cleaning Steps
- Filled missing values in **Age** using median
- Filled missing values in **Embarked** using mode
- Dropped **Cabin** column (too many missing values)
- Checked for null values and data types

---

## 📊 Exploratory Data Analysis
- Survival distribution analysis
- Survival by gender comparison
- Correlation heatmap
- Feature relationships (Age, Fare, Class)

---

## 📈 Key Insights
- 👩 Females had a significantly higher survival rate than males  
- 🎟️ Passengers in higher class (Pclass 1) had better survival chances  
- 💰 Higher fare correlates with higher survival probability  
- 👶 Age had a slight impact, but not as strong as gender/class  
- 👨‍👩‍👧 Family size (SibSp & Parch) shows moderate relationship  

---

## 📷 Visualizations
- Count plots for survival
- Survival by gender chart
- Correlation heatmap

---

## 📁 Project Structure
Titanic-EDA/
│── Task02.ipynb
│── train.csv
│── README.md
## 💡 Conclusion
This analysis highlights how data cleaning and visualization can uncover meaningful patterns in real-world datasets. Factors like gender and passenger class had a strong influence on survival, while age played a smaller role. The project demonstrates the importance of EDA in understanding data before applying machine learning.

---
