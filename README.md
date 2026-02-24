# Dynamic-Dashboard
The Dynamic Retail Dashboard is an interactive and data-driven tool built in Excel to visualize and analyze retail data. It connects to datasets hosted on GitHub, uses Power Query for data transformation, and presents insights through dynamic charts and KPIs. The dashboard solves key business questions, enabling informed decision-making.
Datasets Used
📊 Retail Sales Dashboard (Excel)

An interactive Retail Sales Dashboard built in Microsoft Excel using Power Query, Pivot Tables, Charts, and Slicers to analyze sales performance, profitability, customer segments, and returns data.

📁 Datasets Used

The dashboard is built using three primary datasets:

1️⃣ Orders Table

Contains detailed information about customer orders, shipping, and financial performance.

Key Columns:

Order ID

Returned

Order Date

Ship Date

Ship Mode

Customer Name

Segment

Country

Market

Sales

Profit

Discount

Sample Data:

Order ID	Returned	Order Date	Ship Date	Ship Mode	Customer Name	Segment	Country	Market	Sales	Profit	Discount
CA-2012-124891	No	31-07-2020	31-07-2020	Same Day	Rick Hansen	Consumer	United States	US	2309.65	762.18	0
IN-2013-77878	Yes	05-02-2021	07-02-2021	Second Class	Justin Ritter	Corporate	Australia	APAC	3709.40	-288.77	0.1
2️⃣ Returns Table

Tracks returned orders along with their respective markets.

Columns:

Returned

Order ID

Market

Sample Data:

Returned	Order ID	Market
Yes	MX-2013-168137	LATAM
Yes	US-2011-165316	LATAM
Yes	ES-2013-1525878	EU
3️⃣ People Table

Contains details of sales representatives and their regions.

Columns:

Person

Region

Sample Data:

Person	Region
Anna Andreadi	Central
Chuck Magee	South
Kelly Williams	East
🎯 Problem Statements Solved
1️⃣ Key Performance Indicators (KPIs)

Objective:
Dynamically calculate and display:

Total Sales

Total Profit

Total Quantity

Number of Orders

Profit Margin

Implementation Steps:

Imported Orders table using Power Query

Created calculated column:

Profit Margin = Profit / Sales

Used formulas:

=SUM(Sales)

=SUM(Profit)

=SUM(Quantity)

=COUNT(Order ID)

Built a KPI summary section with formatted indicators

2️⃣ Sales & Profit Trend Analysis

Objective: Identify sales and profit patterns over time.

Steps:

Created Pivot Table grouped by Year & Month

Added Sales and Profit as values

Built a Line Chart for trend visualization

Added Slicers for dynamic filtering

3️⃣ Category-Wise Profit Analysis

Objective: Evaluate profitability across product categories.

Steps:

Pivot Table with Category (Rows) and Profit (Values)

Sorted in descending order

Created Bar Chart

Added slicers for interactivity

4️⃣ Segment-Wise Sales Share (%)

Objective: Analyze sales distribution across customer segments.

Steps:

Pivot Table with Segment and Sales

Calculated percentage share:

Sales % = Sales / Total Sales * 100

Created Pie/Donut Chart

Added dynamic data labels

5️⃣ Sales by Country

Objective: Identify top-performing countries.

Steps:

Pivot Table with Country and Sales

Sorted in descending order

Applied Conditional Formatting / Heatmap

6️⃣ Top 5 Sub-Categories

Objective: Identify highest-performing subcategories.

Steps:

Pivot Table with Sub-Category and Sales

Sorted in descending order

Filtered Top 5

Visualized using Column Chart

⚙️ Dynamic Features

✔️ Interactive Slicers
✔️ Dynamic KPI Cards
✔️ Real-time Chart Updates
✔️ Automated Data Cleaning via Power Query
✔️ Interactive Pivot Tables

🛠 Tools & Technologies Used

Microsoft Excel

Power Query

Pivot Tables

Pivot Charts

Slicers

Conditional Formatting

🚀 How to Use

Download the Dashboard.xlsx file from this repository.

Open in Microsoft Excel (2016 or later recommended).

Use slicers to filter by:

Market

Segment

Region

Category

Dashboard visuals update automatically.

📈 Business Insights Enabled

Identify top-performing markets and countries

Monitor profit trends over time

Analyze segment contribution to revenue

Detect high-return markets

Track category profitability

🔮 Future Enhancements

Add forecasting using Excel Forecast Sheet

Integrate Power BI version

Add automated refresh from external data source

Include advanced DAX-based metrics

📌 Author

[Your Name]
Retail Sales Dashboard Project
Excel Data Analytics

If you’d like,
