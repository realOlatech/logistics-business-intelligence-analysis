# Logistics Business Intelligence & Performance Analysis

## Project Overview

This project analyzes logistics operations data from 2022–2024 to evaluate financial performance, fleet efficiency, driver performance, customer activity, safety performance, maintenance, fuel efficiency, and demand patterns.

The objective is to transform operational data into meaningful business insights that can support better decision-making across logistics and transportation operations.

## Business Problem

Although logistics organizations generate large amounts of operational data, it can be difficult to identify the factors driving profitability, fleet efficiency, customer performance, safety, and demand.

The analysis investigates:

- How profitable is the logistics operation?
- Which routes and customers contribute the most revenue and profit?
- How efficiently are trucks and other assets being utilized?
- Which drivers demonstrate stronger delivery performance?
- What is the impact of maintenance and vehicle downtime?
- How are fuel efficiency and fuel costs changing?
- What are the major safety incident patterns?
- How does load demand change over time?
- How do transportation rates fluctuate with load volume?

## Data Preparation & Transformation

- Cleaned and prepared the logistics datasets
- Performed data transformation using Power Query
- Conducted analytical calculations using SQL
- Developed calculated measures using DAX
- Created KPIs for financial and operational performance
- Structured data for dashboard reporting
- Validated calculated metrics before visualization

### Key Calculations

- Total Revenue
- Total Route Cost
- Total Profit
- Profit Margin
- Total Loads
- Average MPG
- Miles per Truck
- Revenue per Asset
- Cost per Mile
- Total Downtime Hours
- Completed Load %
- Incident Rate per 100 Trips
- Preventable Accident Rate
- Average Revenue per Load

## Analytical Approach

- Financial performance analysis
- Route profitability analysis
- Fleet utilization analysis
- Driver performance analysis
- Maintenance and downtime analysis
- Fuel efficiency analysis
- Customer revenue analysis
- Safety and incident analysis
- Seasonal demand and rate analysis

The analysis was presented through three interactive Power BI dashboards:

- Executive Report
- Fleet & Driver Performance
- Customer, Safety & Demand Analytics

## Key Findings

- Total revenue generated during the analysis period was **$298.62M**.
- Total route cost was **$101.32M**, resulting in **$197.30M total profit**.
- Overall profit margin was **66.07%**.
- The operation recorded approximately **85K loads**.
- Average MPG across the operation was **6.50**.
- Total fleet downtime was approximately **72.23K hours**.
- Revenue per asset was approximately **$262.53M** based on the dashboard calculation.
- The completed load rate was **100%**.
- The incident rate was approximately **19.90 incidents per 100 trips** based on the dashboard KPI.
- The preventable accident rate was **37.65%**.
- Average revenue per load was approximately **$3.50K**.
- Load volumes remained relatively consistent across the period, generally ranging between approximately **2.2K and 2.5K loads per month**.
- Route-level analysis showed substantial differences in revenue, route cost, profit, and profit margin across transportation lanes.
- Customer revenue was concentrated among a number of high-value customers, with the leading customer generating approximately **$10.39M** in revenue.

## Business Recommendations

### Improve Route Profitability

- Monitor low-margin transportation lanes closely.
- Prioritize high-profit routes where operational capacity allows.
- Review pricing and cost structures on less profitable lanes.
- Use route-level profitability to support future pricing decisions.

### Improve Fleet Efficiency

- Monitor miles generated per truck.
- Investigate assets with high maintenance costs or downtime.
- Identify underutilized assets.
- Use maintenance and utilization metrics together when evaluating fleet performance.

### Improve Driver Performance

- Monitor on-time delivery performance regularly.
- Identify drivers with consistently lower delivery rates for targeted support.
- Use performance trends to guide training and operational interventions.

### Strengthen Fuel Management

- Monitor MPG trends alongside fuel costs.
- Investigate periods of declining fuel efficiency.
- Evaluate vehicles with consistently poor fuel performance.

### Improve Safety Performance

- Monitor incident rates and preventable accident rates.
- Focus safety interventions on recurring incident categories.
- Strengthen driver safety training and preventive measures.

### Support Demand & Pricing Decisions

- Monitor monthly load volumes to identify demand patterns.
- Compare load volume with average transportation rates.
- Use demand trends to support capacity planning and pricing strategies.

## Tools Used

- Microsoft Power BI
  - Interactive Dashboards
  - KPI Cards
  - Data Visualization
  - DAX Measures
  - Data Modeling
- SQL
  - Data Analysis
  - Aggregation
  - Business Calculations
- Power Query
  - Data Cleaning
  - Data Transformation
- Microsoft Excel
  - Data Validation
  - Supporting Analysis

---

# Project Report

## 1. Executive Performance Analysis

