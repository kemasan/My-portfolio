# Data Analytics Portfolio 

I am a data analyst focused on turning unclear business questions into structured analysis and actionable insights.  
This repository shows how I think and how I work with data, not only which tools I use.

---

## What I Do:

I use data to reduce uncertainty in decision-making.

My work typically includes:
- Translating vague business questions into clear analytical tasks
- Defining and validating metrics
- Exploring data quality issues
- Communicating insights in a clear and practical way

---

## Tools & Methods:

I use SQL, Python, Excel, Power BI, Tableau and Metabase to explore data, validate assumptions, and support decisions.

My analytical workflow covers:
- Data cleaning and validation  
- Metric definition and reconciliation  
- Exploratory data analysis  
- Dashboard and report design  
- Basic statistics and trend analysis  

Tools are chosen based on the problem.

---

## Projects in This Repository

Each project answers a specific business question.

I focus on:
- Why the question matters  
- How the data is structured  
- Which assumptions are made  
- What trade-offs exist  
- How conclusions change when assumptions change


### Projects:

### 📊 Retention Growth & LTV Strategy

Business Question:
Can we predict and prevent early user churn by identifying toxic friction and financial attachment thresholds?

Description & Methodology: 
Developed an EdTech retention and monetization framework by analyzing user logs tracking daily sessions, problem submission states, and virtual currency balances (CodeCoins). Using a Rolling Retention (Day N+) methodology to account for irregular learning patterns, this study mapped cohort heatmaps and user friction to identify exactly when users realize value versus when they quit. While this approach prevents underestimating long-term engagement, it trades off the ability to spot fading daily habits in favor of protecting overall user Lifetime Value (LTV).

Key Skills: 
SQL (PostgreSQL), Product Analytics, Behavioral Segmentation, Retention Modeling, Metabase Architecture.

Outcome: 
Conducted a behavioral research study validating core engagement hypotheses, constructed an interactive Metabase dashboard for retention tracking, and provided data-driven product recommendations (such as hint triggers at the 4th failure to block churn and loss-aversion mechanics based on virtual balances).

📂 Repository: [edtech-retention-ltv-strategy](https://github.com/kemasan/EdTech-Product-Analytics-Retention-Framework-Monetization-Strategy/blob/main/README.md#-retention-growth--ltv-strategy)
🔗 Dashboard: [Retention Growth Analysis](https://metabase.simulative.ru/dashboard/845-retention-growth-analysis?period_=)


### 💹 DeFi Solvency & Risk Monitoring — GMX V2 Dashboard

Business Question:
Can liquidity pools remain solvent under extreme trader profitability?

Description:
Reconstructed the financial state of GMX V2 markets using on-chain data. Built stress, solvency, and skew indicators to evaluate protocol risk under adverse market conditions.

Focuses on translating blockchain data into financial risk metrics.

Key Skills:
SQL (DuneSQL), DeFi analytics, risk modeling, on-chain data analysis

Outcome:
Produced a monitoring system for identifying liquidity stress and asymmetric risk exposure.

📂 Repository: [gmx-solvency-dashboard](https://github.com/kemasan/GMXV2-Risk-Solvency-Analysis/blob/main/README.md)                      
🔗 Dashboard: https://dune.com/kemasan/gmx-v2-risk-and-solvency-analysis                                     

--- 

### 📊 E-Commerce Inventory Analysis — ABC–XYZ Framework

Business Question:
Which products generate most revenue, and how stable is their demand over time?

Description:
Built an end-to-end analytical pipeline using transactional e-commerce data to segment products by:

Revenue importance (ABC / Pareto principle)

Demand stability (XYZ / coefficient of variation)

The project includes data cleaning, return handling, monthly aggregation, statistical validation, and interactive Tableau dashboards.

Key Skills:
SQL (DuckDB), data modeling, Pareto analysis, demand variability, Tableau dashboarding

Outcome:
Identified high-impact, low-risk SKUs (AX / AY) and high-risk revenue contributors (AZ / CX) to support inventory and procurement decisions.

📂 Repository: [ecommerce-abc-xyz-analysis](https://github.com/kemasan/ecommerce_abc_xyz)    
🔗 Interactive Dashboard: [E-Commerce Inventory Analysis — ABC–XYZ Framework](https://public.tableau.com/views/ABC_17712246527350/ABCXYZInventorySegmentationRevenueConcentrationDemandStabilityAnalysis?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)            
                        

---

### 📈 Market Anomaly Detection — Rolling Z-Score Framework

Business Question:
How can extreme price deviations be detected in volatile financial markets?

Description:
Developed a statistical monitoring system that transforms raw price data into normalized Z-scores using rolling windows. The model highlights price movements that fall outside historical probability ranges.

Includes sensitivity analysis across multiple time horizons and threshold testing.

Key Skills:
Python, time series analysis, statistical modeling, signal validation

Outcome:
Created an early-warning system for detecting abnormal market behavior and potential manipulation.

📂 Repository: [market-anomaly-detection](https://github.com/kemasan/Z-Score)




