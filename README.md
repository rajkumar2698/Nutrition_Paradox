#  🌍 Nutrition Paradox: A Global View on Obesity and Malnutrition

##  📌 Project Overview
The **Nutrition Paradox** refers to the simultaneous presence of **obesity and malnutrition across different regions and populations worldwide.**

This project analyzes global nutrition patterns to understand how these two contrasting health issues coexist.

Using data from the World **Health Organization (WHO) – Global Health Observatory (GHO)**, the analysis 
Explores:
   - Long-term trends in obesity and malnutrition
   - Regional and demographic differences
   - Data uncertainty using confidence intervals
   
   > The entire analysis is implemented in a single Jupyter Notebook using Python, with optional SQL and Power BI integration for advanced analysis and visualization.
  
---
## 🛠️ Tools & Technologies
- **Python**
- **Jupyter Notebook**
- **WHO GHO API**
- **Pandas** - data manipulation and analysis
- **Matplotlib** - data visualization
- **SQLite3**  - database integration and SQL analysis
 - **PowerBi** - interactive dashboards and reporting
---

## 📊 Dataset Information
- Source: **World Health Organization (WHO) – Global Health Observatory**
- **Indicators Analyzed:**
  - **Adult obesity**
  - Child & adolescent obesity
  - **Adult malnutrition**
  - Child & adolescent malnutrition
- Time period analyzed: **2012 – 2022**

---

## 🔄 Project Workflow
**Data Collection**
 - Retrieved global nutrition indicators using the WHO GHO API

**Data Cleaning & Preprocessing**
 - Handled missing values and inconsistencies
 - Standardized region and demographic labels

**Feature Engineering**
 - Age group categorization
 - Confidence Interval Width (CI_Width)
 - Risk-level classification

**Exploratory Data Analysis (EDA)**
 - Trend analysis
 - Regional and demographic comparisons

**SQL Integration**
 - Loaded cleaned data into SQLite
 - Executed analytical SQL queries

**Comparative Analysis**

 - Obesity vs. malnutrition patterns
 - Regional contrasts highlighting the nutrition paradox
---

## 📈 Key Visualizations
**The notebook contains 25+ visualizations, including:**

- Distribution of obesity levels worldwide
- Global obesity trends over time
- Obesity trends in India (2012–2022)
- Regional comparison of malnutrition prevalence
- Gender-based nutrition analysis
- Age-group-wise obesity and malnutrition patterns
- Africa-focused regional trends
- Confidence interval and data reliability analysis
- Countries with increasing malnutrition over time

---

## 📂 Repository Structure
```
Nutrition_Paradox-Project
├─ Nutrition_Paradox.ipynb
└─ README.md
```
---

## ▶️ How to Run the Project
1. Clone or download the repository  
2. Open `Nutrition_Paradox.ipynb` in **Jupyter Notebook / Jupyter Lab**  
3. Run all cells sequentially from top to bottom
4. (Optional) Configure **SQL Lite3** if database connectivity is required  

---

## 🎯 Key Insights
- Global obesity rates are **steadily increasing**, particularly in higher-income and urbanized regions
- Malnutrition remains **highly prevalent in Africa and South-East Asia**
- Clear regional contrasts strongly demonstrate the **global nutrition paradox**
- Nutrition outcomes vary significantly by **gender and age group**
- Confidence interval analysis highlights regions where **data reliability needs improvement** 

---
🧠 Conclusion

This project demonstrates how **data-driven analysis using Python, SQL, and visualization tools** can support public health decision-making.
The insights can help policymakers and health organizations:

 - Identify high-risk regions
 - Allocate resources more effectively
 - Design targeted nutrition and intervention programs

---
## 👤 Author
**_Rajkumar S_** 

---
