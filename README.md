Hospitality Insights Dashboard - Power BI 

Overview

This Power BI dashboard provides key insights into the hospitality industry, focusing on revenue, occupancy, and booking trends. It enables data-driven decision-making by visualizing key performance indicators (KPIs) such as RevPAR, ADR, Occupancy Rate, and Realization Rate.

🚀 Key Features

Dynamic Filters – Analyze data by city, room class, and booking platform.

Revenue & Occupancy Analysis – Breakdown of total revenue, RevPAR, ADR, and occupancy rates.

Booking Trends – Track performance over time with trend analysis.

Platform Performance – Compare different booking platforms' impact on revenue.

Property-Wise Metrics – Analyze revenue and occupancy across multiple hotel properties.

Interactive Visuals – Real-time insights into hotel operations.

📊 Key Insights

Revenue: ₹1.69B

Revenue per Available Room (RevPAR): ₹7,337

Average Daily Rate (ADR): ₹12,696

Occupancy Rate: 57.8%

Highest Revenue-Generating City: Mumbai (₹51M)

Booking Platform Analysis: Direct Online has the highest realization %

🔍 DAX Formulas Used

1️⃣ Revenue per Available Room (RevPAR)

RevPAR = DIVIDE([Total Revenue], [Available Rooms], 0)

2️⃣ Average Daily Rate (ADR)

ADR = DIVIDE([Total Revenue], [Occupied Rooms], 0)

3️⃣ Occupancy Rate

Occupancy Rate = DIVIDE([Occupied Rooms], [Available Rooms], 0) * 100

4️⃣ Realization Rate

Realization Rate = DIVIDE([Actual Revenue], [Potential Revenue], 0) * 100

5️⃣ Total Revenue

Total Revenue = SUM(Sales[Revenue])

6️⃣ Booking Platform Realization %

Platform Realization % = DIVIDE([Total Revenue by Platform], [Potential Revenue by Platform], 0) * 100

📌 What I Did in This Project

✅ Cleaned and transformed raw booking data using Power Query
✅ Built a dynamic dashboard with DAX measures for deeper insights
✅ Created interactive filters to enhance user experience
✅ Designed KPI cards and trend analysis charts
✅ Published the report on Power BI Service


🎯 Challenges & Learnings

⚡ Managing large datasets efficiently
⚡ Optimizing DAX calculations for better performance
⚡ Extracting actionable insights to improve business decisions

📈 Visual Trends & Deep Insights

✔ Revenue Breakdown: Business (61.6%) vs. Luxury (38.4%)
✔ Weekly Trends: RevPAR, ADR, and Occupancy trends help track performance
✔ Platform Performance: Realization % and ADR comparison across booking platforms
✔ City-wise & Property-wise Metrics: Performance insights for different locations and hotels

💡 Conclusion

This project helped me enhance my Power BI, DAX, and data visualization skills. It demonstrates how raw data can be transformed into valuable business insights to optimize hotel performance.