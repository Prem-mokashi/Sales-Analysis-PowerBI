# 📊 Sales Analysis Dashboard - SQL & Power BI

<div align="center">

![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)
![SQL Server](https://img.shields.io/badge/SQL%20Server-CC2927?style=for-the-badge&logo=microsoft-sql-server&logoColor=white)
![T-SQL](https://img.shields.io/badge/T--SQL-316192?style=for-the-badge&logo=microsoft&logoColor=white)

*A comprehensive business intelligence solution for sales data analysis and visualization*

[View Dashboard PDF](Sales%20Report.pdf) • [Download Power BI File](Sales%20Report.pbix)

</div>

---

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

---

## 🎯 Overview

This project demonstrates a complete **end-to-end business intelligence solution** that transforms raw sales data into actionable insights through SQL data cleaning and Power BI visualization. The dashboard provides comprehensive sales analytics including revenue trends, customer segmentation, product performance, and geographical distribution.

### Key Highlights

✨ **Data Transformation** - Clean and prepare data using advanced T-SQL techniques  
📈 **Interactive Dashboards** - Dynamic visualizations with drill-down capabilities  
🎯 **Business-Driven** - Built based on real business requirements and user stories  
🔄 **Scalable Design** - Follows dimensional modeling best practices  

---

## ✨ Features

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

---

## 🛠️ Tech Stack

| Technology | Purpose |
|------------|---------|
| **SQL Server** | Data warehouse and storage |
| **T-SQL** | Data cleaning and transformation |
| **Power BI Desktop** | Dashboard creation and visualization |
| **AdventureWorks DW** | Sample database (2019 version) |
| **DAX** | Calculated measures and KPIs |

---

## 📁 Project Structure

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

---

## 🚀 Getting Started

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

---

## 🗄️ Data Model

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

---

## 📊 Dashboard Components

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

---

## 🔧 SQL Transformations

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

---

## 📋 Business Requirements

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

---

## 🎓 Learning Outcomes

This project demonstrates proficiency in:

- 🗃️ **Data Warehousing** - Understanding dimensional modeling
- 🔍 **SQL Development** - Advanced T-SQL queries and transformations
- 📊 **Data Visualization** - Creating effective business dashboards
- 🎯 **Business Intelligence** - Translating requirements into solutions
- 📈 **DAX** - Creating calculated measures and KPIs
- 🔄 **ETL Processes** - Extract, Transform, Load workflows

---

## 📖 How to Use

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

---

## 🔍 Key Insights

The dashboard reveals:

- 📈 Sales trends and seasonality patterns
- 🏆 Top-performing products and categories
- 👥 High-value customer segments
- 🌍 Geographic sales distribution
- 📊 Budget performance and variances
- 🎯 Areas for improvement and growth

---

## 🤝 Contributing

Suggestions for improvements are welcome! Consider:

- Adding more advanced DAX measures
- Implementing additional visualizations
- Enhancing SQL transformations
- Expanding documentation
- Creating video tutorials

---

## 📄 License

This project uses the AdventureWorks sample database, which is provided by Microsoft for educational purposes.

---

## 🙏 Acknowledgments

- **Microsoft** - For the AdventureWorks sample database
- **Power BI Community** - For visualization inspiration and best practices
- **SQL Server Community** - For T-SQL techniques and optimization tips

---

<div align="center">

### 🌟 If you found this project helpful, please consider giving it a star!

**Built with ❤️ using SQL Server and Power BI**

</div>
