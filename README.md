# 👋 Hi, I'm Raviteja Siliveru

📊 Data Analyst | SQL Engineer (1.4 Years Experience)  
📍 India  
📧 ravitejasiliveru480@gmail.com  
🔗 LinkedIn: https://www.linkedin.com/in/raviteja-siliveru-ab8224400/

---

## 💼 Professional Experience

**SQL Engineer (Vendor – Google Project)**  
**Movate**  
📅 Jan 2025 – May 2026  

- Supported large-scale production data pipelines handling high-volume transactional data  
- Monitored 20+ daily batch jobs to ensure successful data processing  
- Performed Start-of-Day (SOD) checks for time-sensitive reporting  
- Resolved 10–15 weekly incidents using internal ticketing systems (GUTS)  
- Conducted Root Cause Analysis (RCA) to reduce recurring pipeline failures  
- Improved data accuracy to **99%+** through SQL-based fixes  
- Optimized query performance by **~30%** using execution plans and indexing  
- Collaborated with cross-functional teams to support reporting and analytics  

---

## 🛠️ Skills

- **Languages & Tools:** SQL, Python (Pandas, NumPy), Power BI, Excel  
- **Core Skills:** Data Analysis, Data Visualization, Data Modeling, DAX  
- **Concepts:** Query Optimization, Data Pipelines, RCA, ETL, Statistics  

---

# 📊 Projects

---

🇧🇷 Olist E-Commerce Business Intelligence Ecosystem
SQL Engineering | Star Schema Modeling | Power BI Visualization

📌 Executive Summary
This project transforms 100K+ raw Brazilian e-commerce transactions into a strategic decision-making tool. By transitioning raw, siloed data into a high-performance Star Schema, I identified a R$13.59M revenue footprint and pinpointed critical retention gaps in the customer lifecycle.

🏗️ Data Engineering & Architecture
As a SQL-focused analyst, my priority was ensuring Data Integrity and Model Performance before visualization.

**1. The Schema Strategy**
I decomposed the flat-file structure into a Star Schema to optimize DAX query speed and report responsiveness.

Fact Table: order_items (113K+ records).

Dimension Tables: 8 tables including customers, products, sellers, and geography.

Relationships: 1:N (One-to-Many) using a single-direction filter flow to prevent ambiguity and circular dependencies.

**2. ETL & Data Refinement**
Data Cleaning: Handled 2,000+ null values in delivery timestamps using conditional logic to prevent skewed lead-time metrics.

Localization: Built a mapping layer to translate product categories from Portuguese to English, ensuring accessibility for global stakeholders.

Date Intelligence: Engineered a custom Dim_Date table using DAX to support Year-over-Year (YoY) and Month-over-Month (MoM) growth analysis.

**📊 The Strategic Dashboard**
The final report consists of 4 interactive layers designed for multi-level stakeholders:

Executive Overview: High-level KPIs (Revenue, AOV, Order Volume) for C-suite visibility.

Customer Intelligence: Deep dive into geography and purchasing behavior to assist Marketing.

Product & Sellers: Performance ranking by category and seller reliability for Procurement.

Operations: Logistics tracking and delivery SLA performance for Supply Chain teams.

**📈 Key Performance Indicators (KPIs)**
💰 Total Revenue: R$ 13.59 Million (Total Gross Merchandise Value)

📦 Total Orders: 99,441 (High volume requiring automated logistics)

👥 Unique Customers: 15,100 (Target base for future marketing)

🧾 Avg. Order Value (AOV): R$ 137.75 (Critical for setting discount thresholds)

⭐ Avg. Customer Rating: 4.1 / 5.0 (Healthy sentiment with room for growth)

**🔍 Deep-Dive Insights**
Seasonality: Identified a massive Black Friday spike in Nov 2017, accounting for 15% of annual revenue.

The Retention Gap: Discovered that 96% of customers are one-time buyers. Opportunity: Re-engagement campaigns are needed.

Geographic Concentration: São Paulo (SP) is the powerhouse, contributing over 40% of total revenue.

Operational Bottleneck: Delivery success is 97%, but specific regions in the North showed a 12-day higher lead time than the national average.

**💡 Business Recommendations**
Retention: Suggested a "Second-Purchase Discount" trigger for the Health & Beauty category (top performer).

Logistics: Proposed a secondary warehouse hub near high-delay regions to reduce shipping latency.

Marketing: Data proves that marketing spend should be focused on the Watches & Gifts category during Q4 due to high AOV.

**🛠️ Tech Stack Used**
Database: SQL (Data Profiling & Validation)

BI Tool: Power BI Desktop

Modeling: DAX (Measures & Calculated Columns)

Transformation: Power Query (M Language)

## 📸 Dashboard Preview

### Executive Overview
<p align="center">
  <img src="https://raw.githubusercontent.com/Raviteja847-siliveru/olist-ecommerce-dashboard/main/executive_dashboard.png" width="800"/>
