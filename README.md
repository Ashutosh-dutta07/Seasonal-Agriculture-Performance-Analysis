# 🌾 Seasonal Agriculture Performance Analysis

> **Data Analytics Major Project | VOIS AICTE Batch 1 | 2026–2027**

An end-to-end **Data Analytics project** focused on understanding how agricultural performance varies across different seasons, crops, regions, environmental conditions, resource usage, and economic factors.

The project transforms raw agricultural data into meaningful insights using **Python, Pandas, NumPy, Matplotlib, Seaborn, and SciPy**. The analysis covers seasonal yield, production, revenue, cost, profit, environmental conditions, irrigation, water efficiency, crop performance, disease/pest risk, and statistical relationships.

---

## 📌 Project Overview

Agricultural performance is influenced by seasonal variations in environmental conditions, farming practices, resource availability, and market conditions.

This project analyzes these variations to identify:

* Seasonal agricultural performance patterns
* Differences in crop productivity
* Environmental and resource-related patterns
* Irrigation and water-efficiency relationships
* Economic performance across seasons
* Regional variations in yield
* Statistical relationships between important variables
* Areas that can support better seasonal agricultural planning

The project follows a **descriptive and statistical analytics approach** to understand the available agricultural data.

---

## 🎯 Objectives

The major objectives of this project are to:

* Explore and understand agricultural data
* Clean and prepare the dataset
* Analyze agricultural performance across seasons
* Identify important seasonal patterns and trends
* Compare crop and regional performance
* Study relationships between environmental conditions and yield
* Analyze irrigation and resource usage
* Examine revenue, cost, profit, and profitability patterns
* Identify significant observations and unusual patterns
* Apply statistical and visualization techniques
* Generate evidence-based insights and recommendations

---

## 📊 Dataset Overview

The dataset contains information about agricultural activities across different seasons, geographical areas, farming practices, environmental conditions, resource usage, and economic outcomes.

| Parameter       | Value |
| --------------- | ----: |
| Total Records   | 4,000 |
| Total Variables |    28 |
| Seasons         |     3 |
| Crops           |     8 |
| States          |     8 |
| Missing Values  |   120 |
| Duplicate Rows  |     0 |

### 🌱 Seasons

* Kharif
* Rabi
* Zaid

### 🌾 Crops

* Rice
* Wheat
* Maize
* Cotton
* Pulses
* Groundnut
* Chilli
* Sugarcane

### 📍 States

The dataset covers agricultural records from 8 states, including Punjab, Karnataka, Gujarat, Telangana, Maharashtra, Madhya Pradesh, Tamil Nadu, and Andhra Pradesh.

---

## 🔍 Key Features Analyzed

The analysis covers the following major categories:

### 🌦️ Environmental Factors

* Rainfall
* Average Temperature
* Humidity
* Sunlight Hours
* Soil pH
* Soil Moisture

### 🌱 Agricultural Inputs

* Nitrogen
* Phosphorus
* Potassium
* Fertilizer Usage
* Pesticide Usage
* Seed Quality

### 💧 Resource Management

* Irrigation Method
* Water Used
* Water Efficiency

### 🌾 Agricultural Outcomes

* Yield
* Production

### 💰 Economic Performance

* Market Price
* Total Cost
* Revenue
* Profit
* Profit Margin

### ⚠️ Risk Factors

* Disease/Pest Risk

---

## 🧹 Data Cleaning & Preparation

Before performing analysis, the dataset was checked for quality issues.

### Data Quality Findings

* **4,000 records** were analyzed.
* **120 missing values** were identified.
* Missing values were present in important variables such as:

  * Rainfall
  * Soil Moisture
  * Yield
* **No duplicate rows** were found.
* Data was cleaned and prepared before performing further analysis.

The cleaned dataset was then used for statistical analysis and visualization.

---

## 📈 Exploratory Data Analysis

The project uses multiple visualizations to investigate agricultural patterns.

### Seasonal Performance

* Average Yield by Season
* Average Production by Season
* Revenue vs Cost by Season
* Profit by Season

### Environmental Analysis

* Rainfall by Season
* Temperature by Season
* Soil Moisture by Season
* Environmental Conditions vs Yield

### Crop Analysis

* Average Yield by Crop
* Crop Yield Across Seasons

### Resource & Irrigation Analysis

