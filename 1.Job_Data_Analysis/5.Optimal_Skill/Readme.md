# 🧠 5. Optimal Skill Analysis

## 📘 Introduction
This notebook identifies the **optimal skill set** for Data Analysts — those that strike the best balance between **high demand** and **high salary**.  
By analyzing both skill frequency and average pay, this study helps data professionals understand which tools, technologies, and languages offer the **highest return on investment** in the job market.

---

## 🧩 Background
The data analytics field requires a blend of technical and analytical skills. However, not all skills contribute equally to career growth or salary advancement.  
This analysis focuses on:
- Determining which **skills are most common** among job postings.
- Finding which **skills correspond to higher median salaries**.
- Identifying the **optimal combination** of in-demand and well-paid skills for Data Analysts.

---

## 🛠️ Tools & Libraries Used
- **Python**
- **Pandas** → Data filtering, grouping, and aggregation  
- **Seaborn & Matplotlib** → Visualization of skill pay and demand comparison  
- **AST** → Parsing skill data from text format  
- **Numpy** → Numerical operations  

---

## 🔍 Analysis Performed
1. **Data Cleaning**
   - Parsed `job_skills` list safely using `ast.literal_eval()`.  
   - Filtered dataset for **Data Analyst** roles.  
   - Removed rows with missing salary information.

2. **Skill Extraction & Analysis**
   - Expanded skills using `explode()` to assign one skill per row.  
   - Calculated:
     - **Median salary per skill**
     - **Skill frequency (demand)**

3. **Optimal Skill Identification**
   - Merged both datasets (salary & demand) to find high-salary, high-demand skills.  
   - Created scatter plots comparing salary vs. popularity.  
   - Highlighted skills in the **top-right quadrant** as “optimal.”

---

## 💡 What I Learned
- How to integrate **salary data** and **demand metrics** for multi-factor analysis.  
- How to use **visual analytics** to highlight optimal trade-offs.  
- The practical application of `explode()` and `groupby()` for text-based skill analysis.  

---

## 📊 Insights
- **SQL** and **Python** are both **highly in-demand** and **well-paying**, making them core skills for any Data Analyst.  
- **Tableau**, **Power BI**, and **Excel** remain key for reporting and visualization.  
- **Cloud tools** (AWS, Azure) and **automation platforms** (Alteryx) offer salary advantages despite lower demand.  
- Combining programming, visualization, and cloud knowledge results in an **optimal skill mix**.  

---

## 🧾 Conclusion
The analysis reveals that the most **optimal skills** for Data Analysts balance **market demand** with **earning potential**:
- 🔹 Core: SQL, Python  
- 🔹 Visualization: Tableau, Power BI  
- 🔹 Bonus: AWS, Alteryx  

These findings guide professionals toward targeted upskilling strategies that maximize employability and salary growth.
