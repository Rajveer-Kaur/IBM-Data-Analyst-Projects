# Fleet Inventory Data Analysis with Excel

This project simulates a real-world scenario where I assumed the role of a Junior Data Analyst at a local government office. I was tasked with cleaning and analyzing inventory data related to the government’s vehicle fleet using Microsoft Excel.

The project was conducted in two parts:
1. **Data Cleaning**
2. **Data Analysis with Pivot Tables**

---

## 📂 Part 1: Data Cleaning

**Dataset:**  
The dataset is a modified subset of the publicly available fleet inventory data from Montgomery County, Maryland.  
[Source](https://data.montgomerycountymd.gov/Government/Fleet-Equipment-Inventory/93vc-wpdr)

**Tasks Performed:**
- Converted `.csv` to `.xlsx`
- Adjusted column widths for readability
- Removed empty rows using filters
- Removed duplicate entries
- Corrected spelling errors and removed extra whitespace
- Used Flash Fill to merge department names split across columns
- Cleaned up and standardized the dataset for further analysis

---

## 📊 Part 2: Pivot Table Analysis

**Objective:**  
Prepare summary insights from the cleaned dataset using Excel’s PivotTable functionality.

**Tasks Performed:**
- Formatted the dataset as an Excel Table
- Used AutoSum to calculate:
  - SUM
  - AVERAGE
  - MIN
  - MAX
  - COUNT (on Equipment Count column)
- Created 3 Pivot Tables with different layouts:
  - **Pivot Table 1**: Sum of Equipment Count by Department
  - **Pivot Table 2**: Nested view — Equipment Class under Department (collapsed to only show "Transportation")
  - **Pivot Table 3**: Nested view — Equipment Class above Department (collapsed to only show "CUV")
- Sorted pivot tables by descending order of equipment count
- Performed multi-dimensional analysis using Excel’s PivotTable Fields pane

---

## 🛠️ Skills & Tools Used

- Microsoft Excel (for Web)
- Data Cleaning (Flash Fill, Remove Duplicates, Filters)
- Pivot Tables
- AutoSum and Descriptive Stats
- Tabular Data Formatting

---

## 📁 Files

- `Montgomery_Fleet_Equipment_Inventory_FA_PART_1.xlsx`
- `Montgomery_Fleet_Equipment_Inventory_FA_PART_2.xlsx`
- `README.md`

---

## 📌 Outcome

This project demonstrates foundational Excel skills in cleaning and preparing real-world data, followed by analyzing it with pivot tables to generate business-relevant insights.

---

## 🧠 Scenario Summary

As a junior analyst in a government agency, I was expected to organize and explore fleet equipment data to support inventory planning and operations. My deliverables included a cleaned dataset and summarized views that could later be used in dashboards or executive reports.

