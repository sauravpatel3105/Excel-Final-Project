# PR. Final Project: Data Intelligence Dashboard

## 📊 Project Overview

This project delivers a comprehensive **Data Intelligence Dashboard** built using advanced spreadsheet software (e.g., Microsoft Excel).

The core objective was to take a raw dataset of customer transactions, perform a thorough analysis, and transform the insights into a dynamic, interactive dashboard for easy consumption.

### **Key Goal**
To provide a reliable, self-service reporting solution that enables stakeholders to monitor key business performance indicators (KPIs) and conduct strategic analysis, such as scenario planning.

***

## ⚙️ Project Structure and Deliverables

The final workbook is meticulously organized into multiple sheets (tabs) to ensure clarity, efficiency, and adherence to best practices:

| Sheet Name | Purpose | Key Content & Role |
| :--- | :--- | :--- |
| **`Final Project Dataset`** | **Raw Data Source.** Contains the original 200+ customer transaction records. | Includes calculated fields like `Timestamp`, `Date_Different`, and `Abbreviations`. |
| **`Dashboard`** | **Final Presentation View.** The interactive summary dashboard. | Hosts Pivot Charts, Slicers, a Timeline, and visually formatted KPI Indicators. |
| **`Category`, `Region`, `Date`** | **Analysis & Pivot Data.** Sheets containing the aggregated data used to power the dashboard charts. | Summary data for Regional Sales, Sales by Product Category, and Time-Series Trends. |
| **`Top 5 customer`** | **Key Insight.** A list identifying and ranking High-Value Customers. | Customer names ranked by their total revenue contribution. |
| **`Linear Regression`** | **Statistical Analysis.** Output from the Data Analysis Toolpak. | Provides core statistical metrics: Multiple R, R-Square, and regression Coefficients. |
| **`Scenario Summary`** | **What-If Analysis.** Summary report of different modeled business scenarios. | Displays the results of the 'Current Values,' 'High Sales,' and 'Low Sales' scenarios. |

***

## ✨ Key Topics Covered & Features Implemented

This project successfully implements all the advanced analysis and Excel functionality required:

### **Advanced Analysis & Modeling**
* **Linear Regression:** Executed using the Data Analysis Toolpak to find statistical relationships within the data.
* **WHAT-IF Analysis:** Utilized **Scenario Manager** for effective planning and modeling different business outcomes.
* **High-Value Customer Identification:** Employed GroupBy concepts and formulas to accurately rank and identify top revenue-generating customers.

### **Dashboard Interactivity & Visualization**
* **Dynamic Filtering:** Incorporated **Slicers** and a **Timeline** to allow users to instantly filter all charts and metrics by any dimension (e.g., Region, Segment, Date).
* **Visual Reporting:** Designed and connected essential **Pivot Charts** (Bar, Line, Pie) for key metrics.
* **KPI Indicators:** Applied **Conditional Formatting with Icons/Arrows** to provide clear, visual status signals for performance metrics.

### **Formula and Data Manipulation**
* **Date & Time Functions:** Successfully implemented `DATEDIF`, `NOW` for customer loyalty and timestamp calculations.
* **Modern Functions:** Used the `FILTER` function for dynamic multi-value data extraction.
* **Text Functions:** Applied `TEXT` functions to create customer abbreviations, demonstrating data preparation skills.

***

## 🧑‍💻 How to Use the Dashboard

The dashboard is built for a self-service user experience:

1.  **Open the Workbook:** Start by opening the main Excel file (`PR. Final Project.xlsx`).
2.  **Navigate to the `Dashboard` Sheet:** This is the primary view for analysis.
3.  **Use Interactive Filters:** Click on the **Slicers** (buttons) or drag the **Timeline** control to apply instant filters. All charts and KPIs will update dynamically based on your selection.
4.  **Review Insights:** The summary panel provides immediate access to the main KPIs (Total Revenue) and insights (Top Customers, Regional Sales).
5.  **Explore Scenarios:** Check the `Scenario Summary` sheet to see the results of various predicted sales outcomes.