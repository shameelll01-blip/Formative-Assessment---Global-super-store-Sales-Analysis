# Formative-Assessment---Global-super-store-Sales-Analysis
# Global Store Sales Analysis

## Project Overview

This project presents an **interactive sales analysis report** for a global retail store with branches across multiple countries. The analysis is built using the **Global Superstore dataset** and delivered through a **Power BI interactive dashboard**.

The report helps stakeholders understand sales performance, shipping behavior, and geographical trends across **countries, regions, and markets**.

---

## Dataset

* **Source:** Global Superstore Dataset
* **Records:** ~51,000 sales transactions
* **File Used:** `Global Superstore.xlsx`
* **Power BI File:** `global store data sales analysis.pbix`

### Key Fields

* Order ID, Order Date, Ship Date
* Country, Region, Market, State, City
* Category, Sub-Category, Product Name
* Sales, Profit, Quantity, Discount
* Ship Mode, Shipping Cost

---

## Data Cleaning Steps

The following basic data cleaning operations were performed:

* Removed duplicate records
* Converted Order Date and Ship Date to datetime format
* Ensured numeric consistency for Sales, Profit, and Quantity
* Verified missing values and corrected data types

---

## Dashboard Features

### 1. Interactive Filters (Slicers)

* Country
* Region
* Market

These slicers allow stakeholders to dynamically explore the data.

---

### 2. Shipping Mode Analysis

**Visualization:** Pie Chart
**Metric:** Percentage of Sales by Ship Mode

| Ship Mode      | Sales Contribution |
| -------------- | ------------------ |
| Standard Class | ~60%               |
| Second Class   | ~20%               |
| First Class    | ~14%               |
| Same Day       | ~5%                |

**Insight:** Standard Class shipping dominates global sales, indicating customer preference for cost-effective delivery.

---

### 3. Geographical Sales Analysis

**Visuals Included:**

* Sales by City
* Sales by State
* Sales by Region
* Sales by Market

**Insights Provided:**

* Identification of top-performing regions and markets
* City-level contribution to overall sales
* Regional demand patterns

---

### 4. Data Tables

Each visualization is supported by a detailed table showing:

* Sales values
* Geographic attributes
* Shipping modes

This ensures transparency and enables deeper analysis.

---

## Tools & Technologies

* **Power BI** – Interactive dashboard & visuals
* **Microsoft Excel** – Raw dataset
* **Python (Pandas, Matplotlib)** – Data cleaning & exploratory analysis

---

## Video Explanation

A short video walkthrough accompanies the report and explains:

1. Dataset overview
2. Use of slicers and interactivity
3. Shipping mode sales distribution
4. Geographic sales insights
5. Key business conclusions

---

## Key Business Insights

* Majority of sales are shipped via **Standard Class**
* Certain regions and markets consistently outperform others
* Geographic segmentation reveals high-revenue cities and states

---

## How to Use

1. Open `global store data sales analysis.pbix` in Power BI Desktop
2. Use slicers to filter by Country, Region, or Market
3. Hover over visuals for detailed insights
4. Refer to tables for transaction-level details

---

## Author

Prepared for stakeholder sales performance analysis and business decision-making.

---

## License

This project is intended for **educational and analytical purposes only**.
