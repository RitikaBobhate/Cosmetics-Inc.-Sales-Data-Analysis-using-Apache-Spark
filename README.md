# Cosmetics Sales Data Analysis using Apache Spark

## Project Overview

This project analyzes cosmetics sales data using **Apache Spark (PySpark)** to explore product performance, customer purchase patterns, and pricing trends. The objective was to simulate a real-world data analytics workflow involving **data cleaning, transformation, exploratory analysis, and visualization** on a retail dataset.

The project demonstrates how large datasets can be processed efficiently using distributed computing frameworks.

---

## Objectives

* Clean and preprocess raw sales data
* Perform large-scale data processing using Apache Spark
* Identify sales patterns across product categories and brands
* Analyze price distributions and purchasing behavior
* Generate insights that could support data-driven business decisions

---

## Dataset Description

The dataset contains transactional information from a cosmetics retail platform, including attributes such as:

* Product category
* Brand
* Product price
* Event type (view, cart, purchase)
* Timestamp of customer interaction

Before analysis, the dataset required preprocessing to remove inconsistencies and prepare it for structured analysis.

---

## Tools and Technologies

* **Apache Spark (PySpark)** – distributed data processing
* **Python** – data analysis and scripting
* **Pandas & NumPy** – data preprocessing
* **Matplotlib & Seaborn** – data visualization
* **Jupyter Notebook / Google Colab** – analysis environment

---

## Project Workflow

### 1. Data Cleaning

The raw dataset was processed to:

* Handle missing or inconsistent values
* Standardize column formats
* Prepare the data for Spark processing

### 2. Spark Environment Setup

A Spark session was initialized to enable distributed data processing and efficient handling of large datasets.

### 3. Data Transformation

Key transformations included:

* Filtering relevant event types
* Aggregating sales data by product and category
* Structuring the dataset for analytical queries

### 4. Exploratory Data Analysis (EDA)

EDA was performed to understand:

* Sales distribution across product categories
* Brand-level product performance
* Price distribution patterns
* Customer purchase trends

### 5. Visualization

Data visualizations were created to highlight patterns and trends within the dataset and improve interpretability of results.

---

## Key Insights

Some notable insights from the analysis include:

* Certain cosmetic categories consistently generate higher purchase activity.
* Brand-level performance varies significantly across product segments.
* Price distribution analysis reveals distinct purchasing patterns among customers.

These insights could support **inventory planning, pricing strategies, and marketing decisions** in retail environments.

---

## Repository Structure

```
Cosmetics-Sales-Analysis
│
├── Cosmetics_Inc_Sales_Data_Analysis_using_Apache_Spark.ipynb
├── Cosmetics Inc. - Data for Cleaning - Sheet1.csv
└── README.md
```

---

## How to Run the Project

### 1. Clone the repository

```
git clone https://github.com/your-username/your-repository-name.git
```

### 2. Install required libraries

```
pip install pyspark pandas numpy matplotlib seaborn
```

### 3. Run the notebook

Open the notebook in **Jupyter Notebook or Google Colab** and execute the cells to reproduce the analysis.

---

## Future Improvements

Possible extensions for this project include:

* Building machine learning models for sales prediction
* Implementing product recommendation systems
* Deploying Spark pipelines on cloud platforms
* Integrating real-time sales data processing

---

## Author

**Ritika Bobhate**

Final-year Engineering Student
Data Analytics | Machine Learning | Big Data Analytics

