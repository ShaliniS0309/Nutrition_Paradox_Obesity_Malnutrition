# 🥗 Nutrition Paradox: A Global View on Obesity and Malnutrition

## 📌 Project Overview
The **Nutrition Paradox** refers to the coexistence of **over-nutrition (obesity)** and **under-nutrition (malnutrition)** within the same population, country, or region.  
This project analyzes global obesity and malnutrition trends using **World Health Organization (WHO)** data through **data cleaning, analysis, and interactive visualization**.

---

## 🎯 Objectives
- Analyze global trends in **obesity and malnutrition**
- Compare patterns across **countries, regions, gender, and age groups**
- Identify regions facing **dual nutritional challenges**
- Build an **interactive Power BI dashboard** for data-driven insights

---

## 🗂️ Dataset
**Source:** World Health Organization (WHO)

### Processed Datasets:
- `df_obesity_final.csv`
- `df_malnutrition_final.csv`

These datasets include indicators such as:
- Mean estimate
- Confidence intervals
- Gender
- Age group
- Region
- Year

---

## 🛠️ Tools & Technologies
- **Python** (Pandas, NumPy, Matplotlib, Seaborn)
- **SQL / SQLite**
- **Power BI Desktop**
- **Jupyter Notebook**
- **GitHub**

---

## 🔄 Project Workflow

### 1️⃣ Data Cleaning & Preparation
- Removed missing and inconsistent values
- Standardized country names using country codes
- Converted data types
- Handled confidence intervals

### 2️⃣ Feature Engineering
- Created `Age_Group`
- Calculated `CI_Width`
- Categorized:
  - `Obesity_Level`
  - `Malnutrition_Level`

### 3️⃣ Exploratory Data Analysis (EDA)
- Trend analysis across years
- Gender-wise and age-group-wise comparison
- Region-wise aggregation

### 4️⃣ SQL Analysis
- Used SQL queries to aggregate and analyze obesity and malnutrition data
- Performed country-level and regional comparisons

### 5️⃣ Power BI Dashboard
Developed a **3-page interactive dashboard**:

#### 📄 Page 1: Obesity Analysis
- Global obesity trend over time
- Obesity distribution by gender and age group
- Top 10 countries by obesity rate
- Regional obesity comparison

#### 📄 Page 2: Malnutrition Analysis
- Global malnutrition trend over time
- Malnutrition distribution by gender and age group
- Top 10 countries by malnutrition rate
- Regional malnutrition comparison

#### 📄 Page 3: Obesity vs Malnutrition (Combined Analysis)
- Country-wise obesity vs malnutrition scatter plot
- Country trend comparison (dual-line chart)
- Region-wise obesity vs malnutrition comparison
- Heatmap-style matrix using conditional formatting

✔ Interactive slicers included:
- Year
- Country
- Gender
- Age Group

---

## 📊 Key Insights
- Obesity rates are **increasing globally**, particularly among adults
- Malnutrition shows a **gradual decline**, but remains high in specific regions
- Some countries face **both high obesity and high malnutrition**
- Regional disparities highlight the need for **targeted public health policies**

---

## 📁 Repository Structure
