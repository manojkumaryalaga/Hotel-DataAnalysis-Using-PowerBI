# Hotel Management Dashboard (Power BI)

## Overview
This Power BI project analyzes hotel performance across revenue, occupancy, customer types, and booking patterns.  
It highlights how factors such as market segment, distribution channel, hotel type, country, and room category influence total revenue and operational efficiency.

---

## Dataset Description
The dataset contains anonymized hotel booking records, room details, customer information, and revenue metrics.

### Key Columns
- Total Revenue  
- Week Nights Revenue  
- Weekend Nights Revenue  
- Total Occupied Rooms  
- Average Days of Stay  
- Market Segment (Online TA, Offline TA/TO, Direct, Groups, Corporate)  
- Distribution Channel (TA/TO, Direct, Corporate, GDS)  
- Customer Type (Transient, Transient-Party, Contract, Group)  
- Reserved Room Type (A, D, E, F, G, etc.)  
- Hotel Type (City Hotel, Resort Hotel)  
- Country  

Total Bookings: 119,390  
Total Revenue: $26 Million  
Avg Length of Stay: 3 Days  

---

## Data Model and Measures
Calculated fields and DAX measures:
- Total Revenue = SUM(Revenue)  
- Week Nights Revenue  
- Weekend Nights Revenue  
- Total Occupied Rooms  
- Avg Days of Stay = AVERAGE(Stays)  
- Revenue by Market Segment  
- Revenue by Country  
- Revenue by Distribution Channel  
- Revenue by Room Type  

---

## Dashboard Features
- KPI Cards: Total Revenue, Weekday Revenue, Weekend Revenue, Occupied Rooms, Avg Stay  
- Revenue by Market Segment  
- Revenue by Distribution Channel  
- Country-wise Revenue Map  
- Customer Type Revenue Contribution  
- Hotel Type Performance (City vs Resort Hotel)  
- Room Type Revenue (A, D, E, F, etc.)  
- Filters: Hotel Type, Room Type, Market Segment, Distribution Channel, Country  

---

## Insights Discovered
1. Revenue Overview  
   - Total revenue reached $26M, led primarily by Resort Hotels.  
   - Weekday revenue dominates, showing strong business travel patterns.  

2. Market Segment Behavior  
   - Online Travel Agencies contribute the highest revenue share (~$13.7M).  
   - Offline TA/TO and Direct bookings also play a major role in total revenue.  

3. Customer Profile Patterns  
   - Transient customers generate the largest share of revenue.  
   - Contract customers show stable but smaller revenue contribution.  

4. Distribution Channel Insights  
   - TA/TO channels dominate revenue with over $20M contributed.  
   - Corporate and GDS channels show lower but consistent activity.  

5. Room Type Performance  
   - Room Type A is the most heavily booked and highest revenue generator (~$14.5M).  
   - Types D and E follow but at significantly lower contribution levels.  

6. Geographic Insights  
   - Portugal, Spain, France, Germany, and Italy are top revenue contributors.  
   - Western Europe drives the majority of hotel business activity.  

---

## Tools Used
- Power BI Desktop for data modeling and dashboard creation  
- Power Query for cleanup and transformation  
- DAX for KPIs and calculations  
- Excel/CSV as the dataset source  

---

## Hotel Dashboard 
---
![Hotel Data Analysis Dashboard](./Dashboard%20screenshots/Screenshot%20(134).png)

---

## Business Value
- Helps hotel management track revenue drivers and occupancy trends  
- Supports pricing, forecasting, and marketing decisions  
- Identifies high-performing customer groups and distribution channels  
- Enables geographic targeting and channel optimization  
- Improves overall operational efficiency  

---

## How to Run
1. Open Hotel_Report.pbix in Power BI Desktop.  
2. Load the dataset or update the file path via Data Source Settings.  
3. Refresh the dashboard to view all KPIs and visuals.  
4. Use slicers to analyze by market segment, hotel type, room type, or country.  

---
