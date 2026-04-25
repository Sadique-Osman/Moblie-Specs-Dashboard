# 📱 Mobile Specs Intelligence Dashboard

A multi-brand mobile phone analysis dashboard built with **Power BI**, analyzing **224 devices** across **15+ brands** including Samsung, Apple, Google, Vivo, OnePlus, and more.

---

## Dashboard Preview

!<img width="909" height="502" alt="Mobile Specs " src="https://github.com/user-attachments/assets/4afcf698-7387-4998-b4d2-b43908f6a0b6" />


---

## Project Overview

This Power BI dashboard provides deep insights into the mobile phone market in India. It covers pricing, specifications, OS distribution, camera capabilities, and battery performance across multiple brands and price segments.

---

## Tools & Technologies

| Tool | Usage |
|---|---|
| **Power BI Desktop** | Dashboard creation & visualization |
| **Power Query (M Code)** | Data transformation & cleaning |
| **DAX** | Calculated columns & measures |
| **Excel / CSV** | Raw data source |
| **GitHub** | Version control & portfolio |

---

## Dataset Information

| Property | Details |
|---|---|
| Total Devices | 224 phones |
| Total Brands | 15+ |
| Source | 91mobiles.com |
| Columns | 22 (raw) → cleaned |
| Time Period | 2023–2026 launches |

### Columns in Dataset
`phone_name` · `brand` · `price_inr` · `launch_date` · `operating_system` · `chipset` · `min_ram` · `storage` · `main_camera` · `front_camera` · `battery` · `fast_charging` · `display_size` · `display_type` · `resolution` · `sim_type` · `network_support` · `bluetooth` · `nfc` · `price_segment`

---

## 🔧 Data Transformation (Power Query)

Applied the following transformations in Power Query Editor:

- ✅ Promoted headers & changed data types
- ✅ Removed unnecessary columns
- ✅ Split columns by delimiter/position
- ✅ Extracted `min_ram` from `"12 GB / 16 GB"` format
- ✅ Extracted `battery_mah` from `"5000 mAh"` format
- ✅ Extracted `fast_charging_w` from `"Yes, 45W Fast Charging"` format
- ✅ Extracted `display_size_inch` from display raw text
- ✅ Extracted `main_camera_mp` and `camera_count`
- ✅ Filtered null and empty rows
- ✅ Added `price_segment` DAX column

---

## Dashboard Visuals

| Visual | Description |
|---|---|
| **KPI Cards** | Total Phones · Avg Price · Avg Battery · Total Brands · Max Camera |
| **Bar Chart** | Top brands by average price |
| **Donut Chart** | Price segment distribution (Budget / Mid Range / Premium / Flagship) |
| **Column Chart** | Phone count by OS version (Android v11–v16) |
| **Scatter Plot** | RAM vs Price analysis by brand |
| **Table** | Detailed phone specs with all key columns |
| **Slicers** | Filter by Price Segment · RAM · OS Version |

---

## Key Insights

- **Apple** has the highest average price (~₹96K)
- **Mid Range** segment dominates with ~52% of all phones
- **Android v15** is the most common OS (~90 phones)
- Average battery capacity across all phones is **5,589 mAh**
- Maximum camera resolution is **200 MP**
- **~80%** of phones support 5G network

---

## Dashboard Design

- **Background**: Custom designed dark tech theme (HTML/CSS → PNG)
- **Color Scheme**: Deep navy `#080C14` + Cyan `#00B4FF` + Teal `#00C8B4`
- **Canvas Size**: 1920 × 1080px
- **Theme**: Mobile tech with circuit board pattern, phone silhouettes, camera lens elements

---

## Repository Structure

```
Mobile-Specs-Dashboard/
│
├── 📊 dashboard_screenshot.png    # Final dashboard screenshot
├── 🖼️ dashboard_background.png   # Custom dashboard background
├── 📄 README.md                   # Project documentation
└── 📁 data/
    └── device_specs_dataset.csv   # Raw dataset
```

---

## How to Use

1. Clone this repository
2. Open Power BI Desktop
3. Load `device_specs_dataset.csv`
4. Apply Power Query transformations as documented
5. Import `dashboard_background.png` as canvas background
6. Recreate visuals as described above

---

## 👤 Author

**Mohammad Sadique**
- Portfolio: [sadique-osman.github.io/portfolio](https://sadique-osman.github.io/portfolio)
- LinkedIn: [linkedin.com/in/mohammad-sadique-1028ba2a1](https://linkedin.com/in/mohammad-sadique-1028ba2a1)
- GitHub: [github.com/Sadique-Osman](https://github.com/Sadique-Osman)

---

## Certifications

- 🏆 Deloitte Data Analytics Job Simulation — Forage (March 2026)
- 🏆 Complete Data Analyst Bootcamp — Udemy (March 2026)
- 🏆 Power BI Workshop — Be10x (March 2026)

---

⭐ *If you found this project helpful, please give it a star!*
