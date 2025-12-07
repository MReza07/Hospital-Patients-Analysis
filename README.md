## 🏥 Hospital Patients Analysis Dashboard

Power BI Healthcare Analytics Project

A Power BI dashboard designed to analyze hospital patient demographics, treatment outcomes, department performance, insurance distribution, and billing patterns for improved healthcare decision-making.

## 📁 Project Overview

This project provides a comprehensive analysis of patient data in a hospital environment. The dashboard highlights key patient metrics such as age, gender, treatment outcomes, insurance type, department-wise distribution, average test scores, bed utilization, and billing insights.

It helps hospital administrators and medical staff monitor performance, identify trends, and make data-driven decisions to improve patient care.

📷 Dashboard Preview https://github.com/MReza07/Hospital-Patients-Analysis/tree/main/Report

## 📝 Project Summary

| Section              | Summary                                                                                             |
| -------------------- | --------------------------------------------------------------------------------------------------- |
| **Dashboard Title**  | Hospital Patients Analysis                                                                          |
| **Tools Used**       | Power BI, Power Query, DAX                                                                          |
| **Total Records**    | 350 Patients                                                                                        |
| **Key Metrics**      | Total Patients, Avg Age, Avg Days Admitted, Avg Test Score, Bed Utilization, Avg Bill Amount        |
| **Business Purpose** | Improve patient care quality, department performance, operational efficiency & billing transparency |


## 🎯 Key Features
✔ Interactive dashboard with dynamic slicers:

Gender

Department

Treatment Outcome

✔ KPI Cards include:

Total Patients

Total Outcomes

Average Patient Age

Average Days Admitted

Average Test Score

Bed Utilization Index

Average Bill Amount

✔ Visual Analysis:

Recovered Patients by Department

Patients by Treatment Outcome

Insurance Type Distribution

Patient Count by Gender

Patient Count by Department

Billing Amount vs Test Score (Scatter Plot)

## 📈 Key Insights

Orthopedics and Oncology show high patient volumes.

Neurology and Orthopedics report the highest recovery counts.

Government insurance covers the largest segment (37%).

Male patients have the highest count, followed by Female.

Higher bill amounts correlate with higher test scores (positive trend).

Bed Utilization Index is strong at 73%, indicating efficient capacity management.

## 📂 Project Structure

📁 Hospital-Patients-Analysis

│
├── 📄 Dataset/

│     └── Hospital_Patient_Dataset.xlsx
│
├── 📄 PBIX/

│     └── Hospital Patients Analysis.pbix
│
├── 📄 Screenshots/

│     ├── Hospital Patients Analysis.PNG

│     ├── Patients by Department.PNG

│     ├── Insurance Distribution.PNG

│     └── Billing vs Test Score.PNG
│
└── 📄 README.md

## 📐 Sample DAX Measures

DAX

Total Patients = COUNT(Patient_Data[Patient_ID])

Total Outcomes = COUNT(Patient_Data[Treatment_Outcome])

Avg Patient Age = AVERAGE(Patient_Data[Age])

Avg Days Admitted = AVERAGE(Patient_Data[Days_Admitted])

Bed Utilization Index = DIVIDE([Total Patients], 480)   -- Assuming 480 total beds

Avg Test Score = AVERAGE(Patient_Data[Test_Score])

## 📊 Data Dictionary


| Column Name       | Description                                     |
| ----------------- | ----------------------------------------------- |
| Patient_ID        | Unique identifier for each patient              |
| Age               | Age of the patient                              |
| Gender            | Male / Female / Other                           |
| Department        | Hospital department (Neurology, Oncology, etc.) |
| Days_Admitted     | Total inpatient days                            |
| Treatment_Outcome | Recovered, Improved, Critical, Deceased         |
| Insurance_Type    | Government / Private / None                     |
| Bill_Amount       | Total billing amount                            |
| Test_Score        | Diagnostic test result score                    |


## 🚀 How to Open the Dashboard

Go to the PBIX folder

Click Download → Raw to get the Power BI file

Open Hospital Patients Analysis.pbix in Power BI Desktop

Use the slicers to explore the data

(Optional) Download the dataset from the Dataset folder


## 🛠 Tools & Technologies

Power BI Desktop

Power Query (Data Cleaning & Transformation)

DAX (Custom Measures)

Data Modeling

Interactive Visualization

## 📜 License

This project is released under the MIT License.


## 📬 Contact

Md. Rezaul Repon

Linkedin:www.linkedin.com/in/repon07

Data Analyst (Power BI | SQL | Python)

🔗 GitHub: https://github.com/MReza07

📧 Email: reazulrepon@gmail.com





