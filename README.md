# Deloitte-Virtual-Internship - Daikibo Factory Telemetry Analysis

This project focuses on analyzing machine telemetry data from Daikibo's global factories to identify locations and machine types with the most frequent breakdowns. The goal is to help the company optimize maintenance planning and reduce downtime.

## 📊 Overview

Using data collected from Daikibo's four factories, this analysis answers two key business questions:

1. **Which factory experiences the most machine breakdowns?**
2. **Which machines break down most frequently in that factory?**

The insights are presented through an interactive Tableau dashboard, making it easy to visualize unhealthy machines and critical locations.

## 🏢 About the Company

**Daikibo** is an international manufacturing company with the following factory locations:

- **Meiyo** (Tokyo, Japan)
- **Seiko** (Osaka, Japan)
- **Berlin** (Berlin, Germany)
- **Shenzhen** (Shenzhen, China)

Each location operates 9 types of machines that send telemetry data every 10 minutes. The dataset contains one month of telemetry records (May 2021).

## 🛠 Tech Stack

- **Excel** (Data cleaning and preparation)
- **Tableau** (Dashboard creation and data visualization)
- **JSON** (Raw data format)
- **Custom Column**: A new column called `Equality Class` was created for additional classification during analysis.

## 📷 Data and Dashboard
- **View Dashboard Here**: [Tableau Dashboard](https://public.tableau.com/app/profile/mahnoor.rafique/viz/DaikiboTelemetryData_17463691369650/Dashboard1)
- **View Data Here**: [Data](https://github.com/MaryamRafiquee/Deloitte-Virtual-Internship/blob/main/Excel%20Data.xlsx)

## 🔍 Key Findings

- **Factory with Most Downtime**: Daikibo Factory Seiko (Osaka, Japan)
- **Most Unhealthy Machine**: Laser Welding Machines (at Seiko)

## ✅ Features

- Factory-wise downtime comparison
- Machine-wise downtime breakdown
- Custom `Equality Class` column to segment machine health status
- Clean, interactive Tableau visuals

## 📌 Conclusion

Through this project, we successfully identified critical pain points in Daikibo's production line by leveraging machine telemetry data. The analysis clearly highlighted that **Daikibo Factory Seiko** faces the highest machine downtime, predominantly due to **Laser Welding Machines**. These insights can help the company prioritize preventive maintenance, allocate resources more efficiently, and minimize costly disruptions in the production workflow.
