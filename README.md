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

This project analyzes diabetes-related hospital readmissions in the U.S. from 1999 to 2008 to uncover key patterns and risk factors.

11.16% of patients were readmitted within 30 days.

Patients aged 70–90 had the highest readmission rates.

Female patients (11.24%) were slightly more likely to be readmitted than males (11.06%).

African American and Caucasian patients had the highest readmission rates by race.

Heart-related conditions, especially heart attacks, were the most common reasons for readmission.

Patients on Metformin with steady or increased dosage had lower readmission rates.

Patients on Insulin with dosage changes (up/down) were more likely to be readmitted, suggesting more unstable conditions.

## Insights

Based on the diabetes hospital readmission dataset (1999–2008), the following insights were uncovered:

11.16% of patients were readmitted within 30 days of discharge.

Patients aged 70–90 years had the highest likelihood of early readmission.

Female patients (11.24%) were slightly more likely to be readmitted than male patients (11.06%).

African American and Caucasian patients showed the highest rates of readmission among all racial groups.

The most common primary diagnosis among readmitted patients was heart-related conditions, particularly heart attacks.

Patients prescribed Metformin with a steady or increased dosage had lower readmission rates, suggesting better stability or effectiveness of the treatment.

Patients on Insulin with dosage changes (either up or down) were more likely to be readmitted, possibly indicating more complex or unstable diabetes conditions.

These insights offer a clearer understanding of the patient groups most at risk and can help improve treatment plans and reduce avoidable hospital readmissions.
