# Hospital_Emergency_Room_Dashboard
Tools Used: Microsoft Excel (Pivot Tables, Pivot Charts, Slicers, Conditional Formatting, Excel Formulas)
Dataset Size: 9,216 Patient Records
🏥 Project Overview

This project analyzes real-world emergency room (ER) data to identify operational bottlenecks, patient flow patterns, demographic trends, satisfaction scores, and referral behaviors.
Using Excel, an interactive, dynamic dashboard was built to help healthcare administrators monitor key metrics and make data-driven decisions to improve ER efficiency.

📂 Dataset Description

The dataset contains 9,216 records and 12 columns, including:

Patient Age

Patient Gender

Visit Date & Treatment Completion Date

Wait Time (Minutes)

Admission Status (True/False)

Patient Satisfaction Score

Department Referral

Arrival Mode

📌 Key Dataset Statistics

Avg Age: 40.4 years

Avg Wait Time: 28.7 minutes

Median Wait Time: 28 minutes

Average Satisfaction Score: 4.98/10

Admission Rate: 50.03%

Delayed Treatments (>30 minutes): ~39%

🛠 Excel Techniques Used
🔧 Data Cleaning & Preparation

Removed duplicates & standardized gender labels (M/Male, F/Female)

Created age groups using nested IF formulas

Derived attended-within-time flag (≤30 min = “Within Time”)

Cleaned referral department names

🔢 Excel Formulas Applied

IF(), COUNTIF(), COUNTIFS()

AVERAGE(), MEDIAN(), MIN(), MAX()

VLOOKUP()

SEQUENCE() for date table

Conditional Formatting for highlighting delays & scores

📊 Dashboard Components

Pivot Tables for aggregations

Pivot Charts (Bar, Column, Donut, Line)

KPI Cards

Slicers for:

Gender

Admission Status

Department Referral

Age Group

📈 Key Insights (Data-Driven)
1️⃣ Patient Demographics

Nearly balanced gender distribution (4700 males, 4470 females)

Largest volume from ages 30–50 years

2️⃣ Operational Performance

Avg wait time: 28.7 minutes

39% of patients waited more than 30 minutes

Max wait time recorded: 60 minutes

3️⃣ Satisfaction Trends

Avg satisfaction score: 4.98/10

Lower scores correlate with long wait times

4️⃣ Admission & Referral Analysis

Admission Rate: 50.03%

Top referral departments:

General Practice: 1,840

Orthopedics: 995

Physiotherapy: 276

Cardiology: 248

5,400 patients did not require a referral—treated within the ER

🩺 Recommendations
✔ Reduce Wait Times

Implement fast-track triage for low-severity patients.

✔ Adjust Staffing During Peak Hours

Age 30–50 group drives highest ER load → optimize shift schedules.

✔ Improve Patient Communication

Frequent updates during wait periods can raise satisfaction above 5.

✔ Strengthen High-Referral Departments

General Practice & Orthopedics need additional resources.
