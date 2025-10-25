# 📊 Sales & Marketing Dashboard

![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=flat-square&logo=powerbi&logoColor=black)
![Excel](https://img.shields.io/badge/Excel-217346?style=flat-square&logo=microsoft-excel&logoColor=white)
![Status](https://img.shields.io/badge/Status-Complete-success?style=flat-square)

---

## 🔹 Overview

This project presents a **Sales & Marketing Analytics Dashboard** created in Power BI.  
The dashboard provides comprehensive insights into revenue performance, profit margins, cost analysis, and marketing effectiveness.  
It combines **interactive visualizations**, **DAX measures**, and **multi-dimensional analysis** to help decision-makers track business metrics across different years, channels, and regions.

---

## 🔹 Dashboard Highlights

- **Total Revenue**: 630K (↑ 4.75%)
- **Total Profit**: 136K (↑ 3.14%)
- **Total Cost**: 493K (↑ 5.21%)
- **Time Period**: Multi-year analysis (2022, 2023, 2024)
- **Sales Channels**: Online (67.3%) vs In-Store (32.7%)
- **Top Lead Source**: Email generating 145K revenue
- **Top Market**: United Kingdom leading with 78,725 revenue

---

## 🔹 Key Insights

### 📈 Revenue Performance
- **Year-over-Year Growth**: Consistent revenue growth of 4.75%
- **Monthly Trends**: Fluctuating revenue pattern throughout the year
- **Channel Distribution**: Online sales dominate at 67.3% (424K)
- **Peak Performance**: Notable revenue spikes in specific months

### 💰 Profitability Analysis
- **Profit Margin**: 136K profit with 3.14% growth
- **Cost Management**: 493K total cost with 5.21% increase
- **Top Performing Region**: United Kingdom (13.73% revenue growth, 11.30% profit growth)
- **High Growth Market**: South Korea showing 25.07% revenue growth

### 🎯 Marketing Effectiveness
- **Lead Source Performance**:
  - Email: 145K (Top performer)
  - Referral: 136K
  - Social Media: 119K
  - Cold Calling: 117K
  - Website: 113K

### 🌍 Geographic Insights
- **Top Countries**:
  - United Kingdom: 78,725 revenue (13.73% growth)
  - United States: 87,479 revenue (13.65% growth)
  - South Korea: 79,583 revenue (25.07% growth)
- **Regional Performance**: Strong growth across all major markets

---

## 🔹 Data Structure

### Original Dataset Fields
```
- Sales ID
- Customer Name
- Product
- Sales Date
- Sales Amount (USD)
- Cost Price (USD)
- Sales Channel
- Country
- Region
- Sales Rep
- Marketing Campaign
- Lead Source
- Conversion Rate (%)
- Sessions
- Views
- Follow-ups
- Closed Deal?
- Customer Feedback
- Customer Plan
- Customer Rating
```

---

## 🔹 Data Processing Workflow

### Step 1: Data Cleaning
- ✅ Removed duplicate sales records
- ✅ Handled missing customer information
- ✅ Standardized date formats across years
- ✅ Validated sales amounts and cost prices
- ✅ Fixed inconsistent country and region entries

### Step 2: Data Modeling
- **Fact Table**: Sales transactions with measures
- **Dimension Tables**:
  - Dim_Date (year, month, day hierarchy)
  - Dim_Customer (customer details)
  - Dim_Product (product information)
  - Dim_Geography (country and region)
  - Dim_Marketing (campaigns and lead sources)
  - Dim_Channel (online vs in-store)

### Step 3: DAX Measures
Created advanced calculations for revenue growth, profit margins, cost analysis, and period comparisons.

---

## 🔹 Files Included

- `sales_marketing_raw_data.xlsx` → Original raw dataset
- `cleaned_data.xlsx` → Cleaned and processed data
- `sales_marketing_dashboard.pbix` → Power BI dashboard file
- `dashboard_screenshot.png` → Dashboard preview image
- `README.md` → Project documentation

---

## 🔹 Preview

Here is a snapshot of the dashboard:

![Sales Dashboard](sales%20%26%20marketing%20data%20analysis/sales%20dashboard.png)

---

## 🔹 How to Use

1. **Download** and open `sales_marketing_dashboard.pbix` in Power BI Desktop (latest version recommended).
2. **Explore** interactive filters for years (2022, 2023, 2024) at the top of the dashboard.
3. **Refresh** data connection if needed by updating the data source path.
4. **Interact** with visualizations:
   - Click on year buttons to filter all visuals
   - Hover over charts for detailed tooltips
   - Click on countries in the table to cross-filter
   - Analyze revenue trends by month
5. **Drill down** into specific lead sources and sales channels for deeper insights.

---

## 🔹 Dashboard Features

### 📊 Visualizations
- **KPI Cards**: Revenue, Profit, and Cost with growth indicators
- **Line Chart**: Monthly revenue trends with previous month comparison
- **Donut Chart**: Revenue distribution by sales channel
- **Bar Chart**: Revenue breakdown by lead source
- **Data Table**: Country-level performance with flags and growth metrics

### 🎨 Design Elements
- Clean, professional blue color scheme
- Interactive year selector buttons
- Growth percentage indicators with color coding
- Icon-based KPI cards for quick insights
- Responsive layout for easy navigation

---

## 🔹 Technologies Used

- **Power BI Desktop** - Dashboard creation and visualization
- **Power Query** - Data transformation and ETL
- **DAX** - Advanced calculations and measures
- **Excel** - Raw data source
- **Data Modeling** - Dimensional modeling approach

---

## 🔹 Business Recommendations

### 💡 Strategic Actions
1. **Maximize Email Marketing**: Email generates highest revenue (145K) - invest more in email campaigns
2. **Expand Online Presence**: Online channel dominates (67.3%) - optimize digital experience
3. **Focus on High-Growth Markets**: South Korea shows 25.07% revenue growth - expand operations
4. **Cost Optimization**: Cost growing faster (5.21%) than revenue (4.75%) - review cost structure
5. **Leverage Top Markets**: UK and US show strong consistent performance - maintain market share

---


---

Made with ❤️ using Power BI
