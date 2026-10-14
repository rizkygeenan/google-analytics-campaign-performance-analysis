# 📈 Campaign Performance & User Behavior Analysis using Google Analytics

![Google Analytics](https://img.shields.io/badge/Google_Analytics-GA4-orange.svg)
![Data Analysis](https://img.shields.io/badge/Role-Data_Analyst-blue.svg)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen.svg)

## 📌 Project Overview
This project is part of the **Business Intelligence / Data Analytics Bootcamp (DABI 23)** assignment. It focuses on **Campaign Performance Analysis** using **Google Analytics (GA4)** with a demo dataset from the **Google Merchandise Store (Web Only)**. 

This analysis was conducted to evaluate digital marketing campaign effectiveness, user behavior trends (*sessions* and *user trends*), and conversion rates to provide data-driven recommendations for future marketing optimizations.

- **Analysis Period:** January 1, 2026 – January 31, 2026
- **Data Property:** Google Merchandise Store (Web Only)
- **Main Tools:** Google Analytics (Custom Reports & Explorations)

---

## 🎯 Objectives
1. Understand and identify key metrics and reports in Google Analytics.
2. Create Custom Reporting/Explorations to monitor session trends (*Session Trend*) and user trends (*User Trend*: *New vs. Returning Users*).
3. Analyze campaign performance based on *Engagement Rate*, *Bounce Rate*, and *Conversion Rate / Key Event Rate*.
4. Identify the top 2 campaigns along with an in-depth analysis.
5. Answer reflection questions (*Reflection Questions*) regarding metrics and the advantages of custom reporting.
6. Provide data-driven strategic business recommendations.

---

## 📊 Key Findings & Analysis Summary

### 1. Custom Reporting: Session & User Trends
- **Session Trend:** Website traffic experienced a weekly pattern (*weekday peak*), where visits were higher on weekdays (Tuesday–Thursday) and dropped significantly on weekends. A sharp spike occurred in the middle of the month (~Jan 22–23), reaching ~5,000–6,000 sessions due to a special promotion.
- **User Trend:** *New Users* dominated total visits. This indicates that the acquisition strategy ran effectively, but retention (*Returning Users*) remained relatively low.

---

### 2. Campaign Performance Analysis
*Elimination criteria: Campaigns with fewer than 10 sessions were excluded to maintain analytical accuracy.*

- **Top Engagement Rate:** Campaigns with the highest user engagement were dominated by `Shopping Free Listings` (100.0%) and `[Evergreen] Merch Store US and CA | Performance Max` (99.7%).
- **Top Bounce Rate:** The highest bounce rates were found in the `(not set)` channel (5.8%), `(organic)` (2.0%), and `Nov2024_HolidayGifts_V1` (1.1%).
- **Top Conversion Rate & Revenue:** The highest revenue generation was driven by `(organic)` ($31,546.16), `(referral)` ($9,243.15), `Oct2025_Fall_V1` ($8,211.74), and `[Evergreen] Merch Store US and CA | Search` ($5,055.19).

---

### 🏆 Top 2 Best Performing Campaigns

1. **[Evergreen] Merch Store US and CA | Search**
   * **Sessions:** 1,542 | **Engagement Rate:** 99.1% | **Bounce Rate:** 0.9%
   * **Total Buyers:** 58 | **Total Revenue:** $5,055.19
   * **Justification:** The primary revenue driver (*revenue leader*) in the paid campaign category. Users entering through this channel exhibited high purchase intent.

2. **[Evergreen] Merch Store US and CA | Performance Max**
   * **Sessions:** 322 | **Engagement Rate:** 99.7% | **Bounce Rate:** 0.3%
   * **Total Buyers:** 20 | **Total Revenue:** $1,373.82
   * **Justification:** Showed very high traffic efficiency with an almost perfect engagement rate, indicating highly relevant audience targeting.

---

## 🧠 Reflection Questions Summary

1. **Why is Custom Reporting necessary compared to Standard Reports?**
   * *Standard Reports* are generic (*out-of-the-box*) and heavily aggregated, which often hides specific details or audience segments.
   * *Custom Reporting* allows analysts to combine custom dimensions and metrics to address specific business needs, such as tracking custom KPIs, performing deep-dive segmentation, and finding friction points in the conversion funnel.

2. **How do different metrics affect campaign evaluation, and why doesn't high engagement guarantee good conversion?**
   * *Engagement Rate* measures initial content interest, *Bounce Rate* indicates whether there is an expectation mismatch between the ad and the landing page, while *Conversion Rate* serves as the core metric for business success/ROI.
   * Campaigns with high engagement may not convert well due to several factors:
     * **Intent Mismatch:** Audiens are attracted by informative or entertaining content but are not yet ready to buy.
     * **UX/CTA Obstacles:** Complex checkout flows or unclear call-to-action buttons.
     * **Lack of Urgency:** Absence of limited-time offers or promotions that encourage immediate purchase actions.

---

## 💡 Strategic Business Recommendations

1. **Re-allocate Marketing Budget (*Scale Up Budget*):** Increase budget allocation toward the `Search` and `Performance Max` campaigns, as they provenly bring in high-intent audiences with substantial conversion values.
2. **Landing Page Optimization & Mismatch Check:** Re-evaluate landing pages for campaigns with high bounce rates to ensure ad messaging remains consistent with page content.
3. **Retention & Remarketing Strategy:** Since *New Users* acquisition is dominant, implement email remarketing or retargeting ads targeting first-time visitors from the mid-month spike period to drive repeat transactions.
4. **Optimal Launch Timing:** Launch promotions or broadcast campaigns mid-week (Wednesday/Thursday) to match user traffic peak behavior (*weekdays peak*).

---

## 📂 Deliverables & Repository Structure

```text
├── reports/
│   └── Campaign_Performance_Analysis_Report.pdf  # Final PDF Report File Submitted to LMS
├── assets/
│   ├── session_trend_custom_report.png          # Session Trend Visualization
│   ├── user_trend_custom_report.png             # User Trend Visualization (New vs Returning)
│   └── campaign_performance_table.png           # Campaign Performance Table Visualization
└── README.md                                     # Documentation / Portfolio Summary
