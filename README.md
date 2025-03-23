# Understanding-Passenger-Survival-on-the-Titanic
Insights into passenger demographics and survival probabilities
# 🚢 Understanding Passenger Survival on the Titanic

![Titanic](https://upload.wikimedia.org/wikipedia/commons/f/fd/RMS_Titanic_3.jpg)

## 📌 Overview
This project explores passenger survival on the Titanic using **Exploratory Data Analysis (EDA)**. The goal is to identify factors that influenced survival rates and gain insights into the data.  

## 📂 Dataset Information
- **Dataset Source**: [Titanic Dataset (Kaggle)](https://www.kaggle.com/competitions/titanic/data)  
- **Columns Include**:  
  - `Survived` (Target Variable: 0 = No, 1 = Yes)  
  - `Pclass` (Passenger Class: 1st, 2nd, 3rd)  
  - `Sex` (Male/Female)  
  - `Age`, `Fare`, `SibSp`, `Parch`, etc.  

## 🔍 Steps in the Analysis  
This project follows a structured **EDA** process:  
1. **Data Loading**: Read the dataset using Pandas.  
2. **Data Cleaning**: Handle missing values and remove duplicates.  
3. **Feature Engineering**: Create new variables like `FamilySize` and `Title`.  
4. **Visualizations**: Generate insights using histograms, bar charts, and heatmaps.  
5. **Correlation Analysis**: Identify relationships between variables and survival.  
6. **Summary of Findings**: Key insights from the analysis.  

## 📊 Visualizations  
Here are some visual insights from the dataset:  
### **Survival Rate by Passenger Class**  
<img src="images/survival_bar_chart.png" width="500">

### **Correlation Heatmap**  
<img src="images/correlation_heatmap.png" width="500">  

## 🚀 How to Use  
To run this project on your local machine:  
```bash
git clone https://github.com/AfnanNadeem-13/Understanding-Passenger-Survival-on-the-Titanic.git
cd Understanding-Passenger-Survival-on-the-Titanic
jupyter notebook
