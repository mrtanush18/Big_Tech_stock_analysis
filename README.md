# Stock Market Dashboard with Tableau & Pandas
An end-to-end data visualization project that transforms raw stock market data into an interactive Tableau dashboard. This project uses real historical data from NASDAQ to showcase insights for six major tech companies.

## Dataset
Source: Public NASDAQ Stock Dataset (Link : https://www.youtube.com/redirect?event=video_description&redir_token=QUFFLUhqbEp4ZEJWWEo2dlduX3V6NHdmU0Z2aGdfeUNpd3xBQ3Jtc0ttbkVhdmQwcXFSWVgwQ2FUR0tvN1hFTWtBSmRIeEQ1aHZ0MUZIYl9MRTgtWWo4YTNMaklqYUU2QjQtZFlZMWhXaHlmVUlWVUJ3a1pZVW1wWC12cnhXTGpueWZBVmxndl9OVWJJam9RdjNBcGMwQzdKbw&q=https%3A%2F%2Fwww.kaggle.com%2Fdatasets%2Fjacksoncrow%2Fstock-market-dataset&v=_RT32my9PRQ)

Contains historical prices for 6,000+ companies

Used subset for: Apple, Facebook, Google, Nvidia, Tesla, Twitter

Fields: Date, Open, High, Low, Close, Adjusted Close, Volume

## Features Engineered (via Pandas)
Moving Averages (MA50, MA200)

Percent Change in Price & Volume

Daily Change in Price & Volume

Previous Day Price & Volume columns

## Tableau Dashboard Highlights
Link : https://public.tableau.com/views/Stocks_17134694464150/Dashboard1?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link

Multi-line chart: Trading Volume Over Time

Histogram: Price Percent Change

KPI Tables: Latest Stock Performance

Filters: Dynamic date ranges, company selection

Additional Features: Custom logos, clean layout, formatted views

(Insert a screenshot of the dashboard)

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

Recreate or customize the dashboard using the .twbx file provided (if included)