* Yield by Irrigation Method
* Water Efficiency by Season
* Water Usage vs Yield

### Economic Analysis

* Revenue by Season
* Cost by Season
* Profit by Season
* Profit Margin by Season
* Profit and Loss Farm Analysis

### Regional Analysis

* State-wise Average Yield

### Risk Analysis

* Disease and Pest Risk by Season

---

## 📊 Statistical Analysis

Statistical techniques were applied to determine whether observed seasonal differences were statistically meaningful.

### One-Way ANOVA

ANOVA was performed on seasonal yield to test whether the mean yield differs significantly across Kharif, Rabi, and Zaid seasons.

**Result:**

* F-statistic: **1.458**
* p-value: **0.233**
* Significance level: **0.05**

Since **p > 0.05**, the analysis does not provide sufficient statistical evidence to conclude that mean yield differs significantly across seasons at the 5% significance level.

> The observed difference in average seasonal yield should therefore be interpreted as a pattern in this dataset rather than as a statistically significant seasonal effect.

---

## 🔗 Correlation Analysis

A correlation matrix was used to understand relationships between agricultural variables.

### Important Observations

| Variable         | Correlation with Yield |
| ---------------- | ---------------------: |
| Water Efficiency |              **0.915** |
| Production       |              **0.885** |
| Profit           |              **0.490** |
| Revenue          |              **0.434** |
| Water Used       |              **0.389** |
| Nitrogen         |                  0.054 |
| Phosphorus       |                  0.048 |
| Rainfall         |                  0.031 |

The analysis indicates a strong positive association between **water efficiency and yield**.

> **Note:** Correlation indicates association, not causation.

---

# 🌾 Key Findings

## 1. Seasonal Agricultural Performance

* **Kharif** recorded the highest average yield of **5.64 tonnes/ha**.
* **Rabi** recorded an average yield of **5.08 tonnes/ha**.
* **Zaid** recorded the lowest average yield of **4.67 tonnes/ha**.
* Kharif also recorded the highest average production of **46.31 tonnes**.

## 2. Crop Performance

* **Sugarcane** recorded the highest average yield at **46.94 tonnes/ha** among the analyzed crops.
* Other crops showed considerable differences in average productivity.

## 3. Economic Performance

* Kharif showed the strongest economic performance.
* Average Kharif revenue was approximately **₹7.11 lakh**.
* Average Kharif profit was approximately **₹1.79 lakh**.
* Zaid showed the weakest economic performance, with an average loss of approximately **₹24,805**.

## 4. Environmental Conditions

* Kharif recorded the highest average rainfall of approximately **852.08 mm**.
* Kharif also had the highest average soil moisture at **31.20%**.
* Zaid recorded the highest average temperature at approximately **31.04°C**.
* Zaid had the lowest average soil moisture at **19.17%**.

## 5. Irrigation & Water Efficiency

* **Drip irrigation** recorded the highest average yield at **6.62 tonnes/ha**.
* Water efficiency showed a strong positive association with yield (**r = 0.915**).
* This highlights the importance of efficient water management in agricultural analysis.

## 6. Statistical Findings

* ANOVA produced a **p-value of 0.233**, which is greater than 0.05.
* Therefore, seasonal differences in mean yield were **not statistically significant at the 5% level**.
* Water efficiency and production showed the strongest associations with yield among the analyzed variables.

---

# 💡 Data-Driven Recommendations

Based on the analysis, the following recommendations can be considered:

### 💧 Improve Water Management

Promote efficient irrigation practices and monitor water usage to improve agricultural productivity.

### 🌱 Focus on Crop Suitability

Crop selection can consider seasonal conditions, regional characteristics, soil conditions, and historical crop performance.

### 📊 Monitor Seasonal Performance

Agricultural stakeholders can continuously monitor yield, production, revenue, cost, and environmental conditions across seasons.

### 💰 Improve Profitability

Production alone should not be treated as the only performance indicator. Revenue, cost, and profit should also be evaluated while planning agricultural activities.

### 🌦️ Consider Multiple Factors

Agricultural yield should be analyzed using multiple environmental, resource, agricultural, and economic variables rather than relying on a single factor.

---

# 🛠️ Technologies & Tools

