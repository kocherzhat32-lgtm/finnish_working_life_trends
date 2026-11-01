# Finnish Working Life: Myth Busting & Longitudinal Trends (2014–2024)

[![Python](https://img.shields.io/badge/Python-3.8%2B-blue.svg)](https://www.python.org/)
[![Pandas](https://img.shields.io/badge/Pandas-Data%20Cleaning-%23150458.svg)](https://pandas.pydata.org/)
[![Seaborn](https://img.shields.io/badge/Seaborn-Visualization-%233776AB.svg)](https://seaborn.pydata.org/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

An end-to-end data analytics project investigating structural shifts and trends in Finnish working life over a decade (2014–2024) using historical survey microdata.

---

## 📌 Project Overview
This portfolio project processes and harmonizes multi-year survey datasets from the **Finnish Social Science Data Archive (FSD)** (Työolobarometri series). The analysis tracks how workplace dynamics, job security, physical and mental strain, workplace safety, and compensation practices evolved across Finnish enterprises over ten years.

- **Data Source:** Official annual surveys from the **Finnish Social Science Data Archive (FSD)** (*Työolobarometri* 2014–2024). *(Note: Raw microdata files are excluded from this repository in compliance with FSD data distribution terms).*
- **Timeframe:** 2014–2024.

---

## 🛠️ Tech Stack & Methodology
- **Data Processing & Cleaning:** Python (`Pandas`, `NumPy`), automated cross-year column mapping and binary recoding.
- **Data Visualization:** `Matplotlib`, `Seaborn` with custom percentage formatting and longitudinal styling.
- **Methodological Rigor:** Standardized variable harmonization across changing questionnaire structures, managing missing values (`NaN`), and converting ordinal scales into percentage shares and mean scores.

---

## 📊 Key Findings & Visualizations

### 1. Workplace Safety and Discrimination Trends
Tracks multi-year exposure to psychological harassment (bullying), observed discrimination, and physical violence incidents.
![Workplace Safety and Discrimination Trends](workplace_safety_and_discrimination_trends.png)

### 2. Core Work-Life Metrics
Analyzes multi-year dynamics of autonomy, work pace, and mental strain in Finnish workplaces.
![Core Work-Life Metrics](simple_indices_trend_2014_2024.png)

### 3. Job Security & Employment Stability
Tracks perceived risks of dismissals, furlough threats, and overall job security.
![Job Security Dynamics](job_security_trend_2014_2024.png)

### 4. Physical and Mental Work Load
Compares structural demands on physical exertion versus mental strain across industries.
![Physical and Mental Work Load](physical_mental_load_trend_2014_2024.png)

### 5. Unpaid Overtime Dynamics
Highlights the percentage of employees performing unpaid overtime, showcasing a notable peak in 2021.
![Unpaid Overtime Dynamics](unpaid_overtime_trend_2014_2024.png)

---

## 📂 Repository Structure
```text
finnish_working_life_trends/
│
├── 01_core_work_life_indices.ipynb            # Core indices and general workplace metrics
├── 02_unpaid_overtime.ipynb                    # Analysis of unpaid overtime and working hours
├── 03_job_security.ipynb                       # Employment stability and perceived job security trends
├── 04_physical_mental_load.ipynb               # Physical and mental strain indicators
├── 05_data_harmonization.ipynb                 # Master harmonization script for raw survey years
├── 06_visualization_and_analysis.ipynb         # Final trend aggregation and visualization generation
│
├── harmonized_physical_mental_load_2014_2024.csv # Exported aggregated trends: Work Load
├── harmonized_safety_indicators.csv            # Exported aggregated trends: Safety & Discrimination
├── job_security_2014_2024.csv                  # Exported aggregated trends: Job Security
├── unpaid_overtime_2014_2024.csv               # Exported aggregated trends: Unpaid Overtime
├── work_life_2014_2024.csv                     # General harmonized workplace metrics
│
├── job_security_trend_2014_2024.png            # Visualization output: Job Security
├── physical_mental_load_trend_2014_2024.png    # Visualization output: Physical & Mental Load
├── simple_indices_trend_2014_2024.png          # Visualization output: Core Indices
├── unpaid_overtime_trend_2014_2024.png         # Visualization output: Unpaid Overtime
└── workplace_safety_and_discrimination_trends.png # Visualization output: Safety & Discrimination
```

---

## 👩‍💻 Author

**Oksana Kocherzhat**  
Data Analyst (OAMK)  
📍 Finland  
🔗 LinkedIn: https://www.linkedin.com/in/oksana-kocherzhat-834518231
