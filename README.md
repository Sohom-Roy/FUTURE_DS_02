# 📊 Social Media Campaign Performance Tracker

This project was built as part of my **Task 2** during the **Data Science & Analytics Internship** at **Future Interns**.  
It focuses on building an interactive **Power BI dashboard** to analyze and visualize key performance metrics of simulated Facebook/Instagram ad campaigns.
DASHBOARD LINL- https://app.powerbi.com/links/KaoJY366sl?ctid=82b836bd-489b-43ee-b0cd-b1e1afc0081f&pbi_source=linkShare

---

## 🚀 Objective

To help businesses monitor and analyze:
- How well the ad campaigns performed
- Which audience segments engaged the most
- How KPIs like CTR, CPC, and Approval Rate evolved over time

---

## 🧼 Data Cleaning & Preparation

Performed in **Power Query Editor**:
- Removed nulls and irrelevant rows
- Cleaned data types and formats
- Derived new columns using custom logic

### ✅ Added KPI Columns:
| Column Name         | Formula                                      | Purpose                              |
|---------------------|----------------------------------------------|--------------------------------------|
| `CTR`               | `clicks / impressions`                       | Click-Through Rate                   |
| `CPC`               | `spent / clicks`                             | Cost Per Click                       |
| `conversion_rate`   | `total_conversion / clicks`                  | Funnel performance                   |
| `approval_rate`     | `approved_conversion / total_conversion`     | Approval efficiency                  |
| `campaign_day`      | Extracted date from `reporting_start`        | Time-based filtering                 |
| `engagement_score`  | `clicks + total_conversion + approved_conversion` | Engagement analysis              |

---

## 📈 Dashboard Overview

Built in **Power BI Desktop**, the dashboard includes:

### 🔹 Top-Level KPIs (Card Visuals):
- Total Spent
- Total Clicks
- Total Impressions
- CTR
- CPC
- Approval Rate

### 🔹 Visual Charts:
| Visualization               | Description                              |
|-----------------------------|------------------------------------------|
| Donut Chart                 | Spend by Gender                          |
| Bar Chart                   | CTR by Age Group                         |
| Area Chart                  | Daily Engagement Score                   |
| Stacked Column Chart        | Daily Interest Trends (Interest1–3)      |

### 🔹 Filters / Slicers:
- Age Range (Slider)
- Gender (Button)
- Campaign ID
- Ad ID
- Timeline Picker (Date Range)
- Interest Count Tiles

---

## 🛠️ Tools & Skills Used

- **Power BI Desktop**
- **Power Query Editor**
- **DAX (Data Analysis Expressions)**
- Data Cleaning & Transformation
- Dashboard Design & Data Storytelling

---

## 📌 Conclusion

This project delivers actionable insights to marketers and analysts, helping them optimize ad spend, understand audience behavior, and improve conversion performance — all through a visually engaging and user-friendly dashboard.

---

## 📧 Contact

**Sohom Roy**  
📩 sohomroyofficial2025@gmail.com  
🔗 [LinkedIn Profile](https://www.linkedin.com/in/sohom-roy-009588314)  


---

## ⭐ Acknowledgements

- **Future Interns** for the opportunity
- Learning from Power BI creators and communities

---

