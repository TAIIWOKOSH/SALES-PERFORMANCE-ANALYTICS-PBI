# ADVENTURE WORKS SALES PERFORMANCE 2017 - 2021
Summary of the Adventure Works Sales Performance from the year 2017- 2021, which includes, the problems encountered, data collection and preparation, the images, tools used, conclusions, recommendations and calculations.
## 1.	PROBLEMS ENCOUNTERED
### 1.	Data Quality Issues:
. Incomplete and Missing data [ -1 in CustomerKey, ResellerKey, Not Applicable in Reseller ID, Business Type, Reseller, City, State-Province, Country-Region and Postal Code].
. Duplicate records [ ProductKey, SKU duplicates].
### 2.	Limited Insights into Weakness and Threats:
- Lack of actionable insights into external threats [ e.g. competitive pressure,                         market share decline].
- Difficulty in identifying underperformance areas [ e.g. low profit products and declining sales].
## 2.DATA COLLECTION AND PREPARATION
### Data Sources
- Sales Order-Data: It includes, Channel, SalesOrderLineKey, Sales Order,Sales Order Line.
- Sales Territory-Data, this includes details about the geographical locations of the business.
- Sales Data, it includes, order details, customer keys and product keys.
- Reseller Data, this refers to the information about resellers business type and location.
- Date-Data, date dimension table.
- Product-Data, this includes details about the products, e.g. product category and sub-category, SKU, model, cost, colour.
- Customer-Data, this refers to customer location information and customer demographics.

### DATA CLEANING:
- Replaced -1 with [0] and Not Applicable with Unknown to handle incomplete and missing values.

### DATA TRANSFORMATION:
- Power Query was used to clean and transform data before loading it into Power BI.
- Measures were calculated using DAX for KPIs.

## 3. TOOLS USED AND WHY
   - ** POWER QUERY: **
      - Why: It is used for data cleaning, data transformation and preparation before loading it into Power BI.
- ** DAX: **
     - Why: It is used to create calculated measures. [ e.g. Total sales, Profit Margin, Total Order]. Total Sales = SUM (Sales [Sales Amount])
     - '''
               Profit Margin = 
SUM (Sales [Sales Amount]) - SUM(Sales[Total Product Cost])'''  
POWER BI:
     - Why: It is used because it is a powerful business intelligence tool for interactive data visualization.
 

CONCLUSION:
The Adventure Works Sales Performance from 2017- 2021, successfully addressed the company’s need for actionable insights into sales performance, customer behaviour, sales territory and product profitability, by preparing and cleaning the data, creating meaningful visualization as well as implementing interactive features, the dashboard enables stakeholders to make data driven decisions.
Key findings include: 
      Weakness: Low profit margins in the BIKE category and declining market share.
       Threats: Economic downturns and competitive pressure.
       Opportunities: Growth in BIKE accessories.

RECOMMENDATIONS:
. Improve Profit Margins: Maximize production costs and pricing strategies for the BIKE category.
Mitigate Competitive Threats: Implement customer loyalty programs.
. Improve Market Share: Invest in product innovation and targeted marketing campaigns.
Capitalize on Opportunities: Cross-sell bike accessories and expand into emerging markets.

      
