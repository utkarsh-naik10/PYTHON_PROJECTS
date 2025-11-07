# NYC Motor Vehicle Collisions – Exploratory Data Analysis (EDA)

This project explores **motor vehicle collisions in New York City** to understand crash patterns, severity, and contributing factors using real-world open data.  
The goal is to identify **when, where, and why most crashes occur** and uncover trends that can help improve road safety and urban planning.

---

## 📘 Project Overview

The dataset contains detailed crash records from the **NYC Open Data Portal**, including date, time, location, borough, vehicle type, and cause of collision.  
Through data cleaning, visualization, and analysis, this project reveals key insights related to:
- Time-based crash trends  
- Severity and victim analysis  
- Vehicle involvement and fatality rates  
- Major contributing factors  
- Geographic crash hotspots  

> 📂 **Dataset Source:**  
> [Motor Vehicle Collisions – Crashes (NYC Open Data)](https://catalog.data.gov/dataset/motor-vehicle-collisions-crashes)

---

## 🗂️ Folder Structure

### **1. Exploratory_Data_Analysis/**
Initial data exploration, structure inspection, and missing value checks.  
Focuses on understanding dataset columns and preparing data for deeper analysis.  
> 📄 File: `1.Exploratory_Data_Analysis.ipynb`

---

### **2. Severity_&_Victim_Analysis/**
Analyzes how severe crashes are and their impact on different groups — pedestrians, cyclists, and motorists.  
> 🔍 **Key Insights:**  
> - Brooklyn records the **highest fatality count**.  
> - Around **99.5% of victims are injured** rather than killed.  
> - **Motorists** account for most injuries.

---

### **3. Vehicle_Type_Analysis/**
Examines vehicle types most involved in collisions and their fatality rates.  
> 🔍 **Key Insights:**  
> - **Sedans** lead in total crashes (~640K).  
> - **Motorcycles** have the **highest fatality rate (~2.5%)**, showing their high risk per crash.  
> - SUVs and passenger vehicles follow in frequency.

---

### **4. Contributing_Factors/**
Identifies the primary causes of crashes and their borough-wise variations.  
> 🔍 **Key Insights:**  
> - **Driver Inattention/Distraction** is the most common cause.  
> - A large share of cases are **“Unspecified”**, indicating incomplete reporting.  
> - **Brooklyn and Queens** report the most distracted driving crashes.

---

### **5. Geographic_Analysis/**
Explores crash hotspots across NYC based on **streets and zip codes**.  
> 🔍 **Key Insights:**  
> - **Broadway** is the most accident-prone street (~17K crashes).  
> - **Brooklyn’s 11207** zip code tops crash counts (~23K).  
> - Dense traffic corridors and expressways show the highest crash frequencies.

---

## 📊 Tools & Technologies Used

- **Language:** Python  
- **Libraries:** Pandas, NumPy, Matplotlib, Seaborn  
- **IDE:** Jupyter Notebook  
- **Visualization Style:** Simple, clear, and insight-focused  

---

## 🔍 Key Findings (Overall Summary)

| Category | Observation |
|-----------|--------------|
| **Peak Crash Time** | Afternoon (2–6 PM) |
| **Most Dangerous Day** | Friday |
| **Highest Crash Borough** | Brooklyn |
| **Riskiest Vehicle Type** | Motorcycle |
| **Top Contributing Factor** | Driver Inattention/Distraction |
| **Most Crash-Prone Street** | Broadway |
| **Top Crash Zip Code** | 11207 (Brooklyn) |

---

## 🧩 Future Improvements
- Apply **predictive modeling** to estimate crash likelihood.  
- Integrate **weather and traffic data** for deeper context.  

---

## 👨‍💻 Author
**Utkarsh Naik**  
Data Analyst  
Exploring real-world datasets to create meaningful insights and data stories.

---

## 📁 Folders Included
- `1.Exploratory_Data_Analysis/`  
- `2.Severity_&_Victim_Analysis/`  
- `3.Vehicle_Type_Analysis/`  
- `4.Contributing_Factors/`  
- `5.Geographic_Analysis/`

---

**Project Type:** Exploratory Data Analysis (EDA)  
**Dataset:** [Motor Vehicle Collisions – Crashes](https://catalog.data.gov/dataset/motor-vehicle-collisions-crashes)  
**Goal:** Understand NYC crash trends and support data-driven road safety improvements.
