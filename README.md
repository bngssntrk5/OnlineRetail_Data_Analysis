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
<img width="1246" height="664" alt="Ekran görüntüsü 2026-02-17 235438" src="https://github.com/user-attachments/assets/2b965dd7-ea96-40e5-9595-ff94f0c44a15" />


<img width="1244" height="659" alt="Ekran görüntüsü 2026-02-17 235550" src="https://github.com/user-attachments/assets/beedb7de-93c2-4c03-a7dd-bf35d92446e4" />


<img width="1246" height="667" alt="Ekran görüntüsü 2026-02-17 235645" src="https://github.com/user-attachments/assets/4c2b5a1e-08fa-4686-bba7-fc892fa635af" />


<img width="1241" height="664" alt="Ekran görüntüsü 2026-02-17 235508" src="https://github.com/user-attachments/assets/37a8a4f6-2aa1-4c91-b2c9-db3c92dc292e" />


<img width="1245" height="666" alt="Ekran görüntüsü 2026-02-17 235516" src="https://github.com/user-attachments/assets/749cd285-b264-46e5-b843-a3235d508925" />
