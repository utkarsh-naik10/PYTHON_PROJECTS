# 📈 3. Skills Trend Analysis

## 📘 Introduction
This notebook explores how the **demand for different skills** in data-related roles — particularly *Data Analysts* — has evolved over time.  
By analyzing monthly job postings and associated skills, the project identifies trends that reveal which technologies are rising or declining in popularity.

---

## 🧩 Background
The data industry evolves rapidly, with new tools and programming languages emerging every year.  
This analysis investigates **temporal trends** in job skill requirements to answer:
- Which technical skills are gaining momentum?
- Are traditional tools still relevant?
- How do monthly posting trends reflect shifts in demand?

Understanding these trends helps job seekers and educators prioritize relevant skills in an ever-changing job market.

---

## 🛠️ Tools & Libraries Used
- **Python**
- **Pandas** → Data manipulation and time-based grouping  
- **Matplotlib & Seaborn** → Trend visualization over months  
- **Datetime** → Extracting month and year from job posting dates  
- **AST** → Parsing skill lists stored as strings  

---

## 🔍 Analysis Performed
1. **Data Cleaning**
   - Converted `job_posted_date` to `datetime`.  
   - Parsed `job_skills` column from stringified lists into Python lists.  
   - Filtered data for `Data Analyst` roles.

2. **Feature Engineering**
   - Extracted posting month using `dt.month`.  
   - Created a mapping from month number to month abbreviation.

3. **Skill Trend Analysis**
   - Counted occurrences of each skill per month.  
   - Created visualizations showing skill frequency trends.  
   - Compared top 5 or 10 most common skills over time.

---

## 💡 What I Learned
- How to analyze **time-series patterns** in categorical data.  
- Effective use of **groupby()** and **pivot tables** for monthly summaries.  
- How to visualize **dynamic skill demand** using line and area charts.  

---

## 📊 Insights
- **SQL** and **Python** remain consistently dominant across months.  
- Tools like **Power BI**, **Tableau**, and **Excel** show seasonal demand variation.  
- **Cloud-based tools** and **advanced analytics platforms** are showing upward momentum.  
- The number of job postings varies seasonally, reflecting hiring cycles.

---

## 🧾 Conclusion
Skill trend analysis reveals how **data-related job requirements evolve over time**:
- Core tools remain essential, but **visualization and cloud technologies** are on the rise.  
- Continuous learning and adaptability are key for data professionals.  
- This analysis helps forecast the **future skill landscape** and guide targeted upskilling.

