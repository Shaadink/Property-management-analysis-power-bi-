#    Property Management Business Intelligence Dashboard
<p align="center">
  <img src="https://github.com/Shaadink/Property-management-analysis-power-bi-/blob/main/real%20estate%20pbi.png"/>
</p>

##  Project Overview
This project presents a **comprehensive Business Intelligence (BI) dashboard** designed to analyze and optimize the performance of a **multi-national property management and sales operation**.  
The dashboard offers insights into **financial performance, sales channels, geographical revenue, and client profiles**, helping decision-makers transition from reactive management to **data-driven strategic planning**.

---

##  Objectives
The main objectives of this BI project were to:

- **Maximize Revenue & Income:** Identify key drivers of revenue growth and profitability across properties.  
- **Optimize Sales Strategy:** Determine the most effective **sales channels** (Broker, Direct, Online) and **property types** (Condo, Single Family, Apartment, Townhouse).  
- **Identify High-Value Markets:** Highlight the top **revenue-generating countries** and their associated **client demographics**.  
- **Improve Operational Stability:** Study monthly sales patterns to mitigate volatility and ensure consistent cash flow.

---

##  Problem Statement
The property management firm lacked a clear, data-backed understanding of its global operations. Key challenges included:

1. **Lack of Granularity:** Difficulty identifying which property types, channels, or locations contributed most to performance.  
2. **Volatile Sales:** Unpredictable month-to-month fluctuations impacting forecasting accuracy.  
3. **Client Targeting Issues:** Inefficient marketing spend due to limited insight into high-value client segments.

This dashboard resolves these issues by providing actionable insights across sales, revenue, expenses, and client behavior.

---

##  Dataset Information

The analysis used a **consolidated dataset** with multiple interconnected tables to provide a complete view of the sales lifecycle.

| Table Name        | Description                                                   | Key Fields |
|-------------------|---------------------------------------------------------------|-------------|
| `sales_data`      | Core transaction records linking properties, clients, and sales channels. | `SaleID`, `PropertyID`, `SaleDate`, `SalesChannel`, `ClientID`, `PaymentStatus` |
| `property_details`| Descriptive details for each managed property.                | `PropertyID`, `Country`, `Location`, `Type`, `Bedrooms`, `Bathrooms`, `SquareFootage`, `Price`, `Status`, `Img` |
| `expense_data`    | Records of operational and property-specific costs.           | `ExpenseID`, `PropertyID`, `ExpenseType`, `Amount`, `Date` |
| `client_data`     | Details of buyers, including their professions and profile images. | `ClientID`, `Name`, `Occupation`, `PropertiesSold`, `Img` |


---

##  Key Insights

###  Performance Summary (2024 YTD vs. 2023)

| Metric | 2023 Performance | 2024 YTD (Partial) | YTD Trend vs. 2023 |
|--------|------------------|--------------------|--------------------|
| **Revenue** | $41 Million | $26 Million | 🔻 -37.5% |
| **Income** | $30 Million | $17 Million | 🔻 -43.3% |
| **Properties Sold** | 60 | 44 | 🔻 -26.7% |
| **Expense** | $11 Million | $9 Million | 🔻 -18.2% |

> **Note:** 2024 data represents a *partial year (YTD)*; thus, declines are relative to the full 2023 year.

---

###  Insights from 2024 YTD Performance

- **Profitability:** Income at $17M on $26M revenue — strong cost control ($9M expenses).  
- **Sales Volume:** 44 properties sold YTD, with a peak in **July ($6.1M)**.  

####  Sales Channel & Product Focus
- **Online** has become the top performer (**$9.5M**), surpassing **Broker** (**$8.9M**) for the first time.  
- **Property Mix:**  
  - Condos: **29.41%**  
  - Single Family: **28.63%**  
  - Apartments: **27.06%**  
  → Revenue is now more **diversified** across property types.

####  Geographical Performance
- **Top Markets (2024):**  
  - 🇮🇳 **India:** $5.1M  
  - 🇲🇽 **Mexico:** $4.2M  
  - 🇧🇷 **Brazil:** $4.1M  
- Reflects a major **shift away** from 2023 leaders (Italy, Germany, Canada).  
- **July** spike followed by August drop → continued sales volatility.

####  Client Profiling
- **Top Clients:**  
  - Emily Davis – Lawyer – **$5.20M**  
  - David Williams – Lawyer – **$4.50M**  
- Lawyers remain the **highest-value demographic**, indicating a strong professional client segment.

---

###  Insights from 2023 Performance
- **Total Income:** $30M on $41M revenue (expenses: $11M).  
- **Property Leader:** Condos (41.18%).  
- **Top Markets:** Italy ($7.0M), Germany ($5.6M), Canada ($5.6M).

---

###  Insights from 2022 Baseline
- **Total Income:** $20M on $30M revenue (expenses: $10M).  
- **Property Leader:** Single Family (33.11%).  
- **Top Markets:** Australia ($4.7M), Japan ($4.2M), France/Canada ($3.4M).

---

##  Recommendations

### 1.  Strategic Pivot to Online
- Prioritize the **Online sales channel**, as it has overtaken Brokers in revenue.
- Increase **digital marketing**, **SEO**, and **user experience investments**.

### 2.  Reallocate Geographical Resources
- Focus marketing and inventory in **India, Mexico, and Brazil**.
- Investigate reasons behind decline in **Italy, Germany, and Canada** and apply recovery strategies.

### 3.  Stabilize Sales Volatility
- Study **July peaks** and **August drops** historically.
- Introduce **off-season campaigns** (e.g., in May) to balance sales distribution.

### 4.  Maintain Client Focus
- Continue targeting **Lawyer and other high-income professionals**.
- Use referral programs or loyalty campaigns to increase engagement in this segment.

### 5.  Diversify Property Inventory
- Since revenue is evenly spread across **Condo, Single Family, and Apartment**, maintain a balanced inventory strategy.

---

##  Technology Stack

| Component | Tool / Language |
|------------|----------------|
| **Data Source** | CSV |
| **Data Cleaning & Processing** | Power Query |
| **Visualization / Dashboard** | Power BI |
| **Version Control** | Git & GitHub |
| **Documentation** | Markdown (README) |



