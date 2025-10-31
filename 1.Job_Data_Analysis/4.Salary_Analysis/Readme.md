# 💰 4. Salary Analysis

## 📘 Introduction
This notebook explores **how well different data jobs and skills pay**, focusing on both **role-based** and **skill-based** salary comparisons.  
The analysis helps uncover which positions offer the highest compensation and which technical skills correlate with higher salaries in the data analytics field.

---

## 🧩 Background
The dataset provides detailed job postings, including salary data, company information, and required skills.  
By analyzing salary patterns across roles and skills, we can better understand the **market value of technical competencies** in the data domain and how they vary by job level.

This analysis aims to answer:
- Which **data roles** offer the highest median salaries?  
- Which **skills** are most lucrative for **Data Analysts**?  
- How do salaries differ between **junior** and **senior** positions?

---

## 🛠️ Tools & Libraries Used
- **Python**
- **Pandas** → Data manipulation and aggregation  
- **Matplotlib & Seaborn** → Salary visualization and comparison  
- **Datetime** → Handling job posting dates  
- **NumPy** → Statistical computation  

---

## 🔍 Analysis Performed
1. **Data Preparation**
   - Filtered records containing valid yearly salary data (`salary_year_avg`).  
   - Focused on top 6 job titles (Data Analyst, Data Scientist, Data Engineer, and senior variants).  

2. **Role-Based Salary Distribution**
   - Used `Seaborn` boxplots to visualize salary spread across roles.  
   - Sorted job titles by **median salary**.  
   - Converted salary scale to a readable “K” format (e.g., 100K, 200K).

3. **Skill-Based Salary Analysis**
   - Isolated `Data Analyst` roles.  
   - Calculated **median salaries by skill**.  
   - Identified top 10 **highest-paying skills** for Data Analysts.  

4. **Comparison & Insights**
   - Compared high-demand vs. high-paying skills.  
   - Observed differences between analytical and programming tools.

---

## 💡 What I Learned
- How to use **boxplots** to reveal salary distribution and outliers.  
- How to combine **groupby()** with **median aggregation** for ranking.  
- The strong correlation between **technical depth** and **salary level**.  

---

## 📊 Insights
- **Senior Data Scientists** and **Senior Data Engineers** command the highest salaries.  
- **Python**, **AWS**, and **SQL** appear frequently among high-paying roles.  
- **Visualization tools** (e.g., Tableau, Power BI) also correlate with strong pay for Data Analysts.  
- Entry-level and analyst roles show tighter salary bands compared to senior or engineering positions.

---

## 🧾 Conclusion
Salary analysis reveals a clear trend — **advanced technical and cloud-based skills drive higher compensation**.  
Key takeaways:
- Invest in programming (Python, SQL) and cloud platforms (AWS, Azure).  
- Specialization leads to higher salaries in the long term.  
- Data roles show diverse pay scales, reflecting growing specialization in analytics and engineering.

This analysis provides a clear salary benchmark for aspiring data professionals and organizations aiming to attract top talent.
