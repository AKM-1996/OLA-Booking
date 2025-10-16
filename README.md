# 🚖 OLA Ride Analytics Dashboard (July 2024)

This repository presents a comprehensive Power BI dashboard analyzing ride-hailing data from OLA for the month of July 2024. The dashboard is segmented into five key analytical views: Overall Performance, Vehicle Type Analysis, Revenue Insights, Cancellation Breakdown, and Ratings Overview. It demonstrates advanced data modeling, visualization, and storytelling techniques tailored for operational and strategic decision-making.

# 📊 Dashboard Sections & Insights

# 1. Overall Performance
- Total Bookings: 103,024 rides generating ₹35M in value.
- Booking Status Breakdown: Completed vs. Cancelled (by customer, driver, or driver not found).
- Daily Ride Volume: Stable ride activity between 2,000–2,400 rides/day.
- Key Insight: High completion rate with consistent daily volume indicates operational stability.

# 2. Vehicle Type Analysis
| Vehicle Type | Success Rate (%) | Avg. Distance (km) | Total Distance (km) |
|--------------|------------------|--------------------|----------------------|
| Prime Sedan  | 62.8             | 25.01              | 235K                 |
| Prime SUV    | 57.7             | 24.8               | 224K                 |
| Prime Plus   | 57.0             | 25.01              | 202K                 |
| Mini         | 62.4             | 25.01              | 226K                 |
| Moto         | 62.4             | 10.04              | 92K                  |
| Auto         | 61.4             | 10.01              | 89K                  |
| E-Bike       | 61.8             | 25.12              | 231K                 |
| E-Rikshaw    | 61.8             | 25.12              | 231K                 |

-Key Insight: Prime Sedan and Mini lead in success rate and distance efficiency. Moto and Auto serve shorter trips with moderate success.

# 3. Revenue Insights
- Payment Methods:
  - Cash: ₹20M
  - UPI: ₹18M
  - Credit Card: ₹10M
  - Debit Card: ₹5M
- Top Customers: Top 5 contributed ₹32,948 in booking value.
- Daily Rides: ~20K rides/day (note: may reflect total ride requests vs. completed rides).
- Key Insight: Cash and UPI dominate payment preferences. High-frequency customers offer potential for loyalty programs.

# 4. Cancellation Breakdown
- Cancellation Rate: 28.08% (out of 103,024 bookings).
- No Car Found: 39,057 cases.
- Customer Cancellations: Long ETA (9.96%), High Fare (8.57%), Wrong Address (7.19%)
- Driver Cancellations: Customer Not Reachable (8.71%), Long Distance (7.98%), High Fare (7.02%)
- Key Insight: Long ETA and fare sensitivity are major cancellation drivers. Address accuracy and communication gaps need attention.

# 5. Ratings Overview
| Vehicle Type | Driver Rating | Customer Rating |
|--------------|---------------|-----------------|
| Prime Sedan  | 3.99          | 4.00            |
| Prime SUV    | 4.01          | 4.01            |
| Prime Plus   | 4.00          | 4.01            |
| Mini         | 3.99          | 4.00            |
| Auto         | 4.00          | 3.99            |
| Bike         | 3.98          | 3.98            |
| E-Bike       | 3.99          | 3.99            |

- Key Insight: Ratings are consistently high across vehicle types, with Prime SUV slightly leading in both driver and customer satisfaction.

# 🛠️ Tools & Techniques Used
- Power BI: Advanced DAX, dynamic filtering, custom visuals
- Data Cleaning: Handling missing values, duplicates, and feature engineering
- Dashboard Design: KPI cards, pie charts, bar graphs, line charts, and tabular summaries
- Documentation: Clear labeling, intuitive navigation, and contextual storytelling

# Useful Links
- Screenshot : (https://github.com/AKM-1996/OLA-Booking/blob/main/Screenshot%202025-10-14%20201400.png),(https://github.com/AKM-1996/OLA-Booking/blob/main/Screenshot%202025-10-14%20201412.png),(https://github.com/AKM-1996/OLA-Booking/blob/main/Screenshot%202025-10-14%20201430.png),(https://github.com/AKM-1996/OLA-Booking/blob/main/Screenshot%202025-10-14%20201441.png),(https://github.com/AKM-1996/OLA-Booking/blob/main/Screenshot%202025-10-14%20201453.png)
- Google sheet data :https://docs.google.com/spreadsheets/d/11iU-e0C8Geejp6H4hVNqkv5eecG95dKgksg3AUQcQAs/edit?gid=0#gid=0
