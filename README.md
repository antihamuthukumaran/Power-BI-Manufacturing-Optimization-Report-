# **Power BI Manufacturing Optimization Report - MaxMinManufacturing**

## **Project Overview**

This project aims to develop a **Power BI report** for **MaxMinManufacturing** that helps shift managers understand key metrics related to rejected products. The report uses data from the **MaxMinManufacturingDM** SQL Server database, and the goal is to create insightful visualizations that answer key business questions related to rejection rates, trends, and patterns across plants, machines, and product types.

## **Business Questions to Answer**

The goal of the report is to answer the following business questions:
1. **How many rejected products have been created by each plant? Which country does each plant belong to?**
2. **What is the total number of rejected products that were manufactured each month?**
3. **What proportion of rejected products came from each type of machine?**

![image](https://github.com/user-attachments/assets/11575735-63dc-4664-9da5-3071ae0eb73b)

## **Data Source**

The data is sourced from the **MaxMinManufacturingDM** SQL Server database, which includes tables related to manufacturing operations such as:
- Plants
- Machines
- Products
- Rejected Products
- Manufacturing Dates

## **Steps in the Project**

### **Step 1: Data Model Creation**
- **Data Loading**: Loaded data from the MaxMinManufacturingDM SQL Server database into Power BI Desktop.
- **Data Transformation**: No significant data transformations were necessary; however, data cleaning and preparation were done as needed.
- **Relationships**: Verified and created relationships between tables using Power BI's automatic relationship detection and manual adjustments to ensure accurate data connections.

### **Step 2: Measure Creation**
- Created several **measures** to calculate key metrics such as:
  - **Rejection Rate**: Percentage of rejected products.
  - **Monthly Rejected Products**: Total number of rejected products each month.
  - **Rejected Products by Machine Type**: Breakdown of rejected products by machine type.
  - **Rejection Trend**: Trends of rejected products over time.
  - Additional calculated measures for rejection by plant, product type, machine type, and country.

### **Step 3: Data Visualization**
The following visualizations were created to answer the business questions:
1. **Rejected Products by Plant**: Bar chart showing the total rejected products by each plant.
2. **Rejected Products by Machine Type**: Pie chart displaying the proportion of rejected products by machine type.
3. **Rejected Products Over Time**: Line chart showing the trend of rejected products each month.
4. **Rejection Rate by Plant**: Stacked bar chart comparing rejection rates across different plants.
5. **Proportion of Rejected Products by Product Type**: Pie chart showing rejection distribution by product type.

### **Step 4: Formatting and Design**
- Focused on maximizing the **data-to-ink ratio** to ensure visualizations are clear and easily interpretable.
- Used **color schemes** effectively to enhance understanding while avoiding distractions.
- Optimized chart labels, titles, and tooltips for clarity and precision.

### **Step 5: Drill-through & Interactivity**
- Created **Drill-through** pages for deeper insights:
  - Drill-through functionality enables users to right-click on a visual and get more detailed information based on plant, machine type, or product category.
- Interactive elements were added for users to filter and explore data based on different criteria such as date, product type, or plant.

### **Step 6: Report Optimization**
- Performance optimizations were applied to ensure smooth report navigation, even with large data sets.
- The final report includes interactive features such as **filtering**, **slicing**, and **hover-over tooltips** for a more engaging user experience.

### **Step 7: Report Deployment**
- The Power BI report was published to the **Power BI Service** for sharing with stakeholders, including the shift managers.
- Shared the report link and provided instructions for access.

## **Visualizations and Measures Used**
- **KPI Cards** for metrics like rejection rate.
- **Bar charts** for rejections by plant, machine, and product type.
- **Line charts** for rejection trends over time.
- **Pie charts** to show proportional distribution of rejections across machine types and product types.
- **Heatmaps** for rejection rates across different plants and machine types.

## **Color Scheme and Design Choices**
The following color schemes were used to ensure clarity:
- **Green**: Used for positive trends, such as the total number of products manufactured.
- **Red**: Represented rejected products, indicating areas requiring attention.
- **Blue**: Used for neutral charts and backgrounds, providing a calming contrast to other colors.
- **Gray**: For non-essential data points and background elements, ensuring the focus remains on the key insights.

## **Usage Instructions**

1. Clone the repository.
2. Open the **.pbix** file using **Power BI Desktop**.
3. Explore the interactive report to answer the business questions related to rejected products.
4. Use the filters and drill-through options for a deeper dive into the data.

## **Additional Enhancements (Future Work)**
- Integrate machine performance data to track rejection rates per machine.
- Add more detailed trend analysis, including seasonality.
- Incorporate forecast models to predict future rejection trends based on historical data.

## **Technologies Used**
- **Power BI Desktop** for data modeling and report creation.
- **SQL Server** as the data source.
- **DAX (Data Analysis Expressions)** for creating calculated measures and aggregations.

## **Conclusion**
This project serves as a powerful tool for **MaxMinManufacturing**'s shift managers to identify areas of improvement, optimize production efficiency, and reduce rejected products. Through the effective use of data visualizations and interactive features, stakeholders can gain actionable insights that will help in decision-making.

---

### **License**
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
