# 📊 Employee Pay Equity and Job Market Analysis

## Project Overview

Employee Pay Equity and Job Market Analysis is a data analytics project that uses Python, Pandas, NumPy, Matplotlib, Seaborn, and Microsoft Power BI to explore employee salary patterns and workforce characteristics.

The project focuses on understanding the relationship between employee salaries, work experience, age, department, gender, education level, tenure, and performance ratings.

The main objective is to transform raw employee data into meaningful insights through data cleaning, exploratory data analysis, statistical analysis, data visualization, and interactive dashboard development.

## 🎯 Project Objectives

- Analyze employee salary distributions.
- Understand salary differences across departments.
- Study the relationship between work experience and salary.
- Analyze employee distribution by gender.
- Explore the relationship between employee age and experience.
- Examine employee tenure and performance ratings.
- Identify missing values, duplicate records, and salary outliers.
- Create visualizations and an interactive Power BI dashboard.

## 🛠️ Technologies Used

| Technology | Purpose |
|---|---|
| Python | Data analysis and processing |
| Google Colab | Development environment |
| Pandas | Data manipulation and cleaning |
| NumPy | Numerical operations |
| Matplotlib | Data visualization |
| Seaborn | Statistical visualization |
| Scikit-learn | Data preprocessing and scaling |
| Plotly | Interactive visualization |
| Power BI | Interactive dashboard development |

## 📂 Project Structure

```text
Employee-Pay-Equity-Analysis/
│
├── BETN1DS25024l.ipynb
│
├── employee_pay_equity_messy.csv
│
├── cleaned_dataset_employee_pay_equity_messy.csv
│
├── mahi power bi FINAL.pbix
│
└── README.md
```

## 📌 Project Workflow

### Step 1: Foundations and Problem Framing

- Loaded the employee dataset using Pandas.
- Examined the number of rows and columns.
- Identified column names and data types.
- Generated descriptive statistical summaries.
- Analyzed unique values and missing values.
- Identified numerical and categorical columns.

### Step 2: Data Handling Using NumPy and Pandas

- Selected specific columns and records.
- Used indexing and slicing.
- Filtered employees based on experience.
- Sorted employee records.
- Analyzed department and country distributions.
- Created cross-tabulations and pivot tables.
- Performed grouping and merging operations.
- Exported sample data into CSV format.

### Step 3: Data Preprocessing and Analysis

The following preprocessing techniques were applied:

- Duplicate record identification and removal.
- Missing value identification.
- Median imputation for numerical columns.
- Mode imputation for categorical columns.
- Data type conversion.
- Date formatting and feature extraction.
- Outlier identification using the IQR method.
- Salary amount extraction from raw salary values.
- Categorical variable encoding.
- Standardization using StandardScaler.
- Normalization using MinMaxScaler.

### Step 4: Exploratory Data Analysis

The project explores several important relationships:

1. Relationship between employee age and years of experience.
2. Relationship between work experience and salary.
3. Relationship between employee tenure and performance score.
4. Department-wise relationship between experience and salary.
5. Average salary across departments.
6. Employee distribution by gender and department.
7. Employee count across departments.
8. Salary distribution across different pay bands.

Correlation analysis and grouping techniques were used to explore these relationships.

### Step 5: Data Visualization

Python visualization libraries were used to create:

- Employee Age Distribution.
- Employee Count by Department.
- Years of Experience Distribution.
- Missing Values Heatmap.
- Salary Distribution Boxplot.
- Correlation Heatmap.
- Age vs Experience Regression Plot.
- Experience vs Salary Regression Plot.
- Tenure vs Performance Regression Plot.

### Step 6: Power BI Dashboard

Microsoft Power BI was used to create an interactive dashboard for employee pay equity analysis.

The verified report visuals include:

- Employee count by gender.
- Employee distribution by education level.
- Department-wise employee and gender information.

The dashboard uses employee information from the cleaned dataset to support visual exploration and comparison.

## 📈 Key Analysis Areas

| Analysis | Purpose |
|---|---|
| Salary Analysis | Understand salary distribution |
| Department Analysis | Compare employee distribution across departments |
| Gender Analysis | Explore workforce representation |
| Experience Analysis | Examine experience and salary relationships |
| Performance Analysis | Explore performance and employee tenure |
| Education Analysis | Understand employee education distribution |
| Correlation Analysis | Identify relationships between numerical variables |

## 💻 How to Run the Project

**1. Clone the repository**

```bash
git clone https://github.com/your-username/Employee-Pay-Equity-Analysis.git
```

**2. Open the project folder**

```bash
cd Employee-Pay-Equity-Analysis
```

**3. Install the required libraries**

```bash
pip install pandas numpy matplotlib seaborn scikit-learn plotly statsmodels ipywidgets
```

**4. Open Google Colab**

Upload the notebook and the original dataset:

`BETN1DS25024l.ipynb`

`employee_pay_equity_messy.csv`

**5. Run the notebook**

Execute the notebook cells in sequence to perform data loading, preprocessing, analysis, and visualization.

**6. Open the Power BI dashboard**

Open `mahi power bi FINAL.pbix` using Microsoft Power BI Desktop.

## 🎓 Learning Outcomes

Through this project, I gained practical experience in:

- Python programming for data analytics.
- Data cleaning and preprocessing.
- Working with NumPy and Pandas.
- Exploratory Data Analysis (EDA).
- Statistical correlation analysis.
- Data visualization.
- Data transformation and feature engineering.
- Interactive dashboard development using Power BI.

## 🔮 Future Improvements

- Develop a salary prediction model.
- Perform more detailed pay equity comparisons.
- Add advanced interactive dashboard filters.
- Explore machine learning techniques.
- Improve department-wise and experience-wise salary comparisons.

## 👨‍💻 Project Information

**Project Title:** Employee Pay Equity and Job Market Analysis

**Student Name:** M. Mahendra

**Roll Number:** BETN1DS25024

**Branch:** Data Science

**University:** ITM University

**Project Domain:** Data Analytics and Visualization

## 🏁 Conclusion

This project demonstrates how Python and Power BI can be used together to analyze employee salary information and workforce characteristics.

By applying data preprocessing, exploratory data analysis, statistical techniques, and visualization, the project provides a structured approach to understanding salary patterns, employee distribution, experience, and performance.

The project also demonstrates the importance of transforming raw data into meaningful information that can support better data-driven decision-making.

---

⭐ If you find this project useful, consider giving this repository a star!