</p>

### Customer Intelligence
<p align="center">
  <img src="https://raw.githubusercontent.com/Raviteja847-siliveru/olist-ecommerce-dashboard/main/customer_dashboard.png" width="800"/>
</p>

### Product & Sellers
<p align="center">
  <img src="https://raw.githubusercontent.com/Raviteja847-siliveru/olist-ecommerce-dashboard/main/product_dashboard.png" width="800"/>
</p>

### Operations
<p align="center">
  <img src="https://raw.githubusercontent.com/Raviteja847-siliveru/olist-ecommerce-dashboard/main/operations_dashboard.png" width="800"/>
</p>


🎬 Netflix Global Strategy: Data-Driven Content Intelligence
SQL Engineering | Metadata Normalization | Power BI Strategic Analytics

📌 Executive Summary
This project transforms a raw catalog of ~8.8K Netflix titles into a strategic analytical tool. By re-engineering messy, semi-structured metadata into a high-performance Star Schema, I identified the core drivers of Netflix's global expansion (post-2015) and localized content strategies that prioritize Mature (TV-MA) International Dramas.

🏗️ Project Architecture & Engineering
As a Senior Analyst, I prioritized Data Integrity and Scalability over simple visualization.

1. The Normalization Challenge (SQL)
Raw Netflix data often stores multiple values (actors, genres) in a single string. To enable granular analysis, I moved the data to First Normal Form (1NF).

The Problem: Comma-separated values prevent accurate "Top Genre" or "Actor Performance" tracking.

The Solution: Implemented CROSS APPLY and STRING_SPLIT to unnest 500+ unique genre combinations.

Impact: Increased data granularity by 115%, allowing for precise category-level reporting.

Engineering Script: View SQL Normalization Logic

2. Data Modeling (Power BI)
I built a robust Star Schema to minimize redundancy and maximize query performance.

Fact Table: Fact_Titles (Normalized and cleaned content library).

Dimension Tables: Dim_Date, Dim_Genre, Dim_Geography, Dim_Ratings.

Logic: Established 1:N single-directional relationships to prevent filter ambiguity.

📈 High-Level KPIs
🎬 Total Catalog: ~8.8K Titles — A snapshot of the global library across 749 unique countries.

🌍 Global Reach: 749 Countries — Representing a highly diverse and localized content ecosystem.

🎭 Genre Diversity: 515 Unique Genres — Granular categories identified via SQL-based string-splitting.

📊 Core Demographic: TV-MA / TV-14 — Data confirms a primary focus on adult and teen demographics.

📈 Growth Pivot: 2015 — The specific year marking the shift to an aggressive global expansion phase.

🔍 Strategic Insights
The Global Pivot: Data visualizes a massive content volume surge in 2015, correlating with Netflix’s strategic decision to move from a US-centric model to a Global-First production engine.

International Dominance: Drama & International genres are the highest-volume categories, proving that localized storytelling is Netflix's most scalable competitive advantage.

Audience Maturity: The heavy concentration of TV-MA (Mature) content indicates that Netflix’s core value proposition is high-quality, serialized adult storytelling rather than traditional "linear" family broadcasting.

💡 Business Recommendations
Retention Strategy: Increase licensing for "Family/Kids" content in emerging markets to reduce churn in multi-user household accounts.

Market Expansion: Reallocate production budget to "International Action" in the Asia-Pacific region, which shows the highest ROI for cross-border viewership.

Operational Efficiency: Standardize metadata entry at the source to reduce the 20% "Unknown" country/director rate currently found in legacy library data.

🛠️ Technical Stack
SQL Engine: Advanced String Manipulation & Normalization (CTEs, CROSS APPLY).

Power BI: Star Schema Modeling & DAX Time-Intelligence.

Power Query: M-Language for complex ETL and automated data cleaning.

📂 Repository Structure
Plaintext
├── data/
│   ├── raw_netflix_data.csv        # Original Kaggle Dataset
│   └── cleaned_netflix_data.csv    # Post-SQL Transformation
├── scripts/
│   └── netflix_data_cleaning.sql   # SQL Normalization Logic
├── dashboard/
│   └── Netflix_Report.pbix         # Interactive Power BI File
├── images/
│   └── dashboard_preview.png       # High-res Dashboard Screenshot
└── README.md
🚀 How to Replicate this Project
Database: Run the netflix_data_cleaning.sql script in your SQL environment to clean the raw CSV and unnest multi-value columns.

Analysis: Open the Netflix_Report.pbix in Power BI Desktop.

Data Source: If prompted, update the data source path to point to the cleaned_netflix_data.csv in your local /data folder.

📸 Dashboard Preview


Portfolio: Link to your main GitHub Profile
## 📬 Let's Connect!

🔗 LinkedIn: https://www.linkedin.com/in/raviteja-siliveru-ab8224400/  
📧 Email: ravitejasiliveru480@gmail.com  

---
