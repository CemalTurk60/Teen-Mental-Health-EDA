# Teen Mental Health: Exploratory Data Analysis & Preprocessing

This repository contains the first part of a comprehensive data science project focused on analyzing and preparing a dataset related to teenage mental health, social media usage, and lifestyle habits. 

## 📌 Project Overview
The goal of this phase is to perform rigorous Exploratory Data Analysis (EDA) and prepare a 100% clean numerical matrix for future Machine Learning pipelines.

### Key Milestones Achieved:
* **Exploratory Data Analysis (EDA):** Visualized correlations between screen time, sleep hours, and depression/anxiety levels using Seaborn and Matplotlib.
* **Feature Engineering & Data Leakage Prevention:** Successfully identified and dropped highly correlated proxy variables (`mental_health_risk_score`) to prevent future model leakage.
* **Categorical Encoding:** Converted ordinal text variables (`sleep_quality`, `social_interaction_level`) into distinct mathematical hierarchies.
* **Data Cleanliness:** Handled missing values to achieve a 100% complete, non-null processed dataset (`cleaned_mental_health_data.csv`).

## 🛠️ Tech Stack & Libraries
* **Python 3**
* **Pandas** & **NumPy** (Data manipulation)
* **Matplotlib** & **Seaborn** (Data visualization)

## 📁 Repository Structure
* `*.ipynb`: The complete interactive Jupyter Notebook containing all analysis and visualizations.
* `cleaned_mental_health_data.csv`: Preprocessed, scaled, and encoded dataset ready for ML modeling.

---
*Note: This project is part of an ongoing advanced data science and machine learning journey.* 🚀
