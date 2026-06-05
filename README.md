COVID-19 Data Analysis Using Python
Project Overview

This project performs COVID-19 Data Analysis using Python. It loads a COVID-19 dataset, cleans the data, calculates important statistics, and visualizes trends using various charts and graphs.

The project helps understand:

Total confirmed cases
Total deaths
Total recovered cases
Most affected countries
Relationship between confirmed cases and deaths
Correlation among COVID-19 metrics
COVID-19 trends over time
Technologies Used
Python 3.x
Pandas
NumPy
Matplotlib
Seaborn
Required Libraries

Install the required libraries using:

pip install pandas numpy matplotlib seaborn
Dataset

The project uses:

covid_19_data.csv

Place the dataset file in the same folder as the Python script.

Example dataset columns:

ObservationDate
Country/Region
Confirmed
Deaths
Recovered
Active
Project Workflow
Step 1: Import Libraries

Imports necessary Python libraries for:

Data handling
Numerical operations
Data visualization
import pandas as pd
import numpy as np
import matplotlib.pyplot as plt
import seaborn as sns
Step 2: Load Dataset

Reads the CSV dataset into a DataFrame.

data = pd.read_csv("covid_19_data.csv")

Displays:

First 5 rows
Available columns
Step 3: Data Cleaning

Performs preprocessing tasks:

Renames columns
Selects required columns
Converts date column to datetime format
Removes missing values
Removes duplicate records
Step 4: Descriptive Statistics

Calculates:

Total Confirmed Cases
Total Deaths
Total Recovered Cases

Also generates a statistical summary using:

data.describe()
Step 5: Country Analysis

Finds the Top 10 Affected Countries based on confirmed cases.

Visualization:

Bar Chart

Output:

Top 10 Affected Countries
Step 6: Case Distribution Analysis

Calculates overall totals for:

Confirmed
Deaths
Recovered

Visualization:

Pie Chart

Output:

COVID-19 Case Distribution
Step 7: Relationship Analysis

Analyzes the relationship between:

Confirmed Cases
Deaths

Visualization:

Scatter Plot

Output:

Confirmed vs Deaths
Step 8: Correlation Analysis

Computes correlation among:

Confirmed
Deaths
Recovered
Active Cases

Visualization:

Heatmap

Output:

Correlation Heatmap
Step 9: Trend Analysis

If the Date column exists:

Groups data by date
Calculates total confirmed cases over time

Visualization:

Line Chart

Output:

COVID-19 Trend Over Time
Step 10: Conclusion

Displays:

Analysis Completed Successfully!
Visualizations Generated
Bar Chart – Top 10 Affected Countries
Pie Chart – COVID-19 Case Distribution
Scatter Plot – Confirmed vs Deaths
Heatmap – Correlation Matrix
Line Chart – COVID-19 Trend Analysis
Expected Output
First 5 rows of dataset

Columns in dataset

Cleaned Data Information

Total Confirmed Cases

Total Deaths

Total Recovered Cases

Statistical Summary

Various Graphs and Charts

Analysis Completed Successfully!
Project Structure
COVID19-Analysis/
│
├── covid_19_data.csv
├── covid_analysis.py
└── README.md
Future Enhancements
Interactive Dashboard using Streamlit
Country-wise filtering
Real-time COVID data integration
Advanced predictive analytics using Machine Learning
Export reports in PDF format
<img width="578" height="529" alt="week 7" src="https://github.com/user-attachments/assets/31470c15-6fea-4ce9-8e2a-93beaa789759" />
<img width="389" height="411" alt="week 7(1)" src="https://github.com/user-attachments/assets/f65ed0fd-b395-41a1-ac16-198347fd9e19" />
<img width="589" height="455" alt="week 7(2)" src="https://github.com/user-attachments/assets/65654d9a-67bf-4bee-8500-cc148934a6d5" />
<img width="515" height="435" alt="week7(3)" src="https://github.com/user-attachments/assets/4071f69a-2eb6-4196-8654-8213bbd79277" />
<img width="556" height="438" alt="week 7(4)" src="https://github.com/user-attachments/assets/fc0157dc-8fb6-4bf1-943c-cae3710075fd" />




