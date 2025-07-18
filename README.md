Key Features
Data imported from CSV files into SQL Server / MySQL

Power BI connected to SQL for creating visual dashboards

Data cleaned and transformed using Power BI tools

Final dashboard includes KPIs, trends, and breakdowns

📌 Insights from the Dashboard
Total Profit and Revenue trend by month

Region-wise sales performance

Most and least profitable item types

Online vs Offline sales breakdown

High-priority order analysis

Shipment vs Order date gap check

🧮 DAX Measures Used
DAX
Copy
Edit
RegionCount = DISTINCTCOUNT(reliance_sales[Region])  
TotalProfit = SUM(reliance_sales[Total_Profit])
I also added some calculated columns and filters for better insights.

📈 Visuals Included
KPI Cards: Units Sold, Total Revenue, Total Profit

Bar Chart by Region

Line Chart for Monthly Trends

Pie Chart showing Sales Channel

Slicers for Region, Item Type, and Order Priority

All visuals have proper titles, labels, and custom colors

📁 Folder Structure
mathematica
Copy
Edit
Reliance-Sales-Report/
├── Dataset/            → Cleaned CSV files  
├── Report/             → Power BI .pbix file  
├── Screenshots/        → Charts and visuals  
├── Documentation/      → Notes, data dictionary, etc.  
├── README.md           → Overview of the project
🛠 Tools Used
Power BI

SQL Server / MySQL

Excel / CSV for raw data

GitHub for uploading the project

💡 Business Value
This dashboard helps users and managers to:

Understand sales trends across regions and products

Monitor monthly profits and revenue

Compare online and offline channels

Take decisions based on order priority and shipment patterns

