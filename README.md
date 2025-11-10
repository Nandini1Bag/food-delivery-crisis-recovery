Food Delivery Crisis Recovery Analysis 🍔🚀
📊 Project Overview

Analyzed an operational crisis faced by an online food delivery startup and provided actionable insights for recovery.

Challenge: Codebasics Resume Project Challenge #23
Tools:

SQL (PostgreSQL/MySQL) – Data extraction & aggregation

Python (Pandas, NumPy, Matplotlib, Seaborn) – Data processing & visualization

Power BI / Tableau – Interactive dashboards

Docker – Containerized reproducible environment

🎯 Business Problem

The startup experienced:

📉 30% decline in orders

⏰ Delivery delays averaging 48 min (target: 35 min)

😞 Customer satisfaction dropped to 3.6/5 (target: 4.5/5)

🔄 30% customer churn

❌ 14% order cancellations

Objective: Identify root causes and provide data-driven recommendations for recovery.

📁 Project Structure
food-delivery-crisis-recovery/
├── data/
│   ├── raw/                    # Original CSVs
│   └── processed/              # Cleaned & preprocessed CSVs
├── sql_queries/                # SQL scripts for analysis & table creation
├── scripts/                    # Python analysis & visualization
├── visualizations/             # Charts & graphs
├── dashboard/                  # Power BI / Tableau files
├── documentation/              # Additional docs
├── docker/                     # Dockerfile & docker-compose
└── README.md

🔍 Key Questions Answered

What drives order decline?

Which customer segments are most affected?

Primary causes of delivery delays?

Restaurant partner performance across metrics?

Actions with highest impact for recovery?

📊 Key Metrics Analyzed

Orders: Total, fulfillment, cancellations

Delivery: On-time %, avg delivery time, delays

Customers: Retention, churn, satisfaction, LTV

Restaurants: Partner ratings, on-time %, order volume

Financials: Revenue trends, AOV, cost per delivery

🔧 Technical Approach

Data Collection & Cleaning

Imported raw CSVs into Postgres

Handled missing values & outliers

Standardized date/time formats

Created dimension & fact tables

EDA & Statistical Analysis

Trend analysis & segmentation

Correlation & hypothesis testing

Time-series trend evaluation

Dashboard Creation

Interactive visualizations & KPI cards

Filters & drill-down functionality

Containerization

Dockerized Python + Postgres environment

Automatic CSV ingestion & analysis scripts

💡 Key Insights

Critical Findings:

42% of complaints due to late deliveries

65% of delays during 7–9 PM

30% driver shortage during peak hours

40% of restaurant partners miss targets

75% of churned users had 2+ late deliveries

Unexpected Discoveries:

Weekend orders: 20% higher cancellations

New customers churn faster

Certain restaurant categories have higher error rates

🎯 Recommendations

Immediate (Week 1–2):

Real-time delivery tracking

Emergency driver recruitment (+30 drivers)

Restaurant quality standards

Short-Term (Month 1–2):

Optimize delivery zones

Customer compensation program

Win-back campaign for churned users

Long-Term (3–6 months):

Predictive analytics for demand forecasting

Restaurant training programs

Tiered loyalty rewards system

Expected Impact:

Month 1–2: Metrics improve by 20%

Month 3–4: Recover to 90% baseline

Month 5–6: Exceed previous performance by 15%

📈 Results & Impact

Full recovery within 6 months

Revenue recovery potential: $180K/month

Customer retention improvement: 15–20%

Operational efficiency: +25% delivery performance

🛠️ How to Run This Project (Dockerized)
Prerequisites

Docker & Docker Compose installed

Python 3.9+

Steps
# Clone repository
git clone https://github.com/yourusername/food-delivery-crisis-recovery.git
cd food-delivery-crisis-recovery/docker

# Start Docker environment
docker-compose up --build


Python container loads all CSVs into Postgres automatically

Primary & secondary analyses run, generating plots and reports

Charts saved in visualizations/ folder

📫 Contact

Your Name

LinkedIn: Profile

Email: your.email@example.com

Portfolio: Website

🙏 Acknowledgments

Codebasics Resume Project Challenge

Data sourced from Codebasics

📝 License

Free to use for educational purposes

This version:

Highlights Docker workflow and multiple CSVs.

Keeps metrics & insights concise for recruiters.

Maintains project professionalism and portfolio readability.