Strategic E-Commerce Analysis: End-to-End RFM & CLTV Prediction
This project delivers a comprehensive data science solution that transforms raw transactional data into actionable business intelligence. It focuses on identifying high-value customer behaviors and optimizing regional sales strategies through advanced data cleaning, RFM (Recency, Frequency, Monetary) modeling, and Machine Learning-based CLTV forecasting.

Tech Stack
Languages: Python (Pandas, Matplotlib, Seaborn, Lifetimes)

Database: SQL Server (T-SQL, PyODBC)

Machine Learning: BG/NBD & Gamma-Gamma Models (CLTV Forecasting)

BI & Visualization: Power BI (Advanced DAX, Custom UI Design)

Key Findings & Analytical Insights
1. Data Integrity & Scaling Correction
The Challenge: Identified a critical data scaling issue where pricing was recorded at 100x its actual value (e.g., 595 instead of 5.95).

The Solution: Implemented custom Python & DAX logic (/ 100) to normalize Total Revenue to 17M TL and correct the Average Basket Size from an inflated 47k TL to a realistic 466 TL.

2. Behavioral Segmentation (RFM)
Processed 779,325 rows to derive 5,873 unique customer profiles. Used Regex-based mapping to categorize users into 10 strategic segments:

Champions (837): High-frequency, high-spending loyalists; the core of the brand.

Hibernating (1,518): Key targets for re-engagement campaigns to prevent permanent churn.

Pareto (80/20) Optimization: Confirmed that the top 20% of customers and products drive approximately 80% of total revenue.

3. Predictive Modeling: CLTV Estimation
Beyond historical data, I applied probabilistic models to predict future customer value:

BG/NBD Model: Predicted expected transaction frequencies and churn probabilities.

Gamma-Gamma Model: Estimated the average monetary value per transaction.

Business Impact: These models allow for 3-month and 6-month revenue projections, enabling highly targeted marketing budget allocation.

4. Market & Operational Intelligence
Market Concentration: The UK dominates the portfolio with 83.1% of total revenue.

AOV Discrepancy: Despite high volume in the UK, international markets (Netherlands, Australia) show significantly higher Average Order Values (AOV), indicating a premium customer base in those regions.

Operational Peak: 89.7% of sales occur on weekdays, providing a data-driven foundation for logistics and staff scheduling.

Power BI "Mission Control" Dashboard
Developed a high-fidelity dashboard featuring:

Neon-Accented KPIs: Real-time tracking of revenue, AOV, and active customer counts.

Visual Hierarchy: Custom cross-gradient backgrounds and dynamic filtering to drill down into specific customer segments or geographic regions.
<img width="1459" height="775" alt="Ekran görüntüsü 2026-02-22 130357" src="https://github.com/user-attachments/assets/1bede83a-fe41-49fe-ad62-b3419e7749bd" />


<img width="1457" height="780" alt="Ekran görüntüsü 2026-02-22 130423" src="https://github.com/user-attachments/assets/107a92f9-3fa8-4834-95fd-c53f9b74aa44" />

<img width="1457" height="777" alt="Ekran görüntüsü 2026-02-22 130450" src="https://github.com/user-attachments/assets/dc7faea0-1d7b-42dc-b9a9-68cfad3de147" />

<img width="1457" height="775" alt="Ekran görüntüsü 2026-02-22 130509" src="https://github.com/user-attachments/assets/65792b97-f7ed-40b7-a6f2-807aff69eb96" />

<img width="1455" height="775" alt="Ekran görüntüsü 2026-02-22 130527" src="https://github.com/user-attachments/assets/c0389cb6-547a-43dd-bf73-3ff666b3422d" />

<img width="1456" height="776" alt="Ekran görüntüsü 2026-02-22 130543" src="https://github.com/user-attachments/assets/988a7208-02c2-4093-a17a-8b075d2aa20d" />
