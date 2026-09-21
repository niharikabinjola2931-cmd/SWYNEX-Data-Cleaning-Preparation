# SWYNEX Data Cleaning and Preparation

## Project Overview

This project was completed as part of the **SWYNEX Technologies Data Analyst Internship**.

The objective was to clean and validate a public healthcare dataset by checking for missing values, duplicate records, incorrect data types, and inconsistent values.

## Dataset

**India Hospital Readmission Dataset (2015–2024)**

The dataset contains information related to:

* Hospital admissions
* Patients
* Diagnoses
* Billing
* Hospitals

The dataset was obtained from Kaggle and contains synthetic healthcare data.

## Tools Used

* Microsoft Excel
* Power Query
* GitHub

## Data Cleaning and Validation

The following checks were performed across the five datasets:

### Missing Values

Checked all columns for blank, null, or empty values.

**Result:** No missing values were identified in the datasets.

### Duplicate Records

Checked key identifier columns for duplicate records.

**Result:** No duplicate records were identified based on the relevant unique identifiers.

### Data Types

Verified that columns had appropriate data types, including:

* Text for identifiers and categorical fields
* Date for admission and discharge dates
* Numeric types for measurements, costs, and counts
* Boolean/flag values where applicable

### Inconsistent Values

Checked categorical fields for inconsistent or unexpected values.

Examples included:

* Gender
* State
* Insurance type
* Hospital tier
* Admission type
* Ward type
* Discharge type
* Cost category
* Diagnosis category

The values were checked for consistency and standardized where required.

### Data Validation

Relationships between datasets were also validated using key fields.

The following relationships were checked:

* Admissions → Patients
* Admissions → Hospitals
* Billing → Admissions
* Diagnoses → Admissions

No unmatched records were identified during these referential integrity checks.

## Project Structure

```text
data/
├── raw/
│   ├── admissions.csv
│   ├── billing.csv
│   ├── diagnoses.csv
│   ├── hospitals.csv
│   └── patients.csv
│
└── cleaned/
    ├── admissions_cleaned.csv
    ├── billing_cleaned.csv
    ├── diagnoses_cleaned.csv
    ├── hospitals_cleaned.csv
    └── patients_cleaned.csv
```

## Outcome

The datasets were reviewed, validated, and prepared for further analysis. The cleaned datasets can be used for the next stage of the project, including **data analysis and Power BI dashboard development**.

## Internship

**Organization:** SWYNEX Technologies
**Project:** Data Cleaning and Preparation
**Internship Duration:** September 20, 2026 – October 20, 2026
