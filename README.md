# 📊 Customer Behavior Data Analysis Pipeline

This project demonstrates a professional **End-to-End Data Analytics Workflow**, transforming raw shopping data into strategic business insights. It utilizes a powerful combination of **Python**, **SQL**, and **Power BI** to analyze customer trends and performance.

## 📌 Project Overview

The objective is to analyze customer behavior and purchasing patterns through three core stages:
1.  **Preprocessing & EDA (Python):** Cleaning, normalizing, and exploring raw data to discover initial patterns.
2.  **Advanced Analytics (SQL):** Leveraging SQL queries for customer segmentation, loyalty assessment, and identifying key purchase drivers.
3.  **Data Visualization (Power BI):** Building an interactive dashboard to track key KPIs and consumer trends.

## 🛠 Tech Stack
- **Languages:** Python (Pandas, NumPy, Matplotlib, Seaborn).
- **Database:** SQL (MySQL/Postgres/SQLite) - for structured data storage and complex querying.
- **BI Tool:** Power BI - for interactive dashboard design.
- **Others:** Jupyter Notebook, Git.

## ⚙️ Project Workflow

### Phase 1: Data Processing with Python
- Imported raw datasets and performed data auditing for missing values and duplicates.
- Standardized data formats and executed **Feature Engineering**.
- Conducted **Exploratory Data Analysis (EDA)** to visualize distributions and correlations.
- Exported cleaned data into the SQL database for structured storage.

### Phase 2: In-depth Querying with SQL
- Designed the database schema and established table relationships.
- Developed SQL scripts to answer business-critical questions:
    - Identifying top-tier customer segments by revenue.
    - Analyzing seasonal shopping trends and high-performing product categories.
    - Calculating Average Order Value (AOV) and Purchase Frequency.

### Phase 3: Interactive Dashboarding with Power BI
- Established a direct connection between Power BI and the SQL database.
- Created interactive visualizations: Scatter Plots, Trend Lines, and Heatmaps.
- Derived actionable insights and provided business recommendations based on data evidence.

## 📂 Project Structure & Documentation

To provide a comprehensive view of the analysis, the following key documents and assets are included in this repository:

* **[Business Problem Document.pdf](./Business%20Problem%20Document.pdf)**: Detailed scope of the project, defining business objectives and core analytical questions.
* **[Customer Shopping Behavior Analysis.pdf](./Customer%20Shopping%20Behavior%20Analysis.pdf)**: A comprehensive analytical report summarizing key findings, methodology, and strategic business recommendations.
* **Power BI Dashboard (.pbix)**: The source file for interactive data visualization. For those without Power BI Desktop, the static views and insights are captured in the Analysis PDF above.
* **Data/**: Contains both raw and processed datasets.
* **Notebooks/**: Jupyter Notebooks for Python-based data cleaning and EDA.
* **SQL_Queries/**: SQL scripts used for deep-dive analysis and metric calculation.

## 🚀 How to Run
1. Clone the repository to your local machine.
2. Review the **Business Problem Document.pdf** to understand the analysis context.
3. Execute the Notebooks in the `Notebooks/` folder to process the data.
4. Import the resulting data into your SQL Server and run the scripts in `SQL_Queries/`.
5. Open the `.pbix` file in Power BI Desktop or refer to the **Customer Shopping Behavior Analysis.pdf** for the final results and insights.