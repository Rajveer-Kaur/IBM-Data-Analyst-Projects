# 🚗 Analyzing the Impact of Recession on Automobile Sales

This project was developed as part of the **IBM Data Analyst Professional Certificate** and focuses on understanding how economic recessions have impacted automobile sales over time. The project involves both static and interactive visualizations built using Python libraries such as **Matplotlib**, **Seaborn**, **Folium**, **Plotly**, and **Dash**.

---

## 📌 Project Scenario

As a newly hired **Data Analyst** at **XYZAutomotives**, your task is to analyze historical data to uncover how automobile sales were influenced during past recession periods. Your work will inform executive decisions and strategy by providing visual insights through charts and dashboards.

---

## 🧩 Project Breakdown

The project is completed in **two main parts** across **two files**:

### 🔹 Part 1: Static Data Analysis and Visualization  
📁 **File**: `recession_auto_sales_analysis.ipynb`

In this Jupyter Notebook, we use:
- **Matplotlib** & **Seaborn** for line charts, bubble plots, scatter plots, and pie charts
- **Folium** for geospatial visualization

**Tasks Included:**
1. Line chart for annual automobile sales trend  
2. Multi-line plot by vehicle type to observe trends during recession  
3. Recession vs non-recession sales comparison using Seaborn  
4. Subplots comparing GDP trends during/after recession  
5. Bubble plot to show seasonality's impact  
6. Scatter plot showing relationship between price and sales  
7. Pie charts for ad spending (overall & by vehicle type)  
8. Line chart for unemployment rate's effect on vehicle sales

---

### 🔸 Part 2: Interactive Dashboard using Plotly & Dash  
📁 **File**: `dashboard_app.py`

This part includes building a fully functional interactive dashboard:
- Dropdown filters for year or report type
- Callback functions to update graphs based on user inputs
- Dynamic charts for:
  - Recession period statistics
  - Yearly sales analysis

**Dash Features:**
- Interactive line, bar, and pie charts
- Responsive layout
- Simple, clear interface for directors to drill into the data

---

## 📊 Dataset Description

The dataset used here is **synthetic** (artificially generated) for educational purposes. It contains the following fields:

- `Date`: Timestamp of observation  
- `Recession`: Binary indicator (1 = recession, 0 = normal)  
- `Automobile_Sales`: Number of cars sold  
- `GDP`, `Unemployment_Rate`, `Consumer_Confidence`, `Seasonality_Weight`, `Price`, `Advertising_Expenditure`, etc.  
- `Vehicle_Type`: Category of vehicles (e.g., Executive, Sports)  
- `Competition`: Market competitiveness indicator  
- `Month`, `Year`: Extracted from `Date`

---

## 🧠 Key Skills Demonstrated

- Data Manipulation with **Pandas**
- Static & Interactive **Data Visualization**
- **Time Series Analysis**
- **Dash App Development** (callbacks, layouts, interactivity)
- Insightful storytelling through plots

---

## 🛠️ Tools & Technologies

- Python  
- Jupyter Notebook  
- Matplotlib & Seaborn  
- Plotly & Dash  
- Pandas, NumPy  
- Folium (geospatial mapping)  

---

## 📁 Repository Structure

recession-sales-impact/
│
├── recession_auto_sales_analysis.ipynb # Jupyter notebook with static visualizations
├── dashboard_app.py # Dash application (interactive dashboard)
├── images/ # Screenshots of charts and dashboards
└── README.md # Project overview and documentation
