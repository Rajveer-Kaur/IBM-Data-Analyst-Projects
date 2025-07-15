# 🏙️ Chicago Data Analysis with SQL

This project is part of the IBM Data Analyst Professional Certificate program. It demonstrates the use of SQL to analyze real-world datasets related to the city of Chicago — including crime statistics, socioeconomic indicators, and public school performance.

---

## 📌 Project Objectives

- Understand and explore three different datasets from the Chicago Data Portal
- Load datasets into a **SQLite** relational database
- Perform **SQL queries** to extract meaningful insights
- Use **sub-queries** and **aggregations** to answer complex questions

---

## 🗃️ Datasets Used

1. **Chicago Socioeconomic Indicators**
   - Contains socioeconomic metrics and hardship index for various community areas  
   - [Original Source](https://data.cityofchicago.org/Health-Human-Services/Census-Data-Selected-socioeconomic-indicators-in-C/kn9c-c2s2)

2. **Chicago Public Schools Report Cards**
   - School-level performance data used for CPS School Report Cards  
   - [Original Source](https://data.cityofchicago.org/Education/Chicago-Public-Schools-Progress-Report-Cards-2011-/9xs2-f89t)

3. **Chicago Crime Data**
   - Incident-level data for reported crimes in the city  
   - [Original Source](https://data.cityofchicago.org/Public-Safety/Crimes-2001-to-present/ijzp-q8t2)

---

## 🧰 Tools & Technologies

- Python (Jupyter Notebook)
- `pandas`
- `sqlite3`
- SQL (Sub-queries, Joins, Aggregations)

---

## 🧠 Key Tasks & Questions Solved

- Create tables and import data using Python + SQLite
- Join and filter data to derive insights
- Use **sub-queries** to solve complex problems like:

### ✔️ Sample Problems Solved:

- 🏙️ **Which community area is most crime-prone?**  
  → Used `GROUP BY` + `ORDER BY` to find the area number with the most crime incidents.

- 📉 **Which community area has the highest hardship index?**  
  → Used a **sub-query** to extract the community area name with the highest score.

- 🚨 **Which community area has the highest number of crimes?**  
  → Used another sub-query and aggregation to return the area name with the most incidents reported.

---

## 📂 Project Files

- `chicago_sql_analysis.ipynb`: Main notebook containing code, queries, and answers
- `ChicagoCrimeData.csv`
- `ChicagoPublicSchools.csv`
- `ChicagoCensusData.csv`
- `README.md`

---

## 📈 Learning Outcomes

- Hands-on experience with real datasets in a city governance context
- Writing and optimizing SQL queries inside Python
- Data normalization, aggregation, and sub-query writing in SQLite
- Better understanding of the intersection between public policy and data

---

## ✅ Author Note

This project is a part of my journey toward becoming a data analyst. It showcases practical experience in SQL-based analysis using open data, which is vital in many real-world data science roles.

Feel free to explore the code and reach out with feedback!
