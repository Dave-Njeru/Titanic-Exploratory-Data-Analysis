# Titanic-Exploratory-Data-Analysis
📌 **Project Overview**

This project focuses on performing **Exploratory Data Analysis (EDA)** using a Kaggle dataset. The aim is to understand the structure, patterns, relationships, and key insights within the data through systematic analysis and visualization.

Data source: <br>
👉 [EDA Masterclass Guide](https://www.kaggle.com/code/mariyamalshatta/masterclass-1-a-comprehensive-guide-for-eda)

The dataset used is the classic Titanic dataset, which contains passenger information such as age, gender, class, fare, and survival status.

---
🎯 **Objectives**

The purpose of this project is to practice key EDA steps:
- Initial Data Exploration
- Handling Missing Values and Outliers
- Univariate Analysis
- Bivariate Analysis
- Multivariate Analysis
- Target Variable Analysis

---
🛠️ **Tools and Libraries Used**
- Python
- Kaggle
- Pandas
- Numpy
- Matplotlib
- Seaborn

---
📂 **Project Workflow**

🔍 **1. Initial Data Exploration** <br>
Performed basic inspection of the dataset using:
```python
df.head()
df.shape
df.info()
df.describe()
df.columns
df.nunique()
df.duplicated().sum()
```
**Key Checks**
- Data types of each feature
- Missing values
- Duplicate records
- Unique values per column
- General data quality issues

---
🧹 **2: Handling Missing Values and Errors**
- Identify missing values in features like:
  - `Age`
  - `Cabin`
  - `Embarked`

**Strategies Used:**
- Imputation (mean/median for Age)
- Dropping columns with excessive missing values (e.g., Cabin)
- Filling categorical values with mode

---
📈 **3. Univariate Analysis**
- Analyzed each feature independently to understand distributions.

**Examples:**
- Age distribution of passengers
- Count of passengers per embarkation point
- Distribution of ticket fares

**Techniques Used:**
- Histograms
- Count plots
- Box plots

---
🔗 **4. Bivariate Analysis**
- Explored relationships between two variables.

**Key Questions:**
- Does fare vary by passenger class?
- Are younger passengers more likely to survive?
- Does embarkation location affect survival rate?

**Techniques Used:**
- Scatter plots
- Box plots
- Grouped bar charts

---
🧠 **5. Multivariate Analysis**
- Analyzed interactions between multiple variables simultaneously.

**Examples:**
- Combined effect of `Pclass`, `Age`, and `Fare` on survival
- Survival trends across embarkation points and passenger class

**Techniques Used:**
- Heatmaps
- Pair plots
- Grouped visualizations

---
⚠️ **6. Outlier Detection and Handling**
- Detected outliers using:
  - Box plots
  - Statistical methods

**Handling Approaches:**
- Capping extreme values
- Retaining outliers where they provide meaningful insights

**Example:**
- Outliers in `Fare` may represent wealthy passengers and should not always be removed.

---
🎯 **7. Target Variable Analysis**
- Focused on the `Survived` variable.

**Key Insights:**
-Distribution of survivors vs non-survivors
-Dataset balance (imbalanced vs balanced)

**Factors Affecting Survival:**
- Gender
- Passenger class
- Age
- Embarkation point
  
**Techniques Used:**
- Count plots
- Bar charts
- Grouped comparisons

---
📁 **File Structure**
```
project/
|-- eda_titanic.ipynb
|-- README.md
```

---
▶️ **How to Run the Project**
1. Open the notebook in Kaggle
2. Install required libraries:
   ```bash
   pip install pandas numpy matplotlib seaborn
   ```
3. Run all cells step by step
4. Review visualizations and insights

---
✅ **Key Learnings**
- Understanding dataset structure and quality
- Handling missing data and outliers effectively
- Performing different levels of data analysis
- Identifying patterns and relationships in data
- Communicating insights using visualizations

---
⚠️ **Disclaimer**

This project is for educational purposes only. The dataset is publicly available on Kaggle.
