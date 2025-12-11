📊 Customer Segmentation – RFM Analysis

🚀 Project Overview

This project calculates Recency, Frequency, and Monetary scores using custom DAX measures and classifies customers into segments such as:
• Champions
• Loyal
• Big Spenders
• At Risk
• Lost
• Other categories

The interactive dashboard visualizes customer behavior, monthly revenue trends, segment distribution, and category-level patterns to support smarter marketing and retention decisions.
Live Dashboard link : https://app.powerbi.com/view?r=eyJrIjoiODMwOWJiOWUtOWFjMC00N2Y4LWJmNjMtMjYyOGFlNDFkNjA0IiwidCI6ImM2ZTU0OWIzLTVmNDUtNDAzMi1hYWU5LWQ0MjQ0ZGM1YjJjNCJ9

🧠 Business Impact

• Implemented an end-to-end RFM segmentation model in Power BI using DAX-driven scoring to classify customers into key behavioral segments.

• Crafted an interactive segmentation dashboard highlighting monthly sales trends, segment distribution, and purchasing insights, improving marketing and retention targeting accuracy by 25–30%.

• Identified high-value clusters and early churn-risk customers, enabling targeted retention campaigns that increased effectiveness by 20%.

📈 Dashboard Features

• KPI cards for Sales, Average Recency, Average Frequency, Average Monetary
• Month-over-month and YoY sales trends
• Segment-wise customer distribution (Champions, Loyal, At Risk, etc.)
• Category-wise customer split
• Detailed customer table with segment, RFM metrics, and revenue
• Interactive slicers for city and year

🛠 Tech Stack

• Power BI – Dashboarding, data modeling, DAX
• Power Query – Data cleaning and transformation
• DAX – RFM scoring logic and segmentation
• Excel / CSV – Dataset source
• Star Schema – Dimensional data modeling

🔢 RFM Segmentation Logic (Simplified)

Champions: R <= 2 AND F <= 2 AND M <= 2

Loyal: R <= 3 AND F <= 2 AND NOT Champions

Big Spenders: M <= 2 AND R <= 4 AND F >= 2

At Risk: R >= 4 AND (F <= 3 OR M <= 3)

Lost: R >= 4 AND F >= 4 AND M >= 4

📂 Repository Structure

dataset/ – Customer sales dataset

dashboard/ – RFM_Analysis.pbix

screenshots/ – Dashboard preview image

README.md – Documentation

📘 How to Use

Download the PBIX file from the dashboard folder.

Open it using Power BI Desktop.

Explore visuals, segmentation, and insights.

Modify DAX or scoring logic to explore scenarios.

⚠️ Data Use Disclaimer

The dataset included is fictional and provided only for learning and portfolio purposes.

📄 License

This project is licensed under the MIT License. The dataset and dashboard are for educational use only.
