🚀 Key Insights & Descriptive Analysis
1. 📅 Sales Trends & Seasonality
Weekly & Monthly Trends: Satış hacimleri zaman serisi analizi ile incelenerek mevsimsel zirveler (Kasım ve Aralık ayları) tespit edilmiştir.

Operational Intensity: Haftalık satış dağılımı incelendiğinde, operasyonel yoğunluğun en yüksek olduğu günler belirlenerek lojistik planlama için veri sağlanmıştır.

2. 🌍 Geographical Market Analysis
Market Share: Analyzed that the United Kingdom accounts for 83.1% of the total revenue, confirming its position as the primary market.

Order Volume: While the UK leads in transaction count (33,517 orders), international markets ("Other Countries") show a significantly higher Average Order Value (AOV).

Strategic Outcome: This analysis suggests that while the UK requires logistical focus, international markets hold high-value potential for targeted marketing campaigns.

3. 👥 Behavioral Customer Segmentation (RFM Analysis)
Metric Calculation: Processed 779,325 transaction rows to create 5,873 unique customer profiles based on Recency, Frequency, and Monetary values.

Strategic Categorization: Customers were classified into 10 distinct segments (e.g., Champions, Hibernating, At Risk) using quintile-based scoring and Regex mapping.

Segment Insights: Identified 837 "Champions" as the core loyalty group and 1,518 "Hibernating" customers as the primary target for re-activation campaigns.

4. 📊 Pareto (80/20) Optimization
Value Concentration: Identified that the top 20% of customers and products generate approximately 80% of total revenue.

Resource Management: This analysis enables the business to optimize resource allocation, focusing marketing and high-tier support on the most impactful customer segments.

🛠 Tech Stack & Data Handling
Languages & Libraries: Python (Pandas, Matplotlib, PyODBC).

Database: SQL Server (Data cleaning and aggregation via BAYS_Invoices_Clean table).

Data Integration: Automated the data retrieval process using Python to read from localized SQL exports (CSV).

Handling Regional Data Formats: Implemented custom data cleaning scripts to handle European decimal formats (comma vs. dot), specific delimiters (semicolon), and numeric precision rounding (Monetary rounding).
