# Business_Insights_360-PowerBI_Project

**Project Overview**:

AtliQ Hardware is a computer and it's parts hardware manufacturing company that sells various products to customers across different countries and regions.

𝗣𝗿𝗼𝗯𝗹𝗲𝗺 𝗦𝘁𝗮𝘁𝗲𝗺𝗲𝗻𝘁 : 

AtliQ Technologies, a rapidly growing consumer electronics company, faced significant data analysis challenges relying solely on Excel, which proved inefficient during a major financial loss in Latin America.

𝗣𝗿𝗼𝗷𝗲𝗰𝘁 𝗚𝗼𝗮𝗹 : 

Leverage Power BI to enhance data analytics capabilities, addressing key metrics of finance, sales, marketing, supply chain, executive queries from stakeholders. The project utilized an extensive dataset with large number of records.

𝗧𝗼𝗼𝗹𝘀 𝗨𝘀𝗲𝗱 : SQL, Excel, Power BI Desktop, Power BI service, Power Query, DAX, M language, DAX Studio (for optimizing reports) and Performnace analyser. 

**Power BI Techniques**:

𝐏𝐨𝐰𝐞𝐫 𝐐𝐮𝐞𝐫𝐲: Data cleaning, column transformation, conditional columns, and creating date tables using M language.

𝐃𝐀𝐗: Measures for KPIs using functions like SUMX, HASONEVALUE, CALCULATE, ALL, SWITCH, SAMEPERIODLASTYEAR, ISFILTERED, ISCROSSFILTERED, and more.

𝐃𝐚𝐭𝐚 𝐌𝐨𝐝𝐞𝐥𝐢𝐧𝐠: Star Schema.

𝐁𝐨𝐨𝐤𝐦𝐚𝐫𝐤𝐬: for visual toggling with buttons.

𝐅𝐢𝐞𝐥𝐝 𝐏𝐚𝐫𝐚𝐦𝐞𝐭𝐞𝐫𝐬: for selection-based visuals and What-If parameters for sliders.

𝐓𝐨𝐨𝐥𝐭𝐢𝐩𝐬: for trend visualization.

𝐑𝐞𝐩𝐨𝐫𝐭 𝐏𝐚𝐠𝐞 𝐍𝐚𝐯𝐢𝐠𝐚𝐭𝐢𝐨𝐧: for switching between report pages.

𝐂𝐨𝐧𝐝𝐢𝐭𝐢𝐨𝐧𝐚𝐥 𝐅𝐨𝐫𝐦𝐚𝐭𝐭𝐢𝐧𝐠: Highlighting key insights.

𝐏𝐞𝐫𝐬𝐨𝐧𝐚𝐥 𝐆𝐚𝐭𝐞𝐰𝐚𝐲 𝐂𝐨𝐧𝐟𝐢𝐠𝐮𝐫𝐚𝐭𝐢𝐨𝐧 for Automatic data refresh in PowerBI service.

**About Dataset:** - Four years transactional data (sep 2017-dec2021), contains around 1.85 Million records. Dimension tables of customer, product, dates, market. And Fact tables of monthly sales, forecast monthly sales data.
- Data sources: MS Excel files and MySQL database files.
- Products are divisioned as PC, P&A, N&S And product selling channels to consumers are Retailer, Direct & Distributor. 
  
**Actions:**

First gathered the required things from clients meet and built the Project charter/Business Requirement Documents (BRD). After approvals of BRD, the dashboard mockups are sent to client with key metrics. And once they are approved, developed Power BI reports that deliver crucial insights for various departments— Finance, Sales, Marketing, Supply Chain and Executive. These reports track essential KPIs, enabling informed, data-driven decisions across the company.   


<br/>**<h3>Data Modelling</h3>** 

<p align="center">
  <img src="https://github.com/PrashantHangal/Business_Insights_360-PowerBI_Project/blob/main/Data%20Modelling.jpg?raw=true" alt="Data Modelling" width="100%" />
</p>

Use of Star Schema and Snowflake schema, for drafting meaningful relationship between tables.

<br/>**<h3>Home Page</h3>** 

<p align="center">
  <img src="https://github.com/PrashantHangal/Business_Insights_360-PowerBI_Project/blob/main/BI360_Home.jpg?raw=true" alt="Home" width="100%" />
</p>


<br/>**<h3>Finance View</h3>** 

- Analyze Profit & Loss statements, for line items like Gross Sales, Net Sales, Gross Margin %, Net Profit % and comparing their values with current and previous years, also with Benchmarks.
- Identifying top-performing products and customers by P & L values and their change percentage.
- Implemented a financial forecasting model, resulting in more accurate budget predictions.
  

<p align="center">
  <img src="https://github.com/PrashantHangal/Business_Insights_360-PowerBI_Project/blob/main/Finance_view.jpg?raw=true" alt="Home" width="100%" />
</p>


<br/>**<h3>Sales View</h3>** 

- Examined Customer and Product performance, with insights into Net Sales, Gross Margin %, and unit economics, including COGS and deductions.
- Created customer and product overall sales performance report. Identified sales trends and track KPIs.

  
<p align="center">
  <img src="https://github.com/PrashantHangal/Business_Insights_360-PowerBI_Project/blob/main/Sales_view.jpg?raw=true" alt="Home" width="100%" />
</p>


<br/>**<h3>Marketing View</h3>** 

- Gain a comprehensive view of Product, Market, Regional, and Customer performance, while tracking GM% and NP% across segments. Delve into unit economics with detailed COGS, operational expenses, and NP analysis.
- Created region and product wise overall market performance report and unit economics. Identified market trends and track KPIs.

  
<p align="center">
  <img src="https://github.com/PrashantHangal/Business_Insights_360-PowerBI_Project/blob/main/Marketing_view.jpg?raw=true" alt="Home" width="100%" />
</p>


<br/>**<h3>Supply Chain View</h3>** 

- Track Forecast Accuracy, Net Error, and Absolute Error metrics. Observe Accuracy and Net Error trends and review metrics by product for supply chain optimization.
- Identified forecast accuracy % , net error % ,absolute error % trends. Key Metrices by customers and products demanding supply management.

  
<p align="center">
  <img src="https://github.com/PrashantHangal/Business_Insights_360-PowerBI_Project/blob/main/Supply_chain_view.jpg?raw=true" alt="Home" width="100%" />
</p>


<br/>**<h3>Executive View</h3>** :  Metrics critical for top-level decision-makers

- Developed an executive dashboard for real-time performance monitoring. Shows revenue by division, customers , products and channels.
- Built the Market share % of all manufractures, and estimate of Top 5 customers and products by revenue.

  
<p align="center">
  <img src="https://github.com/PrashantHangal/Business_Insights_360-PowerBI_Project/blob/main/Executive_view.jpg?raw=true" alt="Home" width="100%" />
</p>


**Power BI Features:**

1.Creating calcualted columns and DAX measures

2.Data Modelling ,data validation techniques and using KPI indicators

3.Using bookmarks to switch between two visuals and conditional formatting

4.Page navigation with buttons

5.Using tooltips to save page area

6.Dynamic titles based on the applied filters

7.PowerBI services for publishing and sharing reports online

8.Auto refresh setup for data through gateway











