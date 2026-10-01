# connectatel-customer-usage-analysis

**ConnectaTel Consumption Analysis**

This repository contains the statistical analysis and customer segmentation carried out for ConnectaTel, a telecommunications company operating in Mexico and Colombia.

The project integrates three data sources — customers, plans, and usage records — to analyse usage patterns, identify data quality issues and outliers, and segment customers according to their demographic characteristics and behaviour.

## 📂 Repository Contents
The analysis can be viewed directly on GitHub or run in Google Colab:

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1xlrJtkAbQb3p7mpNjS1Y81In7Hf49mKY#scrollTo=9b5d5eca)

`connectatel-customer-usage-analysis.ipynb` → Main notebook containing data cleaning, exploratory data analysis (EDA), distributions, visualisations, segmentation by usage groups, and strategic conclusions.

## 🧠 Analysis Objective
The objective of the analysis was to understand how customers use mobile services and identify patterns that may be relevant for segmentation and commercial strategy.

The following areas were analysed:
- Call and messaging usage patterns.
- Differences in usage by age and plan type.
- Outliers and data inconsistencies.
- Customer segments based on usage volume.
- Potential opportunities to improve the commercial offering.

## 🗂️ Data
The analysis integrates three datasets:

- `plans.csv`	(two plans: Basic and Premium) — Information about the plans, prices, and included benefits.
- `users_latam.csv`	(4,000 users) — Demographic and contractual information about customers.
- `usage.csv` (40,000 usage records) — Records of calls and messages made by users.

The datasets contain missing values, inconsistencies, and outliers that were addressed during the data cleaning process.

## 🔎  Analysis Process

* **Data Integration and Cleaning:** Consolidation and cleaning of databases to build a single dataset of 4,000 users suitable for statistical analysis.
* **Data Validation and Quality:** Application of data validation techniques, data type standardisation, duplicate record management, and treatment of missing or inconsistent values.
* **Statistical Profiling:** Creation of quantitative usage profiles (calls and messages) both at overall business level and broken down by demographic segments.
* **Anomaly Detection (Outliers):** Identification and analysis of atypical behaviour using statistical and visual methods.
* **Advanced Customer Segmentation:** Classification of the user base according to demographic criteria (age ranges) and behavioural patterns to define usage-volume groups (Low Usage, Medium Usage, and High Usage).
* **Visual Analysis and Business Insights:** Creation of histograms and charts to visualise the overlap between plans (Basic vs. Premium) and extract strategic recommendations aimed at optimising the commercial offering.

## 📊 Key Findings

- Identified 55 invalid age records (-999), representing approximately 1.38% of the customer dataset.
- Detected 40 registration records with dates outside the expected analysis period.
- Found additional missing values and data quality inconsistencies across the datasets.
- Customer segmentation identified a Low Usage group representing approximately 19.5% of the analysed customer base.
- Compared customer usage patterns across age groups and mobile plans.

## 💡 Business Insights
The analysis provides a basis for:
- Identifying customers with different usage patterns.
- Detecting segments that may benefit from targeted engagement or retention strategies.
- Evaluating whether existing plans align with actual customer usage.
- Supporting future commercial decisions based on customer behaviour.

## 🛠️ Tools
- Python
- Pandas
- Matplotlib
- Seaborn
- Jupyter Notebook
- Google Colab

## 📌 Demonstrated skills
- Data cleaning
- Data validation
- Exploratory Data Analysis (EDA)
- Statistical analysis
- Outlier detection
- Data segmentation
- Data visualization
- Business insights



