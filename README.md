# Indian-crime-analysis

A comprehensive data visualization project built using **Power BI** to analyze and interpret crime patterns across India. This project transforms raw data into actionable insights to understand crime distribution, temporal trends, and regional hotspots.

---

## 🚀 Project Overview
This dashboard provides a high-level view of crime statistics in India, enabling users to filter data by state, year, and specific crime types. It aims to assist in understanding public safety trends and identifying areas that require law enforcement focus.

## 🛠️ Process Workflow

### 1. Data Sourcing
* Extracted raw crime datasets from **Kaggle**.
* The data includes various crime categories recorded across different Indian states and Union Territories.

### 2. Data Preprocessing (ETL)
* **Power Query**: Cleaned missing values and handled data inconsistencies.
* **Standardization**: Uniformly formatted State/UT names for accurate mapping.
* **Transformation**: Normalized data structures to ensure optimal performance in Power BI.

### 3. Data Modeling
* Implemented a Star Schema or Snowflake Schema (as applicable).
* Established relationships between State-wise, Year-wise, and Crime-type tables.
* Created **DAX Measures** for complex calculations such as Year-over-Year (YoY) growth and crime density.

### 4. Analysis & Visualization
* Developed an interactive interface with drill-down capabilities.
* Used Map visuals for regional hotspot identification.

---

## 📈 Key Insights
* **Trend Analysis**: Visualized crime rate fluctuations over the decades to identify long-term patterns.
* **Regional Hotspots**: Comparative analysis of crime density across different geographic regions.
* **Category Breakdown**: Detailed distribution of crime types (e.g., Theft, Assault, Kidnapping, etc.).

---

## 🖼️ Dashboard Preview
*(Tip: Add a screenshot of your dashboard to the `assets` folder and link it below)*
![Dashboard Screenshot](path/to/your/image.png)

---

## 🧰 Tech Stack
* **Visualization Tool**: Power BI Desktop
* **Data Cleaning**: Power Query (M Language)
* **Analytics**: DAX (Data Analysis Expressions)
* **Source**: Kaggle

## 📂 How to Use
1.  Clone this repository: `git clone https://github.com/your-username/your-repo-name.git`
2.  Ensure you have **Power BI Desktop** installed.
3.  Open the `.pbix` file located in the root directory.
4.  Explore the insights using the interactive filters on the side panel.

---
