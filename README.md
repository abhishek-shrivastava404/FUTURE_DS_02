# FUTURE_DS_02
# 📊 Social Media Campaign Performance Tracker

An end-to-end Power BI dashboard analyzing social media advertising performance using simulated campaign data.  
The project focuses on campaign health, ad-level optimization, and audience engagement insights using estimated metrics.
---
<img width="1286" height="690" alt="image" src="https://github.com/user-attachments/assets/e7b38213-a597-4310-b1d2-f98074be68e5" />
<img width="1286" height="690" alt="image" src="https://github.com/user-attachments/assets/ab4a8740-d394-4c84-95f3-3431473085c8" />
<img width="1286" height="690" alt="image" src="https://github.com/user-attachments/assets/ffbfe756-a32b-4c8c-b036-b3613d13b051" />
---

## 🔍 Overview
This dashboard evaluates how social media ad campaigns perform across platforms (Facebook & Instagram), ads, and audiences.  
It highlights performance gaps, identifies high- and low-performing ads, and provides data-backed optimization insights.

> **Note:** CTR and ROI are estimated using behavioral inference due to the absence of direct click and revenue data.
---

## 🎯 Objectives
- Assess overall campaign performance and efficiency
- Identify ads to scale or pause based on engagement
- Analyze audience response by age, gender, interests, and platform
- Support optimization decisions with clear visual insights
---

## 📐 Key Metrics
- Impressions
- Reach & Frequency
- Estimated Click-Through Rate (CTR)
- Estimated Return on Investment (ROI)
---

## 🧠 Methodology
- Built a star-schema data model using multiple CSV datasets
- Calculated engagement metrics using DAX measures
- Used **weighted CTR** for multi-valued dimensions (e.g., interests) to avoid aggregation bias
- Designed visuals to separate:
  - Executive overview
  - Ad-level performance
  - Audience insights
---

## 📊 Dashboard Pages
1. **Campaign Performance Overview**  
   High-level KPIs and CTR trends to assess overall campaign health.

2. **Ad Performance Analysis**  
   Ad-level engagement, spend vs CTR analysis, and identification of scaling or pausing opportunities.

3. **Audience Insights**  
   Engagement analysis by age group, gender, platform, and user interests.

4. **Optimization & Recommendations**  
   Actionable insights derived from observed performance patterns.
---

## 🛠 Tools & Technologies
- **Power BI** (Data modeling, DAX, visualization)
- **CSV datasets** (Ad Events, Ads, Campaigns, Users)
---

## 📌 Key Insights
- High ad frequency correlates with lower engagement, indicating ad fatigue
- Certain audience segments show higher engagement density despite low overall CTR
- Platform-wise differences suggest opportunities for better targeting alignment
- Interest-level analysis reveals small but high-performing audience pockets
---

## 👤 Author
**Abhishek Shrivastava**
