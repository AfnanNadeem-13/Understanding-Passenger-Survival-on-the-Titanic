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

🚢 Understanding Passenger Survival on the Titanic


📌 Table of Contents
Overview

Dataset Information

Key Findings

Installation

Visualizations

Conclusions

License

Contact

📖 Overview
🚢 Did wealth, age, or gender determine survival on the Titanic? This project explores the Titanic dataset using Exploratory Data Analysis (EDA) to uncover key insights into passenger survival rates.

Through visualizations and statistical analysis, we examine how different factors such as class, fare, age, and family size influenced survival.

📊 Dataset Information
The dataset used for this analysis is the Titanic Dataset from Kaggle. It includes details about passengers, such as:

Age, Gender

Ticket Class (1st, 2nd, 3rd)

Number of Siblings/Spouses Aboard

Number of Parents/Children Aboard

Ticket Fare

🔍 Key Findings
✅ Women had a higher survival rate than men.
✅ 1st class passengers survived more often than lower classes.
✅ Higher fares correlated with better survival chances.
✅ Passengers traveling alone had lower survival rates than those with family.

⚙️ Installation
To run this project locally, follow these steps:

bash
Copy
Edit
# Clone the repository
git clone https://github.com/AfnanNadeem-13/Understanding-Passenger-Survival-on-the-Titanic.git

# Navigate to the project directory
cd Understanding-Passenger-Survival-on-the-Titanic

# Install required dependencies
pip install -r requirements.txt

# Run Jupyter Notebook
jupyter notebook
📊 Visualizations
Below are some of the visualizations used in this project:

1️⃣ Survival Rate by Gender
2️⃣ Passenger Class Distribution
3️⃣ Age Distribution of Survivors vs. Non-Survivors
4️⃣ Correlation Heatmap (Feature Relationships)

🔹 Screenshot Example:



📌 Conclusions
Women and children had higher survival rates.

Wealthier passengers (higher ticket fare) had better chances of survival.

People traveling alone had lower survival rates compared to those with family members.

📝 License
This project is licensed under the MIT License.

📬 Contact
💡 Created by Afnan Nadeem
📧 Feel free to reach out for collaboration!
