Trader Behavior & Market Sentiment Analysis

1.Project Overview

This project analyzes the relationship between market sentiment and trader performance using historical trading data and the Fear-Greed Index.
The goal is to understand how emotions such as fear and greed influence profitability and trading behavior.

2.Tools & Technologies Used

Python

Pandas

NumPy

Matplotlib

Plotly

Google Colab

3.Dataset Information

Two datasets were used:

Historical Trading Data

Contains trade details, profit/loss, leverage, and timestamps.

Fear-Greed Index Data

Contains daily market sentiment classifications.

These datasets were merged using the date column.

4.Project Workflow

Data loading and preprocessing

Handling missing values and date conversion

Merging datasets

Exploratory Data Analysis (EDA)

Visualization and trend analysis

Insight generation

Report preparation

5. Visualizations

The following charts were created:

Average Profit by Sentiment (Bar Chart)

Trade Count by Sentiment (Horizontal Bar Chart)

Daily Profit Trend (Line Chart)

Market Sentiment Distribution (Pie Chart)

Animated Scatter Plot

All output images are stored in the outputs folder.

6.Key Insights

Extreme Greed periods show the highest average profit.

Neutral and Extreme Fear phases show lower profitability.

Trading activity is highest during Fear periods.

Higher activity does not always result in higher returns.

Market sentiment strongly influences short-term performance.


ds_abirami/
│
├── notebook_1.ipynb
├── csv_files/
│   ├── historical_data.csv
│   └── fear_greed_index.csv
    ├──    merged_data.csv
├── outputs/
│   ├── charts
│   
├── ds_report.pdf
└── README.md

7.How to Run the Project


Open notebook_1.ipynb in Google Colab


Upload the project folder to Colab


Run all cells sequentially


View generated outputs and report


8. Results
The analysis shows that positive market sentiment leads to higher profitability, while uncertain market conditions reduce trading efficiency.
This project demonstrates how sentiment indicators can be used to improve trading strategies.

9. Future Enhancements

Machine learning-based profit prediction

Risk modeling

Real-time sentiment integration

Dashboard development

## 📥 Dataset Download

Due to GitHub file size limits, the main dataset is hosted on Google Drive.
Download dataset in csv_files.

Author
Name: Abirami R
Role: Aspiring Data Analyst
Location: Chennai, India



