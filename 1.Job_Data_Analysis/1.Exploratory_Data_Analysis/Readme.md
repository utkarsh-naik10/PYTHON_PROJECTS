# 🧭 1. Exploratory Data Analysis

## 📘 Introduction
This notebook performs an **Exploratory Data Analysis (EDA)** on job market data for data-related roles. The goal is to understand the structure of the dataset, identify patterns, clean and prepare the data, and derive meaningful preliminary insights about job postings, locations, and required skills.

---

## 🧩 Background
The dataset `Job_Data_Analysis.csv` contains job listings for various data roles such as Data Analyst, Data Scientist, and Data Engineer. Each record includes job title, company information, salary, required skills, job location, and other relevant details.  
The EDA phase is critical to uncover data quality issues, detect anomalies, and generate hypotheses for deeper analysis in later stages.

---

## 🛠️ Tools & Libraries Used
- **Python**
- **Pandas** → Data manipulation and cleaning  
- **Matplotlib & Seaborn** → Data visualization and pattern exploration  
- **AST (Abstract Syntax Trees)** → To safely parse skill lists stored as strings  
- **NumPy** → Basic numerical operations  

---

## 🔍 Analysis Performed
1. **Data Cleaning**
   - Converted `job_posted_date` to datetime format  
   - Handled missing or inconsistent entries  
   - Converted stringified lists in `job_skills` to actual Python lists  

2. **Data Filtering**
   - Focused on records where `job_title_short == 'Data Analyst'`  
   - Prepared subsets for later analysis (e.g., salary, skills, companies, etc.)

3. **Initial Data Exploration**
   - Inspected data structure and sample rows  
   - Checked for nulls and data types  
   - Identified columns relevant for further analysis phases  

---

## 💡 What I Learned
- How to **structure a dataset** for analysis using Pandas  
- Techniques to handle **stringified lists** and **date columns**  
- The importance of **EDA in guiding deeper investigations** (e.g., skill trends, salary distributions)

---

## 📊 Insights
- The dataset contains detailed job postings across multiple countries.  
- Many roles mention **skills as lists**, requiring parsing for analysis.  
- Salary and location columns show wide variability, suggesting significant regional differences.

---

## 🧾 Conclusion
The EDA phase provided a clear understanding of the dataset’s structure and quality. The cleaned and filtered data now serves as a solid foundation for the next analytical stages:
- **Most In-Demand Skills**
- **Skill Trends**
- **Salary Analysis**
- **Optimal Skill Combination**
