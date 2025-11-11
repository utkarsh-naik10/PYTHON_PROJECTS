# Severity & Victim Analysis (2020 to Present)

This folder looks at how the severity of crimes and victim characteristics vary across Los Angeles crime data from 2020 onwards.  
It focuses on understanding victim profiles, weapon usage, and how age, gender, and descent relate to different types of crimes.

---

## 1️⃣ Age Group vs Crime Type

![Age Group vs Crime Type](Age%20Group%20vs%20Crime%20Type.png)

**Insights:**
- Most **vehicle thefts** are reported in the **0–12 age group**, likely due to registration or data entry structure (vehicle owners under guardian entries).
- **Assaults and simple assaults** are dominant among the **19–45** age range.
- Crimes like **shoplifting**, **burglary**, and **petty theft** are more frequent among **younger to mid-age groups (13–45)**.
- Very few crimes are linked to individuals above **60**, showing lower exposure or reporting rates.

---

## 2️⃣ Average Victim Age — Violent vs Non-Violent Crimes

![Average Victim Age for Violent vs Non-Violent Crimes](Average%20Victim%20Age%20for%20Violent%20vs%20Non-Violent%20Crimes.png)

**Insights:**
- Victims of **violent crimes** are on average **older (35.3 years)** compared to **non-violent crimes (26.2 years)**.
- This suggests that mature individuals are more likely to encounter physical or aggravated incidents, whereas younger groups face more theft-related offenses.

---

## 3️⃣ Crime Severity by Weapon Usage

![Crime Severity by Weapon Usage](Crime%20Severity%20by%20Weapon%20Usage.png)

**Insights:**
- **Strong-arm assaults** (hands, fists, or bodily force) dominate with over **170K cases**, showing physical altercations are the most common violent act.
- **Guns** and **knives** make up a smaller portion compared to overall force-based attacks.
- **Pepper spray** and **verbal threats** also appear, indicating varied levels of confrontation.

---

## 4️⃣ Top 5 Crime Types by Victim Gender

![Top 5 Crime Types by Victims Gender](Top%205%20Crime%20Types%20by%20Victims%20Gender.png)

**Insights:**
- **Female victims:** Face more **identity theft** and **simple assaults**, often within domestic or interpersonal settings.
- **Male victims:** Experience more **battery** and **aggravated assaults**, showing higher exposure to direct violence.
- **Unknown gender records:** Mostly linked to **vehicle theft**, which is consistent with missing personal fields in vehicle-related reports.
- **Transgender/Other victims:** Affected mainly by **burglary** and **theft**, though counts are limited due to small data size.

---

## 5️⃣ Victim Descent Distribution

![Victim Descent Distribution](Victim%20Descent%20Distribution.png)

**Insights:**
- **Hispanic/Latin/Mexican** victims represent the largest share (~296K cases), followed by **Unknown** and **White**.
- **Black** victims also show significant counts, reflecting urban demographic concentration.
- Asian and Pacific Islander groups have much lower numbers, likely linked to smaller population size or different reporting behavior.

---

## 6️⃣ Victim Descent vs Area Comparison

![Victim Descent vs Area Comparison](Victim%20Descent%20vs%20Area%20Comparisons.png)

**Insights:**
- **77th Street, Newton, and Hollenbeck** have high counts for both **Black** and **Hispanic/Latin** victims.
- **Pacific and Hollywood** show higher representation of **White** victims.
- The heatmap highlights strong area-ethnicity patterns, valuable for targeted safety programs.

---

## Summary of Key Learnings

| Category | Observation |
|-----------|--------------|
| **Victim Age** | Crimes mainly involve victims aged **19–45**. |
| **Crime Severity** | Physical force (no weapon) is the most common method in violent crimes. |
| **Gender Trends** | Women face more intimate partner or identity-related crimes; men face more physical aggression. |
| **Descent Trends** | Hispanic and Black communities are disproportionately affected in several areas. |
| **Weapons Used** | Firearms and knives contribute less than expected; unarmed assaults dominate. |

---

## Notes

- All visuals were created in **Python (Matplotlib & Seaborn)** using cleaned LAPD crime data.
- This notebook (`2.Severity_&_Victim_Analysis.ipynb`) builds on the cleaned dataset prepared earlier.
- The focus here is on **who** is affected and **how severe** the incidents are — forming the base for any further risk or vulnerability analysis.

---

## AUTHOR
**Utkarsh Naik**  
