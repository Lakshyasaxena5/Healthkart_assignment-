# Healthkart_assignment

The HealthKart Influencer Dashboard is a Streamlit-based application designed for campaign managers to simulate and analyze influencer marketing campaigns across HealthKart competitors. It 
visualizes key performance metrics such as Revenue, ROAS (Return on Ad Spend), influencer impact, and brand-level insights through interactive charts and tables along with timeline set up.

Features

Dynamic filters by platform, product, brand, date range, and category

Key metrics displayed: Total Revenue, Total Payout and ROAS

Visualizations including bar charts, line charts, and a product share pie chart

Influencer performance ranking tables

You get upload functionality to preview external influencer dataset (CSV input)

Setup Instructions
1. Install Dependencies
pip install streamlit and other relevant libraries
2. Run the Dashboard
streamlit run healthkart_dashboard6.py 
3. Access the Dashboard
Open your browser and visit: http://localhost:8501

Assumptions and Notes

Data Simulation

1. Influencer posts, tracking, and payouts are randomly generated using numpy and pandas.

2. Included brands: MuscleBlaze, HKVitals, Gritzo, TrueBasics, MBFoods, HealthViva.

3. Revenue per order ranges randomly between ₹250 to ₹3500.

4. Payouts are assigned at random either per-post or per-order basis.

ROAS Calculation

1. ROAS = Total Revenue ÷ Total Payout

Date Filtering

1. Data is simulated within the range: January 2023 to January 2024.

2. Sidebar controls allow for custom date filtering.

File Upload

1. Currently supports previewing external CSV influencer data only.

2. Uploaded data is not merged with internal simulated data yet.

Troubleshooting / FAQ

1. Ensure Python 3.7+ is installed.

2. If streamlit command is not found, verify your environment or reinstall Streamlit.

3. Use a virtual environment (venv, conda) to isolate dependencies.

4. If filtering returns no results, check the selected dates and filters carefully.


