# E-Commerce Analytics Using PySpark, Power BI & Streamlit

## Project Overview

This project analyzes e-commerce sales performance and customer purchasing behavior using Big Data technologies. The goal is to transform raw transactional data into meaningful business insights that support data-driven decision-making.

The project integrates **PySpark for large-scale data processing, Power BI for interactive dashboards, and Streamlit for web-based data visualization**.

## Dataset

**Dataset:** Brazilian E-Commerce Public Dataset by Olist

**Source:** [Kaggle – Olist Brazilian E-Commerce](https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce)

The dataset contains approximately 100,000 e-commerce orders placed in Brazil between 2016 and 2018.

It includes nine interconnected tables covering:

- Customer information
- Orders and order items
- Products and sellers
- Payment transactions
- Customer reviews
- Geographic information

## Project Objectives

The project aims to answer five key business questions:

1. How do sales and revenue change over time and across regions?
2. Which product categories generate the highest revenue?
3. How can customers be segmented based on Recency, Frequency, and Monetary (RFM) analysis?
4. What are the purchasing patterns and repeat purchase rates of customers?
5. How does delivery performance relate to customer satisfaction?

## Technologies Used

| Technology | Purpose |
|---|---|
| Python | Data analysis and application development |
| PySpark | Large-scale data processing and transformation |
| Spark SQL | Data aggregation and analytical queries |
| Power BI | Interactive business dashboards |
| Streamlit | Web-based analytics application |
| Pandas | Working with processed and aggregated data |

## Project Workflow

**Raw Data → PySpark → Data Cleaning & Transformation → Business Analytics → Power BI / Streamlit → Business Insights**

## Project Structure

```text
E-Commerce-Analytics/
├── data/
│   ├── raw/
│   └── processed/
├── notebooks/
│   ├── 01_data_pipeline.ipynb
│   └── 02_business_analytics.ipynb
├── dashboard/
│   └── ecommerce_dashboard.pbix
├── streamlit/
│   └── app.py
├── reports/
│   ├── final_report.pdf
│   └── presentation.pptx
├── requirements.txt
└── README.md
```

*The structure above represents the planned project organization.*

## How to Run

1. Clone the GitHub repository.
2. Install the required dependencies using `pip install -r requirements.txt`.
3. Download the dataset from Kaggle and place the CSV files in `data/raw/`.
4. Run the PySpark notebooks to process the data and generate analytical outputs.
5. Open the Power BI dashboard file to explore the results.
6. Launch the Streamlit application using:

```bash
streamlit run streamlit/app.py
```

**Note:** Apache Spark requires a compatible Java and Python environment. The final dependency versions and environment configuration will be documented after development.

## Expected Outcomes

- A reproducible PySpark data processing pipeline.
- Exploratory data analysis and business KPIs.
- Customer segmentation using RFM analysis.
- Interactive Power BI dashboards.
- A Streamlit analytics application.
- Actionable business insights and recommendations.

## Team Responsibilities

| Role | Responsibilities |
|---|---|
| Data Engineer & Analyst | PySpark pipeline, EDA, KPI calculations, RFM analysis |
| BI & App Developer | Power BI dashboard and Streamlit application |
| Report Writer | Research report, findings, insights, and recommendations |
| Presentation Coordinator | Slides, project documentation, and final submission |
