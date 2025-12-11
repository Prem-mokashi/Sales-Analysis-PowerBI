# 📊 Sales Analysis Dashboard - SQL & Power BI

<div align="center">

<img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&size=32&duration=2800&pause=2000&color=F2C811&center=true&vCenter=true&width=940&lines=Sales+Analysis+Dashboard+%F0%9F%93%8A;SQL+%2B+Power+BI+%2B+Business+Intelligence;Transform+Data+into+Insights+%F0%9F%9A%80" alt="Typing SVG" />

![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)
![SQL Server](https://img.shields.io/badge/SQL%20Server-CC2927?style=for-the-badge&logo=microsoft-sql-server&logoColor=white)
![T-SQL](https://img.shields.io/badge/T--SQL-316192?style=for-the-badge&logo=microsoft&logoColor=white)
![Status](https://img.shields.io/badge/Status-Active-success?style=for-the-badge)
![License](https://img.shields.io/badge/License-Educational-blue?style=for-the-badge)

<img src="https://user-images.githubusercontent.com/74038190/212284100-561aa473-3905-4a80-b561-0d28506553ee.gif" width="700">

*A comprehensive business intelligence solution for sales data analysis and visualization*

[View Dashboard PDF](Sales%20Report.pdf) • [Download Power BI File](Sales%20Report.pbix)

</div>

<img src="https://user-images.githubusercontent.com/74038190/212284115-f47e185f-9a22-4ff6-b8c3-c5e3c7e5f5e5.gif" width="1000">

## 📋 Table of Contents

- [Overview](#-overview)
- [Features](#-features)
- [Tech Stack](#-tech-stack)
- [Project Structure](#-project-structure)
- [Getting Started](#-getting-started)
- [Data Model](#-data-model)
- [Dashboard Components](#-dashboard-components)
- [SQL Transformations](#-sql-transformations)
- [Business Requirements](#-business-requirements)

<img src="https://user-images.githubusercontent.com/74038190/212284115-f47e185f-9a22-4ff6-b8c3-c5e3c7e5f5e5.gif" width="1000">

## 🎯 Overview

<img align="right" alt="Analytics" width="400" src="https://user-images.githubusercontent.com/74038190/229223263-cf2e4b07-2615-4f87-9c38-e37600f8381a.gif">

This project demonstrates a complete **end-to-end business intelligence solution** that transforms raw sales data into actionable insights through SQL data cleaning and Power BI visualization. The dashboard provides comprehensive sales analytics including revenue trends, customer segmentation, product performance, and geographical distribution.

### Key Highlights

✨ **Data Transformation** - Clean and prepare data using advanced T-SQL techniques  
📈 **Interactive Dashboards** - Dynamic visualizations with drill-down capabilities  
🎯 **Business-Driven** - Built based on real business requirements and user stories  
🔄 **Scalable Design** - Follows dimensional modeling best practices  

<img src="https://user-images.githubusercontent.com/74038190/212284115-f47e185f-9a22-4ff6-b8c3-c5e3c7e5f5e5.gif" width="1000">

## ✨ Features

<p align="center">
  <img src="https://user-images.githubusercontent.com/74038190/221352995-5ac18bdf-1a19-4f99-bbb6-77559b220470.gif" width="400">
</p>

### 📊 Analytics Capabilities

- 💰 **Sales Performance Tracking** - Monitor revenue trends over time
- 👥 **Customer Analysis** - Identify top customers and buying patterns
- 🏆 **Product Insights** - Track best-selling products and categories
- 🌍 **Geographic Distribution** - Visualize sales by location
- 📅 **Time Intelligence** - Year-over-year and period comparisons
- 🎯 **Budget vs Actual** - Compare performance against targets
- 📈 **Top 10 Rankings** - Identify top performers across dimensions

### 🎨 Dashboard Features

- Interactive filters and slicers
- Drill-through capabilities
- Custom visualizations
- Responsive design
- Real-time data refresh
- Export functionality

<img src="https://user-images.githubusercontent.com/74038190/212284115-f47e185f-9a22-4ff6-b8c3-c5e3c7e5f5e5.gif" width="1000">

## 🛠️ Tech Stack

<p align="center">
  <img src="https://user-images.githubusercontent.com/74038190/212257454-16e3712e-945a-4ca2-b238-408ad0bf87e6.gif" width="100">
  <img src="https://user-images.githubusercontent.com/74038190/212257472-08e52665-c503-4bd9-aa20-f5a4dae769b5.gif" width="100">
  <img src="https://user-images.githubusercontent.com/74038190/212257468-1e9a91f1-b626-4baa-b15d-5c385dfa7ed2.gif" width="100">
</p>

| Technology | Purpose |
|------------|---------|
| **SQL Server** | Data warehouse and storage |
| **T-SQL** | Data cleaning and transformation |
| **Power BI Desktop** | Dashboard creation and visualization |
| **AdventureWorks DW** | Sample database (2019 version) |
| **DAX** | Calculated measures and KPIs |

<img src="https://user-images.githubusercontent.com/74038190/212284115-f47e185f-9a22-4ff6-b8c3-c5e3c7e5f5e5.gif" width="1000">

## 📁 Project Structure

<img align="right" alt="Coding" width="350" src="https://user-images.githubusercontent.com/74038190/229223156-0cbdaba9-3128-4d8e-8719-b6b4cf741b67.gif">

```
SalesAnalysis_SQL_PowerBI/
│
├── 📄 SQL Scripts
│   ├── DIM_Calendar_Clean.sql          # Date dimension transformation
│   ├── DIM_Customer_Clean.sql          # Customer dimension cleaning
│   ├── DIM_Product_Clean.sql           # Product dimension preparation
│   └── FACT_InternetSales_Clean.sql    # Sales fact table processing
│
├── 📊 Exported Data
│   ├── DIM_Calendar_Export.csv
│   ├── DIM_Customer_Export.csv
│   ├── DIM_Product_Export.csv
│   └── FACT_InternetSales_Export.csv
│
├── 📈 Power BI Files
│   ├── Sales Report.pbix               # Interactive dashboard
│   └── Sales Report.pdf                # Dashboard screenshot
│
├── 📋 Documentation
│   ├── Business Demand Overview & User Stories.docx
│   ├── Example Business Request.docx
│   └── README.md
│
└── 📊 Additional Data
    └── Sent Over Data - SalesBudget.xlsx
```

<img src="https://user-images.githubusercontent.com/74038190/212284115-f47e185f-9a22-4ff6-b8c3-c5e3c7e5f5e5.gif" width="1000">

## 🚀 Getting Started

<p align="center">
  <img src="https://user-images.githubusercontent.com/74038190/212748830-4c709398-a386-4761-84d7-9e10b98fbe6e.gif" width="500">
</p>

### Prerequisites

Before you begin, ensure you have the following installed:

- ✅ **SQL Server** (Express or higher)
- ✅ **SQL Server Management Studio (SSMS)**
- ✅ **Power BI Desktop** (latest version)
- ✅ **AdventureWorksDW2019** database

### Installation Steps

#### 1️⃣ Setup Database

```sql
-- Download and restore AdventureWorksDW2019 database
-- Follow Microsoft's official documentation for database restoration
```

📚 **Database Setup Guide**: [Microsoft SQL Server Samples](https://docs.microsoft.com/en-us/sql/samples/adventureworks-install-configure)

#### 2️⃣ Update Data Warehouse

```sql
-- Run the update script to refresh data to current dates
-- This ensures the data is relevant for analysis
```

💡 **Tip**: Update the data warehouse to include recent dates for meaningful analysis

#### 3️⃣ Execute SQL Scripts

Run the cleaning scripts in the following order:

1. `DIM_Calendar_Clean.sql` - Creates date dimension
2. `DIM_Customer_Clean.sql` - Prepares customer data
3. `DIM_Product_Clean.sql` - Cleans product information
4. `FACT_InternetSales_Clean.sql` - Processes sales transactions

#### 4️⃣ Load Data into Power BI

1. Open Power BI Desktop
2. Import the CSV files or connect directly to SQL Server
3. Configure relationships in the data model
4. Import the budget data from Excel
5. Create calculated measures using DAX

#### 5️⃣ Build Dashboard

Follow the dashboard design steps:
- Organize tables and relationships
- Create calculation measures
- Design visualizations
- Apply formatting and themes
- Test interactivity

<img src="https://user-images.githubusercontent.com/74038190/212284115-f47e185f-9a22-4ff6-b8c3-c5e3c7e5f5e5.gif" width="1000">

## 🗄️ Data Model

<p align="center">
  <img src="https://user-images.githubusercontent.com/74038190/212749447-bfb7e725-6987-49d9-ae85-2015e3e7cc41.gif" width="400">
</p>

### Star Schema Architecture

```
                    ┌─────────────────┐
                    │  DIM_Calendar   │
                    │  (Date Table)   │
                    └────────┬────────┘
                             │
                             │
    ┌─────────────┐    ┌────┴─────────┐    ┌──────────────┐
    │DIM_Customer │────│ FACT_Internet│────│ DIM_Product  │
    │             │    │    Sales     │    │              │
    └─────────────┘    │  (Fact Table)│    └──────────────┘
                       └──────────────┘
                             │
                             │
                    ┌────────┴────────┐
                    │  FACT_Budget    │
                    │                 │
                    └─────────────────┘
```

### Dimension Tables

#### 📅 DIM_Calendar
- Date keys and hierarchies
- Day, Month, Quarter, Year
- Fiscal and calendar periods
- Filtered for 2019 onwards

#### 👤 DIM_Customer
- Customer demographics
- Full name (combined)
- Gender (decoded)
- City (joined from geography)
- First purchase date

#### 📦 DIM_Product
- Product details
- Category and subcategory
- Color, size, and line
- Product status
- Descriptions

### Fact Tables

#### 💵 FACT_InternetSales
- Sales transactions
- Order information
- Sales amounts
- Date keys (order, due, ship)
- Last 2 years of data

<img src="https://user-images.githubusercontent.com/74038190/212284115-f47e185f-9a22-4ff6-b8c3-c5e3c7e5f5e5.gif" width="1000">

## 📊 Dashboard Components

<p align="center">
  <img src="https://user-images.githubusercontent.com/74038190/225813708-98b745f2-7d22-48cf-9150-083f1b00d6c9.gif" width="500">
</p>

### Main Visualizations

| Visual Type | Purpose | Key Metrics |
|-------------|---------|-------------|
| 🥧 **Pie Chart** | Category distribution | Sales by product category |
| 📈 **Line Chart** | Trend analysis | Sales over time |
| 📊 **Bar Charts** | Comparisons | Products, customers, regions |
| 🗺️ **Map** | Geographic analysis | Sales by location |
| 🏆 **Top 10 Lists** | Rankings | Best performers |
| 🎨 **Gradient Bars** | Performance indicators | Visual KPIs |
| 📋 **Pivot Table** | Detailed analysis | Drill-down data |

### Key Performance Indicators (KPIs)

- 💰 Total Sales Revenue
- 📦 Units Sold
- 👥 Customer Count
- 📈 Sales Growth %
- 🎯 Budget Variance
- 💵 Average Order Value

<img src="https://user-images.githubusercontent.com/74038190/212284115-f47e185f-9a22-4ff6-b8c3-c5e3c7e5f5e5.gif" width="1000">

## 🔧 SQL Transformations

<p align="center">
  <img src="https://user-images.githubusercontent.com/74038190/212257465-7ce8d493-cac5-494e-982a-5a9deb852c4b.gif" width="100">
</p>

### Data Cleaning Techniques

#### ✂️ Column Selection
```sql
-- Select only relevant columns for analysis
-- Remove unnecessary multilingual and technical fields
```

#### 🔄 Data Transformation
- **Renaming**: Alias columns for clarity
- **Combining**: Merge first and last names
- **Decoding**: Convert codes to readable values (Gender: M → Male)
- **Handling Nulls**: Use `ISNULL()` for default values
- **Date Filtering**: `WHERE CalendarYear >= 2019`

#### 🔗 Joins
```sql
-- LEFT JOIN to enrich dimension tables
-- Example: Customer + Geography for city information
LEFT JOIN dbo.DimGeography AS g 
  ON g.GeographyKey = c.GeographyKey
```

#### 📝 Advanced Functions
- `CASE()` - Conditional logic
- `LEFT()` - String manipulation
- `ISNULL()` - Null handling
- `YEAR(GETDATE())` - Dynamic date filtering

<img src="https://user-images.githubusercontent.com/74038190/212284115-f47e185f-9a22-4ff6-b8c3-c5e3c7e5f5e5.gif" width="1000">

## 📋 Business Requirements

<img align="right" alt="Business" width="350" src="https://user-images.githubusercontent.com/74038190/216649426-2638f83f-4e91-4e1e-8c0e-6da7e9c6c6e5.gif">

### User Stories

The dashboard was built to address specific business needs:

1. **Sales Manager** 👔
   - Track sales performance over time
   - Compare against budget
   - Identify trends and patterns

2. **Sales Representative** 💼
   - Monitor individual customer performance
   - Identify upsell opportunities
   - Track product preferences

3. **Marketing Team** 📢
   - Analyze customer demographics
   - Identify high-value segments
   - Geographic targeting

### Success Criteria

✅ Real-time sales monitoring  
✅ Historical trend analysis  
✅ Customer segmentation  
✅ Product performance tracking  
✅ Budget variance reporting  
✅ Geographic insights  

<img src="https://user-images.githubusercontent.com/74038190/212284115-f47e185f-9a22-4ff6-b8c3-c5e3c7e5f5e5.gif" width="1000">

## 🎓 Learning Outcomes

<p align="center">
  <img src="https://user-images.githubusercontent.com/74038190/216122041-518ac897-8d92-4c6b-9b3f-ca01dcaf38ee.gif" width="200">
</p>

This project demonstrates proficiency in:

- 🗃️ **Data Warehousing** - Understanding dimensional modeling
- 🔍 **SQL Development** - Advanced T-SQL queries and transformations
- 📊 **Data Visualization** - Creating effective business dashboards
- 🎯 **Business Intelligence** - Translating requirements into solutions
- 📈 **DAX** - Creating calculated measures and KPIs
- 🔄 **ETL Processes** - Extract, Transform, Load workflows

<img src="https://user-images.githubusercontent.com/74038190/212284115-f47e185f-9a22-4ff6-b8c3-c5e3c7e5f5e5.gif" width="1000">

## 📖 How to Use

<p align="center">
  <img src="https://user-images.githubusercontent.com/74038190/212749695-a6817c5a-a794-462b-afca-1b5ce7dd5e63.gif" width="400">
</p>

### Viewing the Dashboard

1. **Interactive Mode** 🖱️
   - Download `Sales Report.pbix`
   - Open in Power BI Desktop
   - Interact with filters and visuals

2. **Quick Preview** 👀
   - Open `Sales Report.pdf`
   - View static dashboard screenshots

### Customizing the Analysis

- Modify SQL scripts to include additional columns
- Adjust date ranges in WHERE clauses
- Add new calculated measures in Power BI
- Create additional visualizations
- Apply custom themes and branding

<img src="https://user-images.githubusercontent.com/74038190/212284115-f47e185f-9a22-4ff6-b8c3-c5e3c7e5f5e5.gif" width="1000">

## 🔍 Key Insights

<p align="center">
  <img src="https://user-images.githubusercontent.com/74038190/212284087-bbe7e430-757e-4901-90bf-4cd2ce3e1852.gif" width="100">
</p>

The dashboard reveals:

- 📈 Sales trends and seasonality patterns
- 🏆 Top-performing products and categories
- 👥 High-value customer segments
- 🌍 Geographic sales distribution
- 📊 Budget performance and variances
- 🎯 Areas for improvement and growth

<img src="https://user-images.githubusercontent.com/74038190/212284115-f47e185f-9a22-4ff6-b8c3-c5e3c7e5f5e5.gif" width="1000">

## 🤝 Contributing

<p align="center">
  <img src="https://user-images.githubusercontent.com/74038190/216644497-1951db19-8f3d-4e44-ac08-8e9d7e0d94a7.gif" width="200">
</p>

Suggestions for improvements are welcome! Consider:

- Adding more advanced DAX measures
- Implementing additional visualizations
- Enhancing SQL transformations
- Expanding documentation
- Creating video tutorials

<img src="https://user-images.githubusercontent.com/74038190/212284115-f47e185f-9a22-4ff6-b8c3-c5e3c7e5f5e5.gif" width="1000">

## 📄 License

This project uses the AdventureWorks sample database, which is provided by Microsoft for educational purposes.

<img src="https://user-images.githubusercontent.com/74038190/212284115-f47e185f-9a22-4ff6-b8c3-c5e3c7e5f5e5.gif" width="1000">

## 🙏 Acknowledgments

<p align="center">
  <img src="https://user-images.githubusercontent.com/74038190/216120974-24a76b31-7f39-41f1-a38f-b3c1377cc612.gif" width="200">
</p>

- **Microsoft** - For the AdventureWorks sample database
- **Power BI Community** - For visualization inspiration and best practices
- **SQL Server Community** - For T-SQL techniques and optimization tips

<img src="https://user-images.githubusercontent.com/74038190/212284115-f47e185f-9a22-4ff6-b8c3-c5e3c7e5f5e5.gif" width="1000">

<div align="center">

<img src="https://user-images.githubusercontent.com/74038190/216644507-4f06ea29-bf55-4356-aac0-d42751461a9d.gif" width="100">

### 🌟 If you found this project helpful, please consider giving it a star!

<img src="https://user-images.githubusercontent.com/74038190/212284158-e840e285-664b-44d7-b79b-e264b5e54825.gif" width="400">

**Built with ❤️ using SQL Server and Power BI**

<img src="https://user-images.githubusercontent.com/74038190/212284100-561aa473-3905-4a80-b561-0d28506553ee.gif" width="700">

</div>

<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&height=100&section=footer"/>
</div>
