# 🏨 Hotel Management Report | Power BI Dashboard

## Overview
--
This Power BI dashboard provides a complete overview of hotel performance, focusing on revenue, room occupancy, booking behavior, and customer segmentation.  
It helps hotel managers monitor operational performance across different segments such as market type, hotel type, customer type, room type, and distribution channel.
--
## 📁 Dataset Description
--
The dataset includes anonymized hotel operational records, including revenue metrics, occupancy data, market segments, room categories, and booking details.

--
### Key Columns
--
- Total Revenue  
- Week Nights Revenue  
- Weekend Nights Revenue  
- Total Occupied Rooms  
- Average Days of Stay  
- Market Segment (Online TA, Offline TA/TO, Direct, Groups, Corporate, etc.)  
- Distribution Channel (TA/TO, Direct, Corporate, GDS)  
- Customer Type (Transient, Transient-Party, Contract, Group)  
- Reserved Room Type (A, D, E, F, G…)  
- Hotel Type (City Hotel, Resort Hotel)  
- Country (for revenue map visualization)  

--
## 📐 Data Model and Measures
--
Common DAX measures used include:  

- Total Revenue = SUM(Revenue)  
- Week Nights Revenue  
- Weekend Nights Revenue  
- Total Occupied Rooms  
- Avg Days of Stay = AVERAGE(Stays)  
- Revenue by Segment  
- Revenue by Room Type  
- Revenue by Distribution Channel  
- Revenue by Country  

--

## 📊 Dashboard Features (Based on Your Screenshot)
--
### 1. KPI Cards
- Total Revenue: $26.0M  
- Week Nights Revenue: $18.9M  
- Weekend Nights Revenue: $7.1M  
- Total Occupied Rooms: 75K  
- Avg Days of Stay: 3  

### 2. Top 10 Countries by Total Revenue (Map Visualization)
Geographical distribution of revenue highlighting major contributing countries:  
Portugal, Spain, France, Italy, Germany, Belgium, Netherlands, Ireland, Switzerland (CHE)  

### 3. Revenue by Market Segment
Revenue contribution by segments:  
- Online TA → $13.7M  
- Offline TA/TO → $5.65M  
- Direct → $4.10M  
- Groups → $1.86M  
- Corporate, Aviation, Complementary (smaller contributions)  

### 4. Total Revenue by Hotel Type (Donut Chart)
- Resort Hotel → $14.4M (55.37%)  
- City Hotel → $11.6M (44.63%)  

### 5. Revenue by Distribution Channel
- TA/TO: $20.8M  
- Direct: $4.3M  
- Corporate: $0.82M  
- GDS: $0.03M  
- Undefined: $0.6K  

### 6. Revenue by Customer Type
- Transient → $19.33M  
- Transient-Party → $5.05M  
- Contract → $1.48M  
- Group → $0.12M  

### 7. Revenue by Reserved Room Type (Tree Map)
- Room Type A → $14.5M  
- Room Type D → $6.0M  
- Room Type E → $2.5M  
- Other types (F, G, etc.) contribute smaller amounts  

--
## 🔍 Insights Discovered
--
### Revenue Insights
- Total hotel revenue is $26M, with the majority generated from Resort Hotels  
- Online TA brings the largest revenue share among market segments  

### Customer Behavior
- Transient customers dominate overall revenue contribution  
- Bookings via TA/TO channels significantly outperform other channels  

### Geographical Insights
- Western European countries contribute heavily to hotel revenue  
- Countries like Portugal, Spain, France, Italy, and Germany are top performers  

### Room & Stay Insights
- Room Type A dominates revenue generation  
- Guests stay on average 3 days, indicating short-to-medium stay patterns  

--
## 🛠️ Tools Used
--
- Power BI Desktop  
- Power Query (for ETL and modeling)  
- DAX (for measures and KPIs)  
- Excel/CSV dataset  

--
## 🖼️ Dashboard
--
Insert your screenshot:  

![Hotel Management Dashboard](./Dashboard/Screenshot134.png)  

--

## 💼 Business Value
--
- Helps hotel management track revenue performance in real time  
- Enables data-driven decisions for pricing, staffing, and marketing  
- Highlights opportunities for optimizing room utilization  
- Supports segmentation strategies to improve profitability  
- Visualizes high-value channels and markets for targeted campaigns  

--
## ▶️ How to Run
--
1. Download the Hotel_Report.pbix file  
2. Download the dataset from the /Dataset folder  
3. In Power BI:  
   - Home → Transform Data → Data Source Settings → Change Source  
   - Update the file path to the dataset  
   - Refresh the dashboard  
4. Use slicers (Year, Market Segment, Room Type, Hotel Type, Metrics) to explore insights
--
