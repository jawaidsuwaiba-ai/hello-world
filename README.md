# hello-world
My first GitHub project
[ClosedWonRevenueAnalysis.xlsx] (ClosedWonRevenueAnalysis.xlsx)
# Closed-Won Revenue Analysis by Lead Source

## Project Overview
This project analyzes **closed-won opportunities** by lead source and company size to identify which marketing channels drive the most revenue across Enterprise, Mid-Market, and SMB segments.

## Business Problem
Which lead sources generate the highest revenue for different company segments, and how should marketing prioritize channels accordingly?

## Methodology
- Filtered opportunities to include **Closed-Won deals only**
- Linked **Leads** and **Opportunities** using `lead_id`
- Built pivot tables to calculate:
  - Total deal value
  - Average deal value
  - Percentage contribution by lead source
- Segmented results by **company size** (Enterprise, Mid-Market, SMB)

## Key Insights
- **Event-driven leads generate 44% of total Enterprise revenue**, making Events the highest-impact channel for Enterprise accounts.
- **Website leads perform strongest for SMB**, indicating inbound digital channels are more effective for smaller customers.
- **Paid Ads and Referrals each contribute approximately 25% of total revenue**, showing balanced but secondary impact compared to Events.
- **Average deal value is highest for Event-sourced opportunities**, confirming Events outperform not only in volume but also in deal size.

## Recommendation
Marketing efforts should be **segmented by company size**:
- Prioritize **Events for Enterprise accounts** due to higher revenue contribution and larger deal sizes.
- Continue **Website-led acquisition for SMB** to maximize inbound efficiency.
- Re-evaluate **Paid Ads ROI**, particularly for Mid-Market, and refine targeting or budget allocation.

## Files
- `ClosedWonRevenueAnalysis.xlsx` – Excel workbook containing raw data, pivot tables, and dashboard
- `dashboard_screenshot.png` – Snapshot of the final Excel dashboard

<img width="1794" height="594" alt="Screenshot 2025-12-22 031956" src="https://github.com/user-attachments/assets/cde68094-a97e-40b6-8752-2d99db6b6944" />
