E-Commerce Strategic Analytics & Customer Segmentation
This project delivers a comprehensive end-to-end data analytics solution, transforming raw transactional data into actionable business intelligence. It focuses on identifying high-value customer behaviors and optimizing regional sales strategies through advanced data cleaning and RFM modeling.

Key Insights & Descriptive Analysis
1. Sales Trends & Seasonality
Temporal Peaks: Time-series analysis identified significant seasonal surges during November and December, likely driven by year-end promotional activities.

Operational Intensity: Weekly distribution analysis revealed that 89.7% of sales occur during weekdays, providing a data-driven foundation for optimizing logistics and staffing schedules.

2. Geographical Market Analysis
Market Concentration: The United Kingdom dominates the portfolio, accounting for 83.1% of total revenue.

AOV Disparity: Despite the UK's high transaction volume (33,517 orders), international markets show a significantly higher Average Order Value (AOV), suggesting a high-tier customer base in regions like the Netherlands and Australia.

3. Behavioral Customer Segmentation (RFM)
Granular Profiling: Processed 779,325 rows to distill 5,873 unique customer profiles based on Recency, Frequency, and Monetary scores.

Strategic Segmentation: Implemented Regex-based mapping to classify customers into 10 segments. Identified 837 "Champions" as the primary loyalty drivers and 1,518 "Hibernating" users as key targets for re-engagement.

4. Pareto (80/20) Optimization
Revenue Drivers: Analysis confirmed that the top 20% of customers and products generate approximately 80% of the total revenue, allowing for highly targeted resource allocation.

Tech Stack & Advanced Data Handling
Languages & Libraries: Python (Pandas, Matplotlib, PyODBC).

Database: SQL Server (BAYS_Invoices_Clean).

Data Integrity & Correction:

Identified and resolved a critical data scaling issue where pricing was ingested at 100x its actual value (e.g., 595 instead of 5.95).

Implemented a custom DAX logic (/ 100) to normalize the Total Revenue to 17M and correct the Average Basket Size from an inflated 47K to a realistic 466.

sign: Developed a high-fidelity "Mission Control" dashboard in Power BI featuring custom diagonal gradient backgrounds and neon-accented KPIs for enhanced visual hierarchy.


UI/UX De<img width="993" height="708" alt="Overview" src="https://github.com/user-attachments/assets/cabcd9ae-9672-4e81-b189-c3df08b513b3" />


<img width="995" height="709" alt="CustomerInsight" src="https://github.com/user-attachments/assets/dbc9bfc5-9aab-427d-80b1-61664889551c" />


<img width="995" height="709" alt="ProductPerformance" src="https://github.com/user-attachments/assets/54eac353-cb00-463f-93e2-08f634ca2f3a" />


<img width="996" height="710" alt="TimeBasedAnalysis" src="https://github.com/user-attachments/assets/03d2bc2b-82ab-46c5-9058-e276e6be6db0" />
