# 📊  Uber Ride Analytics Dashboard — Power BI

<p align="center">
  <img src="https://img.shields.io/badge/PowerBI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black"/>
  <img src="https://img.shields.io/badge/DAX-F2C811?style=for-the-badge&logo=powerbi&logoColor=black"/>
  <img src="https://img.shields.io/badge/Status-Complete-brightgreen?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/Mobile%20View-Optimised-blue?style=for-the-badge"/>
</p>

<p align="center">
  An interactive Power BI dashboard built on a retail sales dataset of
  <strong>100 orders across 12 customers in 4 countries</strong> —
  tracking revenue, product performance, and category breakdowns
  using <strong>DAX calculated columns</strong>, table relationships,
  and a custom dark colour theme.
</p> 
---


## 📸 Dashboard Preview
 
Uber Dashboard 2026
<p align="center">
<img width="707" height="740" alt="image" src="https://github.com/Shobhith01/Uber-Ride-Analytics-Dashboard-Power-BI/blob/main/Uber%20Dashboard.png/Homepage.png" />
<img width="707" height="740" alt="image" src="https://github.com/Shobhith01/Uber-Ride-Analytics-Dashboard-Power-BI/blob/main/Uber%20Dashboard.png/Overview%202.png" />
<img width="707" height="740" alt="image" src="https://github.com/Shobhith01/Uber-Ride-Analytics-Dashboard-Power-BI/blob/main/Uber%20Dashboard.png/Overview%203.png" /> 
</p> 

---

### 🗂️ Project Structure

```
Uber-dashboard-powerbi/
│
├── data/
│   └── uber.xlsx          # 104k customer  — category, quantity, orders
│  
├── Uber Dashboard.pbix     # Power BI Desktop report file
├── dashboard_preview.png       # Full dashboard screenshot
│   └── homepage.png
│   └── overview.png
│   └── vehicle.png
│   └── revenue.png
│   └── customer.png
└── README.md
```
## Dashboard Pages

### 🏠 Home Page
Branded landing screen with navigation buttons to all four analytical pages.
Clean minimal layout with Uber's visual identity.

### 📊 Overview
High-level KPIs across all vehicle types:
- ₹51.8M Revenue | 149K Total Orders | 56.8K Cancelled | 2.5M km Total Distance | 24.6 Avg Distance
- Monthly & Quarterly customer count trend (area chart)
- Revenue by Payment Method — UPI dominates at ₹23M vs Debit Card at ₹4M
- Customer breakdown by payment method
- Lost Customer analysis by vehicle type

### 🚗 Vehicle
Per-vehicle-type deep dive with dynamic image switcher (Auto, Bike, Go Mini, Go Sedan, Premier Sedan, Uber XL):
- Completed / Cancelled / Incomplete ride donut rings per vehicle
- Revenue trend by vehicle type (multi-line chart — Jan to Dec)
- Summary table: Booking Value, Completed Orders, Booking Count, Avg Distance, Lost Bookings, Contribution %

| Vehicle | Booking Value | Completed | Cont% |
|---|---|---|---|
| Auto | ₹1.28Cr | 23,128 | 24.84% |
| Bike | ₹1.14Cr | 20,560 | 22.10% |
| Go Mini | ₹1.03Cr | 18,529 | 19.94% |
| Go Sedan | ₹93.7L | 16,666 | 18.07% |
| Premier Sedan | ₹62.8L | 11,247 | 12.10% |
| Uber XL | ₹15.3L | 2,783 | 2.95% |

### 💰 Revenue
- Monthly revenue trend (area chart) — peak ₹4.53M in Jan, trough ₹3.97M in Mar
- Revenue by Vehicle Type (bar chart)
- Revenue by Payment Method
- Revenue by Customer (top spenders ranked)

### 👤 Customer
- Top Pickup & Drop Points per vehicle type (e.g. Bike: Tagore Garden → Noida Extension)
- Average Customer Rating: 4.40 ⭐ | Average Driver Rating: 4.23 ⭐
- Monthly completed ride trend
- Monthly revenue trend

---

## Key DAX Measures
`Booking_Completed` · `Booking_Lost` · `Booking_Count` · `revenue` · `Booking value`  
`Total Distance` · `Avg Distance` · `Average of Customer Rating` · `Average of Driver Ratings`  
`Top Pick Up` · `Top Drop Point` · `Cont%` · `Booking_Remove_Status_Filter`

## Data Model
| Table | Role |
|---|---|
| `Uber` | Fact table — trip records |
| `_Measures` | Dedicated measures table |
| `Calender` | Date table for time intelligence |
| `Date Axis` | Dynamic axis switching |
| `Veh_IMG` | Vehicle image mapping |

## Tools
Power BI Desktop · DAX · Custom Theme · Page Navigation

---

## 👤 Author

**Shobhith S Kounder**
Aspiring Data Analyst · SQL · Excel · Power BI
📍 Karnataka — Open to relocation anywhere in India

<p>
  <a href="https://www.linkedin.com/in/shobhith-kounder-768859264">
    <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white"/>
  </a>
  <a href="https://github.com/Shobhith01">
    <img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white"/>
  </a>
</p>

---
