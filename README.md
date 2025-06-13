# Understanding Hospital Readmissions Due to Diabetes

## Project Overview

This project analyzes hospital readmissions due to diabetes in the U.S. between 1999 and 2008. Diabetes is a chronic condition marked by high blood sugar levels, and frequent readmissions may signal gaps in care.
The analysis explores patterns across age, gender, race, diagnoses, and medications to understand what factors contribute to early readmission. Insights from this project can help healthcare providers improve diabetes management and reduce preventable readmissions.

##  Data Structure Overview

This project uses the Diabetes 130-US hospitals for years 1999–2008 dataset, containing over 100,000 patient records from U.S. hospitals. Each row represents a hospital encounter related to diabetes care.
The dataset includes more than 50 features grouped into patient demographics, hospital encounter details, diagnoses, and medications.

| Column Name                | Description                                             |
| -------------------------- | ------------------------------------------------------- |
| `encounter_id`             | Unique identifier for each hospital visit               |
| `patient_nbr`              | Unique patient ID (not anonymized across visits)        |
| `race`                     | Patient's race (e.g., Caucasian, AfricanAmerican, etc.) |
| `gender`                   | Patient's gender (Male/Female)                          |
| `age`                      | Age group of the patient (e.g., \[60-70))               |
| `admission_type_id`        | Admission type (e.g., emergency, elective)              |
| `discharge_disposition_id` | Discharge outcome (e.g., discharged home, died)         |
| `admission_source_id`      | Source of admission (e.g., referral, emergency room)    |
| `time_in_hospital`  
|                                                         |

Target Variable

readmitted — Indicates whether a patient was readmitted:

<30: Readmitted within 30 days

>30: Readmitted after 30 days

NO: No readmission

## Executive Summary
