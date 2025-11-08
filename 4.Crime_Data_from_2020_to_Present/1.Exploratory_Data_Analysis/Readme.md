# Exploratory Data Analysis — Crime Data (2020 to Present)

This folder focuses on **visual analysis and insights** derived from the Los Angeles crime dataset spanning **2020 to the present**. The aim is to identify crime patterns across time, area, type, and reporting behavior.

---

## 1️⃣ Yearly Crime Distribution (LAPD)

![Yearly Crime Distribution (LAPD)](Yearly%20Crime%20Distribution%20\(LAPD\).png)

**Insight:**

* Overall crime counts peaked in **2022**, showing a slight drop in 2023 and a steep fall in 2024–2025 (incomplete data likely).
* The trend suggests post-pandemic fluctuations, possibly due to reporting behavior or real decreases in incidents.

---

## 2️⃣ Crime Trend Over Years by Area

![Crime Trend Over Years by Area](Crime%20Trend%20Over%20Years%20by%20Area.png)

**Insight:**

* **Central**, **77th Street**, and **Pacific** divisions report the highest consistent crime counts across years.
* A visible decline begins around 2023, particularly in high-crime zones.
* 2024–2025 lines sit much lower, indicating fewer reports or unrecorded data.

---

## 3️⃣ Area-wise Crime Distribution

![Area-wise Crime Distribution](Area-wise%20Crime%20Distribution.png)

**Insight:**

* **Central (≈69K)** tops the chart, followed by **77th Street**, **Pacific**, and **Southwest**.
* The lower half (Mission, Hollenbeck, Foothill) shows less than 40K incidents — nearly half of Central’s volume.
* This imbalance hints at area-specific factors like population density or patrol distribution.

---

## 4️⃣ Month-wise Crime Volume

![Month-wise Crime Volume](Month-wise%20Crime%20Volume.png)

**Insight:**

* **January** consistently sees the highest reported crimes (~92K), while **November–December** show the lowest (~78K–79K).
* This seasonal trend may align with holiday effects or fewer active patrol reports.

---

## 5️⃣ Crime Trend by Day

![Crime Trend by Day](Crime%20Trend%20by%20Day.png)

**Insight:**

* **Friday** stands out with the highest daily average (~153K crimes), suggesting higher weekend activity or nightlife-related offenses.
* **Tuesday and Sunday** are the least active days.

---

## 6️⃣ Time-wise Crime Trend

![Time-wise Crime Trend](Time-wise%20Crime%20Trend.png)

**Insight:**

* Crime peaks during the **Evening Rush (18–22 hrs)** with over **220K incidents**.
* Lowest counts occur **Late Evening (22–24 hrs)** and **Morning Rush (6–10 hrs)**.
* Suggests high activity around commute hours and public gathering times.

---

## 7️⃣ Part 1 vs Part 2 Crime Comparison

![Part 1 vs Part 2 Crime Comparison](Part%201%20vs%20Part%202%20Crime%20Comparison.png)

**Insight:**

* **Part 1 crimes (60%)** — serious offenses like homicide, assault, and robbery — dominate the dataset.
* **Part 2 crimes (40%)** involve less severe offenses like vandalism or minor thefts.
* The ratio shows a strong emphasis on serious reported crimes.

---

## 8️⃣ Reporting Delays

![Reporting Delays](Reporting%20Delays.png)

**Insight:**

* Majority (≈480K) of crimes are reported **the same day**, with a steep drop-off afterward.
* **1–3 day delays** are common, while reports beyond **90 days** are rare (<20K).
* Indicates high immediacy in reporting, crucial for investigation timelines.

---

## 9️⃣ Top 10 Most Frequent Crime Categories

![Top 10 Most Frequent Crime Categories](Top%2010%20Most%20Frequent%20Crime%20Categories.png)

**Insight:**

* **Vehicle Theft** leads by a large margin (115K+ cases), followed by **Simple Assault** and **Burglary from Vehicle**.
* The top five categories are theft-related or property crimes, showing strong urban opportunistic crime patterns.
* **Identity theft** remains notably high — pointing toward growing cyber/financial offenses.

---

## Summary of Insights

| Category        | Key Findings                                                       |
| --------------- | ------------------------------------------------------------------ |
| **Time**        | Crime peaks during evenings and Fridays.                           |
| **Location**    | Central, 77th Street, and Pacific are persistent hotspots.         |
| **Seasonality** | Early-year months (Jan–Mar) show the highest activity.             |
| **Crime Type**  | Theft and assault dominate reported cases.                         |
| **Reporting**   | Most crimes are reported within 3 days, ensuring data reliability. |

---

## Notes

* All visuals were generated using **matplotlib** and **seaborn** in Jupyter Notebooks.
* Data cleaning and transformation steps are handled in `Data_Cleaning_&_Transforming.ipynb`.
* This EDA serves as the base for trend forecasting and dashboard integration in future phases.

---

## Author
**Utkarsh Naik**
