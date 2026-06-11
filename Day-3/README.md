# Salesforce Administrator Track – Day 3

## What is Data Management?

Data Management is the process of collecting, storing, maintaining, importing, exporting, and securing data in Salesforce. Good data management ensures data accuracy and reliability.

---

## What is Data Loader?

Data Loader is a Salesforce tool used to import, export, update, upsert, and delete large volumes of records.

### Features of Data Loader

- Import data
- Export data
- Update records
- Upsert records
- Delete records
- Bulk data operations

---

## Difference Between Import Wizard and Data Loader

| Import Wizard | Data Loader |
|--------------|-------------|
| Web-based tool | Desktop application |
| Easy to use | Advanced tool |
| Up to 50,000 records | Millions of records |
| Limited functionality | Full functionality |
| No delete option | Supports delete |
| Beginner friendly | Admin/Developer friendly |

---

# Data Migration Challenges

Assume Vishnu Institute is migrating data from Excel to Salesforce.

### Challenges

1. Duplicate student records
2. Missing email addresses
3. Invalid phone numbers
4. Incorrect department names
5. Missing mandatory fields
6. Data mapping issues
7. Inconsistent formatting
8. Legacy data errors
9. Incorrect attendance values
10. Invalid placement records

---

## Data Cleaning Requirements

- Remove duplicate students
- Fix invalid email addresses
- Standardize phone numbers
- Correct spelling mistakes
- Validate attendance percentages
- Verify placement status
- Remove incomplete records

---

## Duplicate Records That May Exist

- Duplicate Student IDs
- Duplicate Faculty IDs
- Duplicate Email Addresses
- Duplicate Phone Numbers
- Duplicate Placement Records

---

## Required Validations

- Email Validation
- Phone Number Validation
- Required Fields Validation
- Student ID Uniqueness
- Attendance Range Validation
- Placement Status Validation

---

# Data Quality Problems

| Problem | Business Problem | Salesforce Solution |
|----------|-----------------|---------------------|
| Missing Email | Cannot contact student | Required Field |
| Wrong Phone Number | Communication failure | Validation Rule |
| Duplicate Student | Incorrect reports | Duplicate Rules |
| Wrong Branch | Wrong analytics | Picklists |
| Invalid Placement Status | Reporting errors | Validation Rule |
| Missing Student ID | Tracking issues | Required Field |
| Duplicate Faculty | Confusion in records | Duplicate Rules |
| Incorrect Attendance | Wrong decisions | Validation Rule |
| Blank Department | Reporting issues | Required Field |
| Outdated Records | Poor analytics | Regular Data Audits |

---

# Consequences of Incorrectly Importing 50,000 Records

1. Incorrect reports
2. Wrong dashboards
3. Inaccurate placement tracking
4. Wrong notifications
5. Duplicate student records
6. Incorrect attendance reports
7. Misleading analytics
8. Poor decision making
9. Reduced data trust
10. Time-consuming cleanup process

---

# Reflection

Clean data is essential for business success. Reports, dashboards, and analytics depend on accurate data. Poor data quality can lead to incorrect decisions and operational issues.

---
