# 🚢 Titanic Survival Analysis  
Machine Learning • EDA • YData Profiling

## 📘 Project Overview
This project analyzes the **Titanic Dataset** to identify key factors that influenced passenger survival.  
It involves:

- Data Cleaning & Preprocessing  
- Exploratory Data Analysis (EDA)  
- Automated Data Profiling using **YData Profiling**  
- Building machine learning models to predict survival  
- Visualizing insights from the dataset  

---

## 📂 Repository Structure
├── Analysing_Survival_on_the_Titanic.ipynb # Jupyter Notebook

├── Titanic-Dataset.csv # Dataset

├── report.html # YData Profiling Report

└── README.md # Project Documentation

yaml
Copy code

---

## 📊 Dataset Information
The dataset used: **Titanic-Dataset.csv**  
It contains the following major features:

- Survived  
- Pclass  
- Name  
- Sex  
- Age  
- SibSp  
- Parch  
- Ticket  
- Fare  
- Cabin  
- Embarked  

This dataset is widely used for classification and pattern recognition tasks.

---

## 🔍 Data Profiling
A complete profiling report was generated using **YData Profiling** (previously Pandas Profiling).

📄 **report.html** gives:  
- Feature summary  
- Missing values  
- Correlation heatmap  
- Data types  
- Outlier detection  
- Sample records  

---

## 🧪 Project Workflow

### ✔️ 1. Importing Libraries  
Loading required Python libraries for analysis.


### ✔️ 2. Data Cleaning  
- Handling missing values  
- Converting datatypes  
- Encoding categorical variables  


### ✔️ 3. EDA (Exploratory Data Analysis)  
- Distribution plots  
- Comparison between survived vs non-survived  
- Feature correlation analysis  


### ✔️ 4. Machine Learning Models  
Models used:

- Logistic Regression  
- Decision Tree  
- Random Forest  


### ✔️ 5. Evaluation Metrics  
- Accuracy Score  
- Confusion Matrix  
- Classification Report  

---

## 📈 Key Insights
Some important findings:

- Females survived more than males  
- Passengers in **1st Class** had higher survival probability  
- Younger passengers tended to survive more  
- Higher fare correlated with better survival  

---

## ▶️ How to Run This Project

### **1. Clone the Repository**
```bash
git clone https://github.com/your-username/titanic-survival-analysis.git
```
### 2. Install Dependencies

Copy code
```bash
pip install -r requirements.txt
```

### 3. Run the Notebook

Copy code
```bash
jupyter notebook Analysing_Survival_on_the_Titanic.ipynb
```

📦 Requirements

nginx

pandas

numpy

matplotlib

seaborn

scikit-learn

ydata-profiling


