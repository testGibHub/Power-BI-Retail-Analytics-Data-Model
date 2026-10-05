# Power BI Retail Analytics – Data Modelling Project
Power BI retail analytics project demonstrating data modelling, DAX, fact and dimension tables, sales, inventory, customer and marketing analysis.


## 📊 Project Overview

This project demonstrates the development of a structured Power BI data model for analysing retail business performance across sales, customers, products, inventory, marketing campaigns, order processing and sales targets.

The objective of the project was to transform multiple business datasets into a well-organised analytical model that can support reliable reporting, KPI calculations and interactive Power BI dashboards.

The project focuses particularly on **data modelling, table relationships, fact and dimension table design, DAX measures and business reporting**.

---

## 🎯 Project Objectives

The main objectives of this project were to:

- Build a scalable Power BI data model using fact and dimension tables.
- Establish relationships between multiple business datasets.
- Create reusable DAX measures for key business KPIs.
- Analyse sales and order performance.
- Compare actual sales against business targets.
- Support customer and product-level analysis.
- Incorporate inventory and marketing data into the analytical model.
- Create a model that can support future interactive dashboards and business reporting.

---

## 🗂️ Data Model

The Power BI model contains multiple fact and dimension tables.

### Fact Tables

**fact_sales**

Contains transactional sales information and acts as one of the core fact tables in the model.

**fact_inventory**

Contains inventory-related information used to analyse stock and product availability.

**fact_sales_target**

Stores sales targets that can be compared with actual sales performance.

**fact_campaign_spend**

Contains marketing campaign expenditure information.

**fact_promotion_coverage**

Supports analysis of promotional activity and product/customer coverage.

**fact_order_process**

Contains information related to the order process and operational performance.

---

### Dimension Tables

**dim_customer**

Contains customer-related attributes and supports customer-level analysis.

**dim_product**

Contains product information used to analyse sales and performance across products.

**dim_date**

Provides the date dimension required for time-based analysis such as:

- Year
- Quarter
- Month
- Day

**dim_geo**

Contains geographical information for location-based analysis.

**dim_campaign**

Contains descriptive information relating to marketing campaigns.

**dim_order_flags**

Contains order-related classifications and flags used for analysing order behaviour.

---

### Additional Tables

**_measures**

A dedicated measures table is used to organise DAX measures separately from transactional tables. This improves model organisation and makes the semantic model easier to maintain.

**security**

A security-related table is included in the model to support controlled data access and model security requirements.

---

## 🔗 Data Modelling Approach

The project uses a fact-and-dimension modelling approach.

Dimension tables provide descriptive business information such as customers, products, dates, geography and campaigns, while fact tables contain measurable business events such as sales, inventory, targets and campaign spending.

This structure helps:

- Reduce unnecessary duplication
- Improve model readability
- Simplify DAX calculations
- Support consistent filtering
- Improve report scalability
- Make business reporting easier to maintain

---

## 📐 DAX Measures

A dedicated measures table was created to organise business calculations.

Examples of measures used in the model include:

### Total Sales

Used to calculate overall sales revenue.

### Total Orders

Used to calculate the total number of orders.

These measures can be reused across cards, tables, charts and other Power BI visuals while responding dynamically to filter context.

---

## 📈 Analysis Supported by the Model

The model can support analysis across several areas of the business, including:

### Sales Analysis
- Total sales
- Sales trends over time
- Product performance
- Customer sales performance

### Target Analysis
- Actual sales vs target revenue
- Performance against business targets
- Time-based target tracking

### Customer Analysis
- Customer purchasing behaviour
- Customer contribution to sales
- Customer segmentation opportunities

### Product Analysis
- Product-level sales
- Product performance
- Inventory analysis

### Inventory Analysis
- Inventory units
- Stock-level analysis
- Product availability

### Marketing Analysis
- Campaign spending
- Campaign performance
- Promotional coverage

### Order Analysis
- Total orders
- Order-processing performance
- Order classifications and flags

---

## 🛠️ Tools & Technologies

- **Microsoft Power BI Desktop**
- **Power Query**
- **DAX**
- **Data Modelling**
- **Star Schema / Fact & Dimension Modelling**
- **Data Visualisation**
- **Business Intelligence**

---

## 💡 Skills Demonstrated

This project demonstrates practical experience in:

- Power BI data modelling
- Fact and dimension table design
- Table relationships
- Data transformation
- DAX measure creation
- KPI development
- Time-based analysis
- Business intelligence reporting
- Data visualisation
- Analytical thinking
- Translating business data into reporting structures

## 📸 Data Model
images/data_model.png


## 📊 Dashboard Preview
images/dashboard.png

## 🚀 Future Improvements

Future development of the project could include:

- Additional DAX KPIs
- Sales growth and YoY analysis
- Customer segmentation
- Product profitability analysis
- Campaign ROI analysis
- Inventory performance KPIs
- Drill-through report pages
- Interactive tooltips
- Enhanced dashboard design
- Row-level security
- Power BI Service deployment

---

## 📌 Key Learning

This project helped strengthen my understanding of how different business datasets can be transformed into a structured Power BI semantic model.

A key focus was understanding the difference between transactional fact tables and descriptive dimension tables and designing relationships that allow multiple business areas to be analysed within the same Power BI model.

The project also improved my practical understanding of DAX measures, filter context and building reusable calculations for business reporting.

---

## 👤 Author

**Gayatri Addala**

Aspiring Data Analyst | Power BI | SQL | Excel 

This project forms part of my data analytics portfolio demonstrating practical Power BI and business intelligence skills.
