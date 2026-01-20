# sleep_data_cdc
# Sleep, Stress, and School Engagement  
## What a National Student Survey Reveals

## Overview
This project explores the relationship between sleep, stress, and school engagement using data from the **2023 CDC Youth Risk Behavior Survey (YRBS)**.

The analysis focuses on how sleep duration is associated with student wellbeing and school engagement indicators such as attendance disruption and grade-level progression. While the national dataset does not include GPA or letter grades, it captures several variables that are closely linked to academic functioning.

The goal of this project is to practice **data analysis and data science** using real-world public data, while carefully acknowledging limitations such as missing data and the difference between correlation and causation.

---

## Dataset Description
This study uses the following dataset: https://www.cdc.gov/yrbs/data/index.html 

- **2023 CDC Youth Risk Behavior Survey (YRBS)**
- **Special Adolescent Data Collection (SADC)**
- **National Combined Dataset**

The YRBS surveys hundreds of thousands of U.S. high school students (grades 9–12) about health behaviors, mental well-being, safety, and school-related experiences.

Although the dataset contains many variables, this analysis uses a **carefully selected subset** that:
- Is directly relevant to the research questions
- Has sufficient response coverage for meaningful analysis

---

## Data Source
Official CDC YRBS data and documentation are available here:  
https://www.cdc.gov/yrbs/data/index.html

---

## Files in This Repository

### Data Files
- **`yrbs_2023_sadc_vars.csv`**  
  Cleaned CSV file used for analysis, extracted from the original CDC files.

### CDC Source Files
- **`2023-SADC-SPSS-Input-Program.sps`**  
- **`sadc_2023_national.dat`**  

These files are provided by the CDC and define the structure of the raw YRBS data.

---

## Code Files

### Data Extraction
- **`sps_to_csv.py`**  
  Python script used to extract and convert the raw CDC `.dat` file into a usable CSV format using the SPSS input program.

### Basic Analysis
- **`basic.ipynb`**  
  Exploratory data analysis and visualizations using **pandas**, **NumPy**, and **matplotlib**.

### Enhanced Visualizations
- **`pyecharts.ipynb`**  
  Analysis and visualizations created using **PyEcharts** for more engaging and interactive charts.

---

## Tools & Libraries Used
- Python  
- pandas  
- NumPy  
- matplotlib  
- PyEcharts  

---



