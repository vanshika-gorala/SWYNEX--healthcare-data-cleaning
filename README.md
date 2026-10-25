# SWYNEX Project (Healthcare Dataset)

## Task 1: Data Cleaning and Preparation

### Task Overview
The objective of this task was to clean and prepare the healthcare dataset for further analysis using Excel Power Query.

### Dataset Source
[Healthcare Dataset by Prasad Patil – Kaggle](https://www.kaggle.com/datasets/prasad22/healthcare-dataset)

### Data Cleaning Steps
1. Imported the raw dataset into Power Query Editor.
2. Checked Column Quality to identify errors and empty values.
3. Removed duplicate records by selecting all columns.
4. Checked category consistency in Gender, Blood Group, Medical Condition, Admission Type, and Test Results.
5. Created a temporary column to validate admission and discharge dates, then removed it after checking the results.
6. Sorted Age and Room Number columns to check for negative and unusual values.
7. Verified the data types of all columns.
8. Used Close & Load to load the cleaned data back into Excel.

### Outcome
Prepared the healthcare dataset for the next task: Exploratory Data Analysis (EDA).


# Task 2: Exploratory Data Analysis (EDA) 

## Task Overview
As part of my Task 2, I performed Exploratory Data Analysis (EDA) on a healthcare dataset to understand patient demographics, medical conditions, admission patterns, and billing information.

The objective of this task was to explore the dataset, identify patterns, summarize important findings, and derive meaningful insights using Python.

## 🛠️ Tools & Technologies
- **Python** – Data analysis
- **Pandas** – Data manipulation and analysis
- **Matplotlib** – Data visualization
- **Seaborn** – Statistical data visualization
- **Google Colab** – Python coding environment

## 📂 Dataset Overview
The dataset contains healthcare-related information, including:
- Patient demographics (Age, Gender, Blood Group)
- Medical conditions
- Admission types and admission dates
- Billing amounts
- Insurance providers

## 🔍 EDA Process

### 1. Data Understanding
- Examined dataset dimensions, column names, and data types.
- Checked for missing values and reviewed the overall structure of the dataset.
- Used summary statistics to understand numerical and categorical variables.

### 2. Patient Analysis
- Analyzed the age distribution of patients.
- Examined gender distribution.
- Explored patient counts across different medical conditions.

### 3. Medical Analysis
- Calculated median billing amounts for medical conditions.
- Compared average patient ages across medical conditions.
- Identified the medical condition with the highest mean billing amount.

### 4. Admission Analysis
- Analyzed the distribution of Elective, Urgent, and Emergency admissions.
- Compared average billing amounts across admission types.
- Examined age information for emergency admission records.

### 5. Billing Analysis
- Compared maximum billing amounts across insurance providers.
- Identified the lowest billing amount among insurance providers.
- Counted records with billing amounts greater than the overall mean billing amount.

### 6. Data Visualization
Created visualizations to understand patterns and compare categories:
- Age Distribution – Histogram
- Gender Distribution – Bar Chart
- Medical Condition Distribution – Bar Chart
- Average Billing by Medical Condition – Bar Chart
- Admission Type Distribution – Bar Chart
- Average Billing by Insurance Provider – Bar Chart

## 📊 Key Insights

### Patient Analysis
1. **Age Distribution:** Patients' ages range from 13 to 89 years, with an average age of 51 years.
2. **Gender Distribution:** The dataset contains 27,749 male patients and 27,741 female patients, indicating a nearly equal gender distribution.

### Medical Analysis
1. **Median Billing Amount:** Arthritis has a median billing amount of 25,628.30, while Obesity has a median billing amount of 26,200.51.
2. **Average Age:** The mean age of patients is approximately 51 years across all medical conditions.
3. **Highest Mean Billing Amount:** Obesity has the highest mean billing amount among all medical conditions.
4. **Medical Condition Distribution:** Arthritis has the highest patient count, with 9,207 patients, while Asthma has the lowest patient count, with 9,077 patients.

### Admission Analysis
1. **Admission Type Distribution:** Elective and Urgent admissions each account for approximately 33% of total admissions, while Emergency admissions account for approximately 32%.
2. **Average Billing by Admission Type:** Elective admissions have the highest average billing amount (25,663), followed by Urgent admissions (25,568) and Emergency admissions (25,551).
3. **Emergency Admission Records:** Emergency admissions include patients ranging in age from 13 to 89 years.

### Billing Analysis
1. **Highest Billing Amount:** Blue Cross has the highest maximum billing amount of 52,764.28, followed by UnitedHealthcare at 52,373.03.
2. **Lowest Billing Amount:** Medicare has the lowest maximum billing amount of 52,092.67, followed by Cigna at 52,170.04.

## Outcome
The EDA helped identify patient demographics, medical condition trends, admission patterns, and billing insights using Python, Pandas, and visualizations.

