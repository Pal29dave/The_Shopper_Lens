# The_Shopper_Lens
Data Analytics Project showcasing customer behavior analysis using Python, SQL and Power Bi

 The Shopper Lens
Overview

This project showcases a full end-to-end data analytics workflow. It begins with loading and exploring a dataset in Python, followed by data cleaning, SQL-based analysis using PostgreSQL, interactive visualization using Power BI, and a final presentation summarizing key insights for stakeholders.
The goal is to demonstrate strong analytical skills, technical proficiency, and the ability to communicate data-driven insights clearly.

Dataset

File: Customer.csv 

Records: Add number of rows after checking the file
[Customer.ipynb](https://github.com/user-attachments/files/23681353/Customer.ipynb)

Features include:

Customer demographics (age, gender, income, etc.)

Transaction and spending information

Product categories and delivery types

Tools & Technologies

Python: Pandas, NumPy, Matplotlib, Seaborn

Jupyter Notebook: Data exploration & code execution

PostgreSQL: Advanced SQL analysis

Power BI: Dashboard visualization

PowerPoint: Summary presentation for stakeholders

GitHub: Version control & project hosting

Project Steps
1. Load Data in Python

Imported dataset using Pandas.

Inspected shape, data types, missing values, and initial patterns.

2. Exploratory Data Analysis (EDA)

Generated statistical summaries.

Visualized distributions and correlations.

Identified outliers, trends, and category-level patterns.

3. Data Cleaning

Handled missing values and inconsistencies.

Treated outliers and standardized formats.

Created new engineered features for deeper insights.

4. SQL Analysis in PostgreSQL

Loaded cleaned dataset into a PostgreSQL database.

Executed analytical SQL queries such as:

Aggregations

Group-by segment analysis

Customer segmentation queries

Joins and window functions where applicable

SQL results were used to validate insights and strengthen analysis.

5. Power BI Dashboard

Built an interactive BI dashboard featuring:

Demographic spending trends

High-value customer segments

Category-wise purchase insights

KPIs and summary visuals

Designed for quick and intuitive insight consumption by decision-makers.

6. Presentation

A concise PowerPoint presentation includes:

Project goals

Data preparation steps

EDA highlights

SQL findings

Dashboard explanation

Final insights and recommendations

Dashboard

The Power BI dashboard provides:

Interactive filters for age, gender, product category

Visual summaries of spending patterns

Key metrics such as average purchase, frequency, and segment contribution

Customer behavior insights through charts and cards

<img width="1463" height="931" alt="Screenshot 2025-11-20 210428" src="https://github.com/user-attachments/assets/f039a400-557d-447e-81f2-6d34da3b4748" />


Results & Key Insights

Identified spending trends based on demographic groups.

Highlighted high-value customer segments for targeted marketing.

Detected patterns across product categories and delivery preferences.

Provided actionable recommendations to improve customer engagement and sales.

How to Run the Project
1. Clone the Repository
git clone <your-repo-link>
cd <project-folder>

2. Install Dependencies
pip install -r requirements.txt

3. Run the Python Notebook

Open Customer.ipynb in Jupyter Notebook or VS Code.

4. Set Up PostgreSQL

Create a database.

Import the cleaned dataset (cleaned_customer.csv).

Run the SQL queries in sql_queries.sql.
