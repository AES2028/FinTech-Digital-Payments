# FinTech-Digital-Payments
Interactive Power BI dashboard analyzing digital payment transactions — from Python data cleaning to a 3-page BI solution covering growth, customer behavior, geography, and merchant reliability. Built as a data analysis diploma capstone (SIS).

FinTech Digital Payments Analysis Dashboard
End-to-end FinTech analytics project: raw transaction data cleaned with Python, modeled and visualized in Power BI to track revenue, success rates, customer engagement, and merchant reliability.
An end-to-end analytics project that turns raw digital-payment transaction data into an interactive, decision-support Power BI dashboard — covering growth, revenue, customer behavior, geography, merchant performance, and transaction reliability.
Built as the capstone project for my Data Analysis diploma at Smart Investment Solution (SIS).


📌 Project Overview
Digital payment platforms generate huge volumes of transaction data, but raw data alone doesn't tell a business story. This project shows the full journey from messy source data to a dashboard that a payments operations or leadership team could actually use to make decisions — followed by concrete recommendations, not just charts.
Core principle applied throughout:
Observation → Business Meaning → Recommended Action
Example: a high-volume payment channel with a below-average success rate is a bigger operational priority than a low-volume channel with a larger percentage failure rate — even though the second looks worse in isolation.

🔧 Workflow
Raw Data → Python Cleaning → Data Model → Date Dimension → DAX Measures → Dashboard → Business Insights
1. Data Cleaning (Python / pandas)
Removed duplicates and resolved inconsistent formats
Handled missing values across transaction, customer, and merchant fields
Standardized data types and validated business logic (e.g. valid status codes, non-negative amounts)
Scripts: Fin Tech data cleaning - Colab
2. Data Modeling (Power BI)
Star-schema model centered on a transaction fact table, connected to dimension tables for:
Customers
Accounts
Merchants
Transaction types
Locations
Date (custom date dimension for time intelligence)
3. DAX Measures
Key measures built for the model include success rate, failed rate, average processing time, month-over-month growth, and transactions-per-active-customer .
4. Dashboard (3 pages)
Page	Focus	Key Metrics
Executive Performance Overview	Growth & revenue	Total Transactions, Successful Value, Success Rate %, Provider Fee Revenue, Active Customers, MoM Growth
Customer & Geographic Performance	Customer behavior & geography	Transactions per Active Customer, Segment Value, Engagement/Frequency, Acquisition Channel, Geographic Distribution
Merchant & Transaction Reliability	Operational reliability	Active Merchants, Failed Transactions, Failed Rate %, Avg Processing Time, Channel Reliability, Failure Trends
📂 Repository Structure
├── data/           # Sample/masked raw data (or a note on data source, if data is private)
├── scripts/        # Python cleaning & validation scripts
├── powerbi/        # .pbix file
├── screenshots/    # Exported PNGs of each dashboard page
├── docs/           # Data model notes, DAX measure list
└── README.md

🛠️ Tools & Skills
Python (pandas) · Power BI · Power Query · DAX · Data Modeling · KPI Design · Dashboard UX · Business Storytelling


📬 Contact
Feel free to connect or reach out with feedback — always open to discussing data modeling, DAX, or dashboard design decisions.
