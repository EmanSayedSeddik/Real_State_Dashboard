# 🏡 Egypt Real Estate – Power BI Sales Analysis

![Cover](screenshots/cover.png)

A Power BI project that analyzes real estate sales in Egypt across branches, agents, property types, cities, and customer showings.

In this project, I imported the data into Power BI, cleaned and transformed it using Power Query, and built a 5-page interactive dashboard that supports data-driven decisions on sales performance, property insights, agent and branch performance, the showings funnel, and market trends.

---

## 🎯 Project Objective

To build an interactive report that helps real estate management answer questions such as:

- 💰 Which branches and cities generate the most sales?
- 🏠 Which property types and zones perform best?
- 🧑‍💼 Which agents handle the most transactions?
- 👥 How do property showings convert into purchases?
- 📈 How do sales and showings trend over time?

---

## 🛠️ Tools Used

- 📊 **Microsoft Power BI Desktop** – data modeling, visualization, and interactivity
- 🔄 **Power Query** – data import and transformation
- 🧹 **Data Cleaning** – preparing the data for analysis

---

## 🧹 Data Preparation

The data was imported into Power BI and prepared using Power Query.

The preparation included:

- 🔍 Reviewing the dataset structure and column types
- 🧹 Cleaning inconsistent and missing values
- 📅 Preparing date fields for time-based analysis
- 🏷️ Standardizing categories (property type, zone, specialization)
- 🌎 Organizing location fields (region, city, branch)

---

## 📊 Dashboard Pages

### 1️⃣ Executive Overview

A high-level summary of overall business performance.

- 💰 Total Sales, Total Transactions, Average Transaction Value, Properties Sold
- 🏢 Sales by Branch
- 📈 Monthly Sales Trend
- 🎛️ Slicers: Year, Region, Property Type

![Executive Overview](screenshots/executive-overview.png)

---

### 2️⃣ Property Analysis

Focuses on property types, pricing, and inventory.

- 🏠 Properties Sold, Average Asking Price, Total Properties
- 📊 Sales Value by Property Type
- 💵 Average Asking Price by Property Type
- 📦 Properties by Type
- 🏷️ Average Transaction Value by Zone (Luxury / Mid-Range / Economic)
- 🌆 Sales by City

![Property Analysis](screenshots/property-analysis.png)

---

### 3️⃣ Agent & Branch Performance

Compares branches and agents.

- 💰 Total Sales, Total Transactions, Average Transaction Value
- 🏢 Sales by Branch
- 🧑‍💼 Total Transactions by Agent
- 🥧 Transactions by Branch (share %)
- 🍩 Total Sales by Branch (share %)
- 🎛️ Slicers: Region, Specialization (Commercial / Residential), Year

![Agent & Branch Performance](screenshots/agent-branch-performance.png)

---

### 4️⃣ Showings & Conversion Funnel

Tracks how customer showings turn into purchases.

- 👁️ Total Showings, Customers Shown, Customers Purchased
- 🧑‍💼 Showings by Agent
- 📈 Monthly Showing Trend
- 💬 Showings by Customer Feedback (Negative / Neutral / Positive)

![Showings & Conversion Funnel](screenshots/showings-conversion-funnel.png)

---

### 5️⃣ Location & Market Insights

Analyzes performance by geography and zone.

- 💰 Total Sales, Total Transactions, Average Transaction Value
- 🌆 Transactions by City
- 💵 Sales Value by City
- 🗺️ Total Sales by City (map)
- 🍩 Average Transaction Value by Zone

![Location & Market Insights](screenshots/location-market-insights.png)

---

## 🎛️ Interactive Features

- 🎛️ Slicers: Year, Region, City, Property Type, Specialization
- 🔍 Cross-filtering between visuals
- 🧭 Multi-page navigation with a consistent branded design

---

## 📌 Key Results

| KPI | Result |
|---|---:|
| 💰 Total Sales | **≈ 2T** (branch totals add up to ≈ 2.46T) |
| 🧾 Total Transactions | **100K** |
| 💵 Average Transaction Value | **≈ 25M** |
| 🏠 Properties Sold | **49K** |
| 🏘️ Total Properties | **60K** |
| 👁️ Total Showings | **200K** |
| 👥 Customers Shown / Purchased | **49K / 42K** |

> Figures are as displayed in the dashboard (rounded by Power BI card formatting).

---

## 💡 Key Insights

- 🏢 **North Coast Branch** led sales with **549bn (22.36%)**, followed by Zayed (535bn) and Alex (503bn). **Maadi Branch** was the lowest at **409bn (16.66%)**.
- 🌆 **Alexandria** and **Cairo** had the highest sales value by city, while **Matrouh** was far lower.
- 🏠 Sales value was spread almost evenly across property types (Apartment 495bn, Chalet 493bn, Commercial 488bn, Duplex 478bn, Villa 474bn).
- 🏷️ Average transaction value was very similar across the Luxury, Economic, and Mid-Range zones (≈ 24M–25M).
- 📈 Monthly sales and showings stayed fairly stable from 2022 to 2026.

---

## 🔄 Workflow

```text
Raw Data
   ↓
📥 Import Data (Power BI)
   ↓
🧹 Power Query – Cleaning & Transformation
   ↓
🗂️ Data Model
   ↓
📊 Visuals & KPIs
   ↓
🎛️ Interactive 5-Page Dashboard
   ↓
💡 Business Insights
```

---

## ⚠️ Known Limitations & Next Improvements

- Some property types (Villa, Duplex) appear twice in slicers and charts, which suggests duplicated category values to be standardized in Power Query.
- The Year slicer starts at 1952 while the trend charts start in 2022, so the date range should be reviewed.
- The last month in the trend charts drops sharply, likely because the month is incomplete.
- Currency labels should be unified across pages.

---

## 👩‍💻 Author

**Eman Sayed Seddik**
🔗 [LinkedIn](https://www.linkedin.com/in/eman-sayed-seddik-59bb1616a/)
