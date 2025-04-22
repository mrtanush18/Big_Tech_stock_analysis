# Stock Market Dashboard with Tableau & Pandas
An end-to-end data visualization project that transforms raw stock market data into an interactive Tableau dashboard. This project uses real historical data from NASDAQ to showcase insights for six major tech companies.

## Dataset
Source: [NASDAQ Stock Dataset](https://www.kaggle.com/datasets/jacksoncrow/stock-market-dataset)

Contains historical prices for 6,000+ companies

Used subset for: Apple, Facebook, Google, Nvidia, Tesla, Twitter

Fields: Date, Open, High, Low, Close, Adjusted Close, Volume

## Features Engineered (via Pandas)
Moving Averages (MA50, MA200)

Percent Change in Price & Volume

Daily Change in Price & Volume

Previous Day Price & Volume columns

## Tableau Dashboard Highlights

Multi-line chart: Trading Volume Over Time

Histogram: Price Percent Change

KPI Tables: Latest Stock Performance

Filters: Dynamic date ranges, company selection

Additional Features: Custom logos, clean layout, formatted views

![image](https://github.com/user-attachments/assets/f9e410a4-1aca-496a-b220-bb3bb04163d9)

## Tools Used
Python: Data preprocessing with Pandas

Jupyter Notebook: EDA and feature engineering

Tableau: Interactive visualizations and dashboard

## How to Run
Clone the repo
git clone https://github.com/your-username/stock-dashboard.git

Install Python dependencies
pip install pandas

Run pandas_processing.ipynb to generate cleaned CSVs

Open Tableau and import the CSV files

Recreate or customize the dashboard which can be downloaded using the [link](https://public.tableau.com/views/Stocks_17134694464150/Dashboard1?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)
