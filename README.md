UK Train Rides Analysis Project


Project Overview
This project analyzes UK railway data to identify delay causes, understand travel behavior, and forecast demand using Python (Pandas, Seaborn) and Power BI.

Key outputs include:

Actionable insights for scheduling optimization.

Interactive dashboards for visualizing delays, ticket sales, and journey performance.

Dataset & Data Preparation
Dataset
Source: UK railway records.

Key Variables:

Ticket purchases, journey dates/times, delays, ticket types.

Columns: departure_time, arrival_time, delay_time, ticket_class, delay_reason.

Data Cleaning Steps
Handled Missing Values:

Imputed gaps in Railcard and Reason_For_Delay.

Standardization:

Renamed columns and converted strings to datetime objects.

Feature Engineering:

Derived journey_duration (planned vs. actual).

Calculated delay_time (minutes).

Key Insights & Visualizations
1. Delay Analysis
Top Delay Reasons: Signal failures (32%), weather (25%), operational issues (18%).

Peak Delay Times: Weekday rush hours (7–9 AM, 4–6 PM).

Visualizations:

Bar Charts: Delay reasons by frequency.

Heatmaps: Delays by weekday/hour.

2. Customer Behavior
Ticket Trends: First-class tickets contributed 40% of revenue.

Purchase Patterns: 65% booked 1–3 days before departure.

Visualizations:

Line Charts: Sales trends over time.

Boxplots: Delay times by ticket class.

3. Demand Forecasting
Predicted 12% increase in weekday demand.

Revenue growth driven by first-class tickets (+18% YoY).

Power BI Dashboard
Ticket Analysis Dashboard
KPIs:

Total tickets sold: 31.65K | On-time rate: 86.8%.

Visuals:

Donut Chart: Journey status (on-time/delayed/cancelled).

Bar Charts: Ticket types and payment methods.

Journey Analysis Dashboard
KPIs:

Total journeys: 20K | Delayed: 1,062 | Cancelled: 790.

Visuals:

Route Frequency Bar Chart.

Delay Reason Breakdown.

Dashboard Preview

How to Access
Power BI Dashboard:https://app.powerbi.com/links/kckAmHwR7W?ctid=dee1ed73-19ca-4ce0-8066-8261fbabbeaa&pbi_source=linkShare&bookmarkGuid=5fd618cc-5c53-4253-81cf-4a224f1de0ea


Repository Files
UK_Train_Analysis.ipynb	Python script for EDA & modeling.
train_data_cleaned.csv	Processed dataset.
Dashboard.pbix	Interactive Power BI dashboard.
Technical_Report.docx	Full analysis with conclusions.
Buisness report
Tools & Technologies
Python Libraries: Pandas, NumPy, Seaborn, Matplotlib.



Authors
Youssef Ahmed
Yomna Saad Abdelazeem
