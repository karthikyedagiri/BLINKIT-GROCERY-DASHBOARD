# 🛒 Blinkit Grocery Sales Analysis Dashboard | Power BI

![Power BI](https://img.shields.io/badge/Power%20BI-Dashboard-yellow?logo=powerbi)
![Data Analytics](https://img.shields.io/badge/Domain-Data%20Analytics-blue)
![Status](https://img.shields.io/badge/Project-Completed-success)

## 📌 Project Overview

The **Blinkit Grocery Sales Analysis Dashboard** is an interactive Business Intelligence project developed using Microsoft Power BI. The project focuses on analyzing grocery sales data to understand sales performance, product category contributions, outlet characteristics, and business performance indicators.

The dashboard converts raw data into meaningful visual insights through interactive charts, KPI cards, filters, and slicers. It helps users explore different aspects of grocery sales and supports data-driven decision-making.

This project demonstrates practical skills in data analytics, data visualization, dashboard design, and business reporting.

---

## 🎯 Project Objectives

The main objectives of this project are:

- Analyze overall grocery sales performance.
- Evaluate sales contributions from different product categories.
- Compare sales performance across outlet types and locations.
- Understand how product characteristics relate to sales.
- Explore customer-facing product attributes, where available in the dataset.
- Create an interactive dashboard for business analysis.
- Present complex sales data through clear and meaningful visualizations.
- Support business decisions using data-driven insights.

---

## 🛠️ Tools and Technologies

| Tool / Technology | Purpose |
|---|---|
| Microsoft Power BI | Dashboard creation and interactive reporting |
| Power Query | Data cleaning, transformation, and preparation |
| DAX | Calculated measures and business metrics |
| Data Modeling | Organizing relationships between tables, where applicable |
| Data Visualization | Presenting sales performance through charts and KPIs |
| GitHub | Project version control and portfolio presentation |

---

## 📂 Dataset Overview

The project uses grocery sales data associated with Blinkit. Depending on the dataset provided to the dashboard, the analysis may include the following fields:

- **Item Identifier:** Unique identifier for each product.
- **Item Type:** Product category, such as fruits, snacks, or household items.
- **Item MRP:** Maximum retail price of the product.
- **Item Visibility:** Relative visibility of a product within an outlet.
- **Item Weight:** Product weight, where available.
- **Sales:** Sales amount associated with an item.
- **Outlet Identifier:** Unique identifier for an outlet.
- **Outlet Type:** Classification of the outlet.
- **Outlet Size:** Outlet size category.
- **Outlet Location Type:** Classification based on location.
- **Establishment Year:** Year the outlet was established.
- **Item Fat Content:** Product fat-content classification, where applicable.

*Note: The exact fields and measures depend on the dataset connected to the Power BI template.*

---

## 📊 Dashboard Features and Visualizations

### 1. Key Performance Indicators (KPIs)

KPI cards provide a quick overview of business performance.

Possible metrics include:

- Total Sales
- Average Sales
- Number of Items
- Average Rating

These metrics help users understand overall performance without examining every chart individually.

### 2. Sales by Item Type

A bar chart can compare sales across product categories.

**Business purpose:**
- Identify high-performing product categories.
- Compare category-level sales contributions.
- Understand which product groups may require further investigation.

### 3. Sales by Outlet Type

A chart comparing outlet types helps users evaluate sales distribution across different store formats.

**Business purpose:**
- Compare outlet performance.
- Identify differences between store formats.
- Support outlet-level performance analysis.

### 4. Sales by Outlet Location

A visualization of sales across location tiers can help explore geographic performance differences.

**Business purpose:**
- Compare sales across outlet location categories.
- Identify differences in sales distribution.
- Support location-based business analysis.

### 5. Sales by Item Fat Content

A pie or donut chart can show the contribution of different fat-content categories to sales.

**Business purpose:**
- Compare product segment contributions.
- Understand the distribution of sales across product attributes.
- Explore potential differences between product segments.

### 6. Sales by Outlet Establishment Year

A time-oriented chart can compare outlet sales by establishment year.

**Business purpose:**
- Explore sales distribution across outlet establishment periods.
- Compare outlets established in different years.
- Investigate whether outlet age is associated with differences in sales.

*This visualization should be interpreted as a historical comparison, not as a time-series sales trend, unless the underlying data supports that interpretation.*

### 7. Interactive Filters and Slicers

Slicers allow users to filter the report based on available fields, such as:

- Item Type
- Outlet Type
- Outlet Size
- Outlet Location
- Item Fat Content
- Establishment Year

The available filters depend on the report configuration.

**Business purpose:** Users can narrow the analysis to specific segments and compare results dynamically.

---

## 📈 Business Analysis and Insights

The dashboard can be used to investigate several business questions:

1. Which item categories generate the highest sales?
2. Which outlet types contribute most to total sales?
3. How does sales distribution differ across outlet locations?
4. What share of sales comes from each item segment?
5. How do sales vary across outlet establishment years?
6. How do the KPIs change when different filters are applied?
7. Which product and outlet segments should be investigated further?

### Potential Business Applications

- **Sales Planning:** Understand sales distribution across product categories.
- **Outlet Analysis:** Compare performance across store formats and locations.
- **Product Analysis:** Explore how product attributes relate to sales.
- **Performance Monitoring:** Track key metrics through dashboard KPIs.
- **Decision Support:** Use interactive reports to investigate business questions.

*Actual findings and rankings should be added after loading the dataset and reviewing the dashboard's results.*

---

## 🔄 Project Workflow

The project follows a typical Power BI analytics workflow:

1. **Data Collection:** Connect the grocery sales dataset.
2. **Data Preparation:** Inspect the data and identify quality issues.
3. **Data Transformation:** Clean and format fields using Power Query, where required.
4. **Data Modeling:** Organize tables and relationships, if applicable.
5. **DAX Calculations:** Create or validate measures for sales and other KPIs.
6. **Dashboard Development:** Build charts, KPI cards, and slicers.
7. **Data Validation:** Verify calculations and check visual consistency.
8. **Business Analysis:** Interpret the results and identify useful findings.
9. **Reporting:** Present the completed dashboard for interactive exploration.

---

## 🧮 DAX Measures

The following are examples of common DAX measures that can be used if the dataset contains the required columns. Adjust table and column names to match your model.

### Total Sales

```dax
Total Sales = SUM('Blinkit Data'[Sales])
```

### Average Sales per Record

```dax
Average Sales = AVERAGE('Blinkit Data'[Sales])
```

### Number of Items

```dax
Number of Items = COUNTROWS('Blinkit Data')
```

### Average Rating

```dax
Average Rating = AVERAGE('Blinkit Data'[Rating])
```

*These are example formulas, not a claim that the template already contains these exact measures. Replace `Blinkit Data`, `Sales`, and `Rating` with your actual model names and columns.*

---

## 🚀 How to Open the Project

### Prerequisites

- Microsoft Power BI Desktop
- The dataset required by the template, if it is not embedded or otherwise available
- Access to any external data sources referenced by the template

### Steps

1. Clone or download this GitHub repository.
2. Open the `.pbit` file using Power BI Desktop.
3. Enter the required data source parameters if prompted.
4. Connect the appropriate dataset.
5. Refresh the data, if necessary.
6. Verify that the visuals and measures load correctly.
7. Use the slicers and filters to explore the dashboard.

### Project File

`BLINKIT GROCERY DASHBOARD.pbit`

**Important:** A `.pbit` file is a Power BI template. It generally contains report definitions, model structure, and query definitions, but it does not package the imported dataset in the same way as a standard `.pbix` report. Additional data-source setup may be required.

---

## 📁 Repository Structure

```text
BLINKIT-GROCERY-DASHBOARD/
│
├── BLINKIT GROCERY DASHBOARD.pbit
├── README.md
└── assets/
    └── dashboard-screenshot.png
```

The `assets` folder and screenshot are optional. Add them if you want to display a preview of the dashboard in your GitHub README.

To display a screenshot, add the following Markdown after uploading the image:

```markdown
## 📸 Dashboard Preview

![Blinkit Grocery Dashboard](assets/dashboard-screenshot.png)
```

---

## 🌟 Skills Demonstrated

- Data Analysis
- Business Intelligence
- Microsoft Power BI
- Power Query
- DAX Fundamentals
- KPI Development
- Interactive Dashboard Design
- Data Visualization
- Business Reporting
- Analytical Thinking

---

## 🔮 Future Enhancements

- Add month-over-month or year-over-year analysis if suitable date fields are available.
- Include additional sales and profitability measures where the data supports them.
- Improve report navigation and drill-through functionality.
- Add more detailed product and outlet comparisons.
- Enhance the dashboard layout and accessibility.
- Publish the report to Power BI Service, if appropriate.
- Document validated findings and recommendations.

---

## 👨‍💻 Author

**Karthik Yedagiri**

Aspiring Data Analyst | Artificial Intelligence & Data Science

**Technical Interests:** Power BI | Python | SQL | Excel | Data Analytics

---

## 🤝 Feedback and Contributions

Suggestions and feedback are welcome. Feel free to explore the repository and share ideas for improving the dashboard.

If you find this project useful, consider giving the repository a ⭐.

---

## 🏷️ Tags

`Power BI` `Blinkit` `Grocery Sales Analysis` `Data Analytics` `Business Intelligence` `Dashboard` `DAX` `Power Query` `Data Visualization`

<img width="1322" height="742" alt="Screenshot 2026-10-25 154116" src="https://github.com/user-attachments/assets/008acf48-275f-46da-a912-b5b306d68ead" />
