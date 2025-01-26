# SQL - Data Analysis - Healthcare Dataset 
![SQL](https://img.shields.io/badge/Language-%20SQL-yellow/Workbench)
![SQL](https://img.shields.io/badge/Workbench-%20MySQL-green)

This dataset is taken from Kaggle (https://www.kaggle.com/datasets/prasad22/healthcare-dataset).

The SQL queries conducted on the Healthcare database provided comprehensive insights into various facets of patient demographics, medical conditions, treatments, financial aspects, and hospital performances. These findings facilitate informed decision-making processes and offer valuable insights for healthcare management and analysis. 

## Analysis Overview

### 1. Data Overview & Basic Statistics
- The dataset was explored to gather a comprehensive view of patient information and healthcare records
- Queries included counting total records, finding the maximum and average ages of hospitalized patients
- Analysis of patient demographics based on age

### 2. Medical Conditions & Medications
- Detailed insights were derived regarding prevalent medical conditions
- Analysis of medications prescribed for specific conditions
- Study of frequency of condition occurrence
- This information assists in understanding the distribution and treatment of various health issues within the dataset

### 3. Insurance Providers & Hospitals
- The project delved into patient preferences for insurance providers and hospitals based on frequency
- This data aids in:
  - Resource allocation
  - Understanding coverage preferences
  - Evaluating the prominence of healthcare services across different facilities

### 4. Financial Analysis & Duration of Hospitalization
- Financial aspects were scrutinized by examining:
  - Average billing amounts associated with different medical conditions
  - Total billing amount across various hospitals
  - Duration of hospital stays for patients
- This helps in understanding costs, hospital efficiency, and patient care duration

### 5. Blood Type Analysis & Donation Matching
- Analysis of distribution of blood types among patients
- Highlighting potential correlations between age groups and blood type occurrences
- Creation of 'Blood_Matcher' stored procedure to:
  - Identify potential donors and recipients
  - Match based on blood types, age, and hospital affiliation

### 6. Yearly Admissions & Insurance Analysis
- Identification of hospitals with patient admissions in 2024 and 2025
- Understanding billing patterns across different insurance providers
- Analysis aids in:
  - Understanding patient inflow trends
  - Identifying disparities in billing practices among insurance companies

### 7. Patient Risk Categorization
- Creation of risk categories (high, medium, low) based on:
  - Medical conditions
  - Test results
- Enables quick assessment of patient status
- Facilitates required follow-up actions

## Dataset Column Description

The dataset contains the following columns with their descriptions:

### 1. Name
- Patient name associated with the healthcare record

### 2. Age
- Patient age at time of admission (in years)

### 3. Gender
- Patient gender ("Male" or "Female")

### 4. Blood Type
- Patient blood type (e.g., "A+", "O-", etc.)

### 5. Medical Condition
- Primary medical condition or diagnosis
- Examples: Diabetes, Hypertension, Asthma

### 6. Date of Admission
- Date of patient admission to healthcare facility

### 7. Doctor
- Name of doctor responsible for patient care

### 8. Hospital
- Healthcare facility name where patient was admitted

### 9. Insurance Provider
- Patient's insurance provider
- Options include: Aetna, Blue Cross, Cigna, UnitedHealthcare, Medicare

### 10. Billing Amount
- Amount billed for healthcare services
- Expressed as floating-point number

### 11. Room Number
- Patient's accommodation room number

### 12. Admission Type
- Type of admission:
  - Emergency
  - Elective
  - Urgent

### 13. Discharge Date
- Date of patient discharge
- Based on admission date plus random days within realistic range

### 14. Medication
- Prescribed/administered medication
- Examples: Aspirin, Ibuprofen, Penicillin, Paracetamol, Lipitor

### 15. Test Results
- Medical test outcomes:
  - Normal
  - Abnormal
  - Inconclusive
