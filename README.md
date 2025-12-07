# healthcare-SQL-analytics-project
End-to-end SQL project analyzing hospital KPIs using PostgreSQL
Healthcare SQL Analytics Project (PostgreSQL)

A real-world analytics project for hospitals & healthcare decision-making.

📊 Project Overview

This project simulates a real hospital database and applies SQL analytics to solve key business problems such as:

Reducing patient readmissions

Improving department efficiency

Monitoring doctor performance

Understanding cost & insurance coverage

Identifying high-risk patients

Analyzing medication usage

Tracking monthly admission trends

All analysis is performed using PostgreSQL, a widely-used database system in Canadian healthcare & tech companies.

🧱 Database Schema (ERD Structure)

Tables:

patients (patient details)

doctors (specialty & doctor info)

admissions (hospital visits)

billing (cost, insurance, out-of-pocket)

medications (treatments prescribed)

Relationships:

One patient → many admissions

One doctor → many admissions

One admission → one billing record

One patient → many medications

💾 Dataset

Synthetic (dummy) dataset with:

20 patients

10 doctors

40 admissions

40 billing rows

40 medication rows

Designed to reflect realistic patterns in healthcare.

📂 Project Structure
data/
    create_tables.sql      → all table creation scripts
    insert_data.sql         → sample dataset inserts

queries/
    01_avg_length_of_stay.sql
    02_top_diagnoses.sql
    03_readmission_rate.sql
    04_department_load.sql
    05_doctor_performance.sql
    06_high_risk_patients.sql
    07_avg_out_of_pocket.sql
    08_costly_diagnoses.sql
    09_medication_usage.sql
    10_monthly_trend.sql

insights/
    business_insights.md    → interpretation of results

🧠 Key SQL Analyses
✔ 1. Average Length of Stay (ALOS)

Helps hospitals reduce bed occupancy & optimize operations.

✔ 2. Most Common Diagnoses

Finds top diseases increasing hospital load.

✔ 3. 30-Day Readmission Rate

Critical KPI in Canadian healthcare systems.

✔ 4. Department Workload Analysis

Supports staff/resource planning.

✔ 5. Doctor Performance Dashboard

Evaluates doctors based on patient volume & readmissions.

✔ 6. High-Risk Patients

Patients with repeat visits or complications.

✔ 7. Financial Cost Analysis

Insurance vs. out-of-pocket — helps financial planning.

✔ 8. Medication Usage

Most prescribed drugs.

✔ 9. Monthly Admission Trend

Seasonal or pattern analysis.

🧩 Tools Used

SQL (PostgreSQL)

pgAdmin

Database Design

Data Analysis

📈 Business Value

This project mimics real hospital data scenarios and shows SQL skills in:

Healthcare analytics

Cost optimization

Operational insights

Patient outcome analysis

KPI reporting

👩‍💻 About Me

Sucharita Tunga — Data Scientist with 5+ years of experience in analytics & data modeling.
Permanent Resident, Canada.