| Technology           | Purpose                                |
| -------------------- | -------------------------------------- |
| **Python**           | Data analysis and processing           |
| **Pandas**           | Data cleaning and manipulation         |
| **NumPy**            | Numerical computations                 |
| **Matplotlib**       | Data visualization                     |
| **Seaborn**          | Statistical and advanced visualization |
| **SciPy**            | Statistical analysis and ANOVA         |
| **Jupyter Notebook** | Development and analysis environment   |

These tools were used throughout the project for data preparation, exploratory analysis, visualization, and statistical testing.

---

# 📂 Project Structure

```text
Seasonal-Agriculture-Performance-Analysis/
│
├── 📓 Seasonal_Agriculture_Performance_analysis.ipynb
├── 📊 seasonal_agriculture_performance_dataset.csv
├── 📑 Major Project_Seasonal Agriculture Performance Analysis.pdf
├── 📽️ major project VOIS.pptx
└── 📄 README.md
```

---

# 🚀 Future Scope

The project can be extended from descriptive analytics to **predictive and prescriptive analytics**.

Possible future improvements include:

* **Real-Time Data Integration**
  Integrate live weather, rainfall, soil, and market-price data.

* **Crop Yield Prediction**
  Build Machine Learning models to predict crop yield before harvesting.

* **Crop Recommendation System**
  Recommend suitable crops based on season, soil, and environmental conditions.

* **Weather-Based Farming Insights**
  Combine weather forecasts with historical agricultural data.

* **Advanced Regional Analysis**
  Include more states, districts, and farms for region-specific analysis.

* **Smart Irrigation Optimization**
  Develop models to recommend efficient irrigation methods and water requirements.

* **Disease/Pest Prediction**
  Extend the analysis towards early disease and pest detection.

* **Interactive Dashboard**
  Develop a Power BI dashboard for interactive agricultural monitoring and decision support.

The long-term goal is to move towards a data-driven agricultural decision-support system.

---

# 👥 Potential End Users

The insights generated from this project can be useful for:

* 👨‍🌾 **Farmers** – Crop selection and seasonal planning
* 🏛️ **Agricultural Departments** – Monitoring agricultural performance
* 🏢 **Agribusinesses & Cooperatives** – Production and profitability analysis
* 💧 **Irrigation & Resource Managers** – Water management
* 🔬 **Researchers & Analysts** – Agricultural pattern analysis
* 📋 **Policy Makers** – Evidence-based agricultural planning

---

# 📓 Notebook

The complete analysis, including data cleaning, exploratory data analysis, visualizations, and statistical analysis, is documented in the Jupyter Notebook included in this repository.

**Main file:**

`Seasonal_Agriculture_Performance_analysis.ipynb`

---

# 📊 Project Presentation

The project presentation contains:

* Problem Statement
* Project Objectives
* Dataset Overview
* Data Quality Analysis
* Exploratory Data Analysis
* Seasonal Performance Analysis
* Crop & Irrigation Analysis
* Environmental Analysis
* Economic Analysis
* Statistical Analysis
* Correlation Analysis
* Overall Insights
* Recommendations
* Future Scope
* Conclusion

---

# 📌 Conclusion

The **Seasonal Agriculture Performance Analysis** project demonstrates how data analytics can be used to understand agricultural performance across seasons, crops, regions, environmental conditions, resource usage, and economic outcomes.

The analysis shows that **Kharif performed strongest overall**, while **Zaid showed comparatively lower productivity and profitability**. Drip irrigation and water efficiency were strongly associated with higher yield, while rainfall and selected nutrient variables showed relatively weak direct correlations with yield.

The project provides a foundation for extending agricultural analytics towards **Machine Learning-based prediction, smart irrigation, crop recommendation, real-time monitoring, and interactive decision-support systems**.

---

## 👨‍💻 Author

### **Ashutosh Kumar**

**Aspiring Data Analyst | Data Science & Machine Learning Enthusiast**

🎓 Shivalik College of Engineering
📚 VOIS AICTE Batch 1 — 2026–2027

---

## ⭐ If You Find This Project Useful

If you find this project interesting or useful, consider giving the repository a **⭐ Star** and exploring the complete notebook and analysis.

---

### 📜 Project Context

This project was developed as part of the **VOIS AICTE Batch 1 Major Project (2026–2027)** on *Seasonal Agriculture Performance Analysis*. The project brief focuses on identifying seasonal patterns, relationships, variations, and evidence-based agricultural insights.
