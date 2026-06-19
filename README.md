# Top 30 Power BI Interview Questions and Answers

## 1. What is Power BI?

**Answer:** Power BI is a business intelligence and data visualization tool developed by Microsoft that helps users connect to data sources, transform data, create interactive dashboards, and generate reports for decision-making.

---

## 2. What are the main components of Power BI?

**Answer:** The main components are:

* Power BI Desktop
* Power BI Service
* Power BI Mobile
* Power BI Gateway
* Power BI Report Server

---

## 3. What is Power Query?

**Answer:** Power Query is a data transformation and ETL (Extract, Transform, Load) tool used to clean, transform, and prepare data before loading it into Power BI.

---

## 4. What is DAX?

**Answer:** DAX (Data Analysis Expressions) is a formula language used in Power BI to create calculated columns, measures, and custom calculations.

---

## 5. What is the difference between a Measure and a Calculated Column?

**Answer:**

* **Measure:** Calculated dynamically based on filter context.
* **Calculated Column:** Calculated during data refresh and stored in the model.

---

## 6. What are Power BI Dashboards?

**Answer:** Dashboards are single-page visual displays that combine multiple report visuals to provide a consolidated view of business metrics.

---

## 7. What is a Power BI Report?

**Answer:** A report is a collection of visualizations spread across one or more pages that provide detailed insights into data.

---

## 8. What are Data Sources supported by Power BI?

**Answer:** Power BI supports:

* Excel
* SQL Server
* Oracle
* MySQL
* PostgreSQL
* SharePoint
* Azure
* Google Analytics
* CSV files
* Web APIs

---

## 9. What is Data Modeling in Power BI?

**Answer:** Data modeling is the process of defining relationships between tables to enable efficient analysis and reporting.

---

## 10. What are Relationships in Power BI?

**Answer:** Relationships connect tables using common columns and allow data interaction across multiple tables.

---

## 11. What is Star Schema?

**Answer:** A Star Schema consists of:

* One Fact Table
* Multiple Dimension Tables

It is the recommended data model design in Power BI.

---

## 12. What is a Fact Table?

**Answer:** A fact table contains measurable business data such as sales, revenue, quantity, or transactions.

---

## 13. What is a Dimension Table?

**Answer:** A dimension table contains descriptive information such as customer names, product details, and dates.

---

## 14. What is Power BI Gateway?

**Answer:** Gateway allows secure data transfer between on-premises data sources and Power BI Service.

---

## 15. What is Row-Level Security (RLS)?

**Answer:** RLS restricts data access for specific users based on defined security roles.

---

## 16. What is the difference between Import Mode and DirectQuery?

**Answer:**

| Import Mode             | DirectQuery                       |
| ----------------------- | --------------------------------- |
| Stores data in Power BI | Queries data directly from source |
| Faster performance      | Real-time data                    |
| Limited by dataset size | Depends on source performance     |

---

## 17. What are Filters in Power BI?

**Answer:** Filters help users focus on specific subsets of data.

Types:

* Visual-level Filters
* Page-level Filters
* Report-level Filters

---

## 18. What is a Slicer?

**Answer:** A slicer is a visual filter that allows users to interactively filter report data.

---

## 19. What is Drill Down?

**Answer:** Drill Down allows users to navigate from summarized data to detailed data within a hierarchy.

---

## 20. What is Drill Through?

**Answer:** Drill Through allows users to navigate to a detailed report page based on selected data.

---

## 21. What is a KPI in Power BI?

**Answer:** KPI (Key Performance Indicator) visual tracks business performance against a target value.

---

## 22. What are Bookmarks?

**Answer:** Bookmarks capture the current report view and allow users to create interactive report navigation.

---

## 23. What is a Workspace in Power BI?

**Answer:** A workspace is a collaborative environment where reports, dashboards, and datasets are shared and managed.

---

## 24. What is Power BI Service?

**Answer:** Power BI Service is the cloud-based platform used for publishing, sharing, and collaborating on reports.

---

## 25. What are Aggregations in Power BI?

**Answer:** Aggregations summarize large datasets to improve query performance.

---

## 26. What is Incremental Refresh?

**Answer:** Incremental Refresh updates only newly added or modified data instead of refreshing the entire dataset.

---

## 27. What is the Difference Between SUM and SUMX?

**Answer:**

* **SUM:** Adds values from a column.
* **SUMX:** Evaluates an expression for each row and then sums the results.

Example:

```DAX
Total Sales = SUM(Sales[Amount])

Total Revenue = SUMX(Sales, Sales[Quantity] * Sales[Price])
```

---

## 28. What is a Data Gateway Cluster?

**Answer:** A Gateway Cluster consists of multiple gateways working together to provide high availability and load balancing.

---

## 29. What are Custom Visuals in Power BI?

**Answer:** Custom visuals are specialized charts and visualizations developed by Microsoft or third parties and imported into Power BI.

---

## 30. Why is Power BI Popular?

**Answer:** Power BI is popular because it offers:

* Easy-to-use interface
* Strong data visualization capabilities
* Integration with Microsoft products
* Real-time analytics
* Advanced DAX calculations
* Cost-effective BI solution
* Cloud and on-premises support

