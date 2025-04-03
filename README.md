🏥 Healthcare Waiting List Analysis - Power BI Dashboard

📌 Overview

This project analyzes Inpatient and Outpatient Waiting Lists from 2018 to 2021, identifying key trends in patient wait times across different medical specialties. The data is cleaned, modeled, and visualized using Power BI.

📂 Dataset

IN_WL 2018-2021 → Inpatient & Day Case Waiting List data

Op_WL 2018-2021 → Outpatient Waiting List data

Mapping_Specialty.csv → Links specialty codes to broader specialty groups

🔧 Process & Workflow

Data Cleaning

Removed duplicates, handled missing values

Standardized column names and formats

Data Merging & Modeling

Combined Inpatient & Outpatient datasets into a single table (All_Data)

Linked All_Data with Mapping_Specialty for better classification

Created relationships between tables in Power BI

Measure Table (DAX Calculations)

Created Total Patients, % Wait Time Breakdown, YOY Trends, Top Specialties

Dashboard Creation

Designed interactive visualizations for better insights

Implemented filters by specialty, time bands, case type

📊 Key Insights

Total Cases: Outpatients (~88%) dominate the waiting lists.

Longest Wait Times: 18+ months category has the highest patient count (~4.3M).

COVID-19 Impact: Notable dip in waiting lists in 2020.

Top Specialties with High Waitlists: Ophthalmology, General Surgery, Dermatology, Orthopaedics.

🛠️ Tools & Technologies

Power BI → Data Modeling, DAX, Dashboard Design

GitHub → Version Control & Project Sharing

🚀 How to Use

Clone the repo:

git clone https://github.com/yourusername/healthcare-waitlist-dashboard.git

Open Power BI and load the .pbix file.

Explore insights using interactive filters.

📢 Future Enhancements

Add forecasting models to predict future waiting list trends.

Incorporate regional analysis for better location-based insights.

Improve UI/UX design with more dynamic visuals.

✨ Author

Yash - Data Analyst | Power BI Enthusiast

