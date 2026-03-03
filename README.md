# 📊 Data-Driven Comparative Analysis of Global Defense Systems

## 📌 About The Project

This project presents a structured analytical study of global weapon systems including:

* Artillery
* Heavy Weapons
* Small Arms

The goal is to build a centralized data-driven dashboard that compares global defense capabilities based on:

* Operational Range
* Caliber
* Rate of Fire
* Cost
* Effectiveness Score
* Mobility
* Indigenous Production Capability

The project converts raw structured data into interactive intelligence using Power BI and DAX.

---

## 🎯 Problem Statement

Defense datasets contain multiple parameters across countries and weapon categories. However:

* There is no unified analytical system to compare global weapon systems.
* Cost vs effectiveness relationships are unclear.
* Decision-makers lack insight into modernization and upgrade priorities.
* Large datasets make manual comparison inefficient.

This project solves the problem by building:

* A cleaned and structured dataset
* Analytical measures using DAX
* An interactive dashboard for strategic comparison

---

## 🛠 Technologies Used

* **Power BI** – Data visualization & dashboard development
* **DAX (Data Analysis Expressions)** – Measures and calculated columns
* **Python (Pandas, NumPy)** – Dataset creation & cleaning
* **CSV / Excel** – Data storage

---

## 📂 Dataset Overview

The dataset includes 500+ structured records with the following fields:

| Column               | Description                           |
| -------------------- | ------------------------------------- |
| Weapon_Name          | Unique weapon identifier              |
| Country              | Manufacturing country                 |
| Category             | Small Arms / Artillery / Heavy Weapon |
| Type                 | Weapon classification                 |
| Range_km             | Operational range                     |
| Caliber_mm           | Caliber size                          |
| Rate_of_Fire         | Rounds per minute                     |
| Mobility_Score       | Mobility index                        |
| Accuracy_Score       | Accuracy rating                       |
| Cost_Million_USD     | Unit cost                             |
| Indigenous           | Yes / No                              |
| Terrain_Adaptability | Environmental adaptability score      |

### 🔹 Data Cleaning Steps

* Removed null and invalid values
* Standardized country names
* Verified numeric ranges
* Ensured consistency across categories

---

## 📊 Dashboard Structure

### 🟦 Page 1 – Strategic Overview

* KPI Cards (Total Weapons, Avg Range, Avg Effectiveness)
* Cost Distribution by Category
* Country Performance Comparison
* Global Map View

### 🟦 Page 2 – Technical Performance Analysis

* Cost vs Range Scatter Plot
* Category Effectiveness Comparison
* Country-wise Cost Analysis

### 🟦 Page 3 – Intelligence & Recommendations

* Cost-Effectiveness Evaluation
* Upgrade Needed Classification
* Procurement Recommendation Logic
* Detailed Weapon Comparison Table

---

## 📈 Key Insights

* Heavy weapons contribute the largest share of overall defense cost.
* High cost does not always guarantee high effectiveness.
* Certain mid-cost systems provide better performance-to-cost ratios.
* Indigenous capability significantly impacts strategic strength.

---

## 🧮 DAX Implementation

### Example Measures

```DAX
Total Weapons = COUNT(global_weapon_analysis[Weapon_Name])
```

```DAX
Avg Effectiveness = AVERAGE(global_weapon_analysis[Effectiveness])
```

```DAX
Total Cost = SUM(global_weapon_analysis[Cost_Million_USD])
```

### Example Calculated Column

```DAX
Cost_Efficiency = 
global_weapon_analysis[Effectiveness] 
/ global_weapon_analysis[Cost_Million_USD]
```

---

## 🧠 What This Project Demonstrates

* Data modeling skills
* DAX calculations (Row Context vs Filter Context)
* Dashboard storytelling
* Analytical thinking
* Strategic interpretation of structured data

---

## 🚀 Future Improvements

* Integration of Machine Learning for predictive analysis
* Real-world defense procurement dataset integration
* Advanced DAX optimization
* Automated PDF report generation

---

## 👩‍💻 Author

Shreya Ghoderao
Data Analytics & Business Intelligence Enthusiast

---