This dashboard provides a high-level overview of the logistics operation's financial and operational performance.

### Key Metrics

- Total Revenue: **$298.62M**
- Total Route Cost: **$101.32M**
- Total Profit: **$197.30M**
- Total Loads: **85K**
- Average MPG: **6.50**
- Profit Margin: **66.07%**

### Key Observation

The business generated substantial revenue and maintained a strong overall profit margin. However, profitability varies across individual transportation lanes, making route-level analysis important for identifying opportunities to improve cost efficiency and margins.

---

## 2. Fleet & Driver Performance

This analysis evaluates the efficiency of transportation assets and driver performance.

### Key Metrics

- Miles per Truck: **122M**
- Cost per Mile: **0.05**
- Revenue per Asset: **$262.53M**
- Total Downtime Hours: **72.23K**

### Driver Analysis

The dashboard compares the top drivers based on on-time delivery performance and highlights drivers with the highest maintenance-associated costs.

### Key Observation

Fleet productivity should be evaluated alongside maintenance exposure and downtime. Assets generating high utilization but also experiencing significant downtime or maintenance costs may require closer operational review.

---

## 3. Fuel Efficiency Analysis

The Fuel Cost & MPG Trend compares fuel expenditure with average MPG over time.

### Key Observation

Fuel efficiency fluctuates throughout the analysis period. Monitoring MPG alongside fuel costs provides management with a better understanding of changes in transportation operating efficiency.

---

## 4. Customer Analysis

Customer performance was analyzed using revenue contribution and load completion metrics.

### Key Customer Finding

The leading customer generated approximately **$10.39M** in revenue, followed by other major customers contributing significant portions of total revenue.

### Key Observation

Customer revenue is not evenly distributed. Monitoring high-value customers can therefore support account management, retention strategies, and revenue planning.

---

## 5. Safety Analysis

Safety performance was evaluated using:

- Incident Rate per 100 Trips
- Preventable Accident Rate
- Incident Severity Distribution

### Key Metrics

- Incident Rate per 100 Trips: **19.90%**
- Preventable Accident Rate: **37.65%**

### Incident Distribution

The dashboard identifies several major incident categories, including:

- DOT Violations
- Accidents
- Equipment Damage
- Customer-related incidents
- Moving Violations

### Key Observation

The preventable incident rate indicates an opportunity to strengthen preventive safety measures, driver training, and operational controls.

---

## 6. Demand & Pricing Analysis

Monthly load volume was analyzed together with average revenue/rate.

### Key Metrics

- Completed Load Rate: **100%**
- Average Revenue per Load: **$3.50K**

### Key Observation

Monthly load volumes remain relatively stable throughout the available period, while average rates fluctuate.

Comparing these two metrics provides useful context for understanding changes in transportation demand and pricing.

---

## 7. Route Profitability

Route profitability was evaluated using:

- Total Revenue
- Total Route Cost
- Total Profit
- Profit Margin

The dashboard highlights the most profitable lanes and allows routes to be compared based on their financial contribution.

### Key Observation

Route-level profitability varies considerably. This indicates that revenue alone is not sufficient for evaluating route performance; transportation costs and resulting margins must also be considered.

---

## 8. Overall Business Recommendations

Based on the analysis, logistics management should:

- Prioritize high-margin transportation lanes.
- Review routes with relatively high costs.
- Improve utilization of transportation assets.
- Monitor assets with high maintenance costs and downtime.
- Strengthen driver performance monitoring.
- Improve fuel efficiency through continuous MPG monitoring.
- Focus safety interventions on preventable incidents.
- Monitor high-value customers closely.
- Use demand and rate trends to support capacity and pricing decisions.

## Conclusion

This project demonstrates how logistics data can be transformed into a centralized Business Intelligence solution.

The analysis provides visibility into **financial performance, route profitability, fleet utilization, driver performance, maintenance, fuel efficiency, customer contribution, safety, and demand patterns**.

The resulting dashboards provide management with a clear and interactive way to monitor operational performance and identify opportunities for improved profitability, efficiency, safety, and customer service.

## Dashboard

### Executive Report

<img width="1412" height="753" alt="Screenshot 2026-08-27 083603" src="https://github.com/user-attachments/assets/1dea8ae8-502f-42cd-b59a-97ab2b846301" />


### Fleet & Driver Performance

<img width="1405" height="750" alt="Screenshot 2026-08-27 083626" src="https://github.com/user-attachments/assets/e27b7463-6a41-4f67-80b2-ad31837f22de" />


### Customer, Safety & Demand Analytics

<img width="1417" height="760" alt="Screenshot 2026-08-27 083643" src="https://github.com/user-attachments/assets/ff9720bd-641d-4317-81b4-8f4420245103" />
