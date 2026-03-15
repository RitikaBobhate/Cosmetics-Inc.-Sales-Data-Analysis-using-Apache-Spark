# Cosmetics Sales Data Analysis using Apache Spark
Overview

This project analyzes cosmetics sales data using Apache Spark to uncover purchasing trends, product performance, and revenue patterns. The goal was to simulate how large-scale retail datasets can be processed using distributed data processing tools.

The analysis focuses on data cleaning, transformation, and exploratory analysis to extract insights that could help businesses optimize product strategy and sales performance.

Dataset

The dataset contains transactional sales data from a cosmetics company, including information such as:

Product category

Brand

Price

Customer interaction data

Purchase events

The raw dataset required preprocessing to handle inconsistencies and prepare it for analysis.

Technologies Used

Apache Spark (PySpark) – large-scale data processing

Python – data manipulation and analysis

Pandas / NumPy – data preprocessing

Matplotlib / Seaborn – visualization

Jupyter Notebook – experiment environment

Project Workflow
1. Data Cleaning

Initial preprocessing included:

Removing missing and inconsistent values

Standardizing column formats

Preparing the dataset for Spark processing

2. Spark Environment Setup

A Spark session was initialized to enable distributed processing of the dataset.

3. Data Transformation

Key transformations included:

Filtering relevant purchase events

Aggregating sales by product and category

Preparing structured datasets for analysis

4. Exploratory Data Analysis

The analysis focused on identifying:

Top-performing cosmetic product categories

Brand-wise sales distribution

Price distribution patterns

Customer purchasing behavior trends

5. Visualization

Data visualizations were created to highlight patterns and trends in the dataset, helping interpret the results more effectively.

Key Insights

Some insights extracted from the analysis include:

Certain cosmetic categories consistently drive higher purchase activity.

Price segmentation reveals distinct purchasing behavior patterns.

Brand-level analysis highlights which brands dominate sales within specific categories.

These insights can support inventory planning, marketing strategy, and product positioning.

Repository Structure
Cosmetics-Sales-Analysis
│
├── Cosmetics_Inc_Sales_Data_Analysis_using_Apache_Spark.ipynb
├── Data_for_Cleaning.csv
└── README.md
How to Run

Clone the repository

git clone https://github.com/your-username/your-repository.git

Install dependencies

pip install pyspark pandas numpy matplotlib seaborn

Run the notebook in Jupyter or Google Colab.

Future Improvements

Potential extensions for this project include:

Building predictive models for sales forecasting

Implementing recommendation systems for cosmetic products

Deploying the analysis pipeline using cloud-based Spark environments

Author

Ritika Bobhate
Data Analytics | Machine Learning | Distributed Data Processing
