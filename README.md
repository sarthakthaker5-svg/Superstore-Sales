<div align="center">

# 📊 Superstore Sales Dashboard

<img src="https://img.shields.io/badge/Power_BI-Data_Visualization-F2C811?style=for-the-badge&logo=powerbi&logoColor=black" alt="Power BI">
<img src="https://img.shields.io/badge/Power_Query-Data_Transformation-2673B8?style=for-the-badge" alt="Power Query">
<img src="https://img.shields.io/badge/Status-Completed-brightgreen?style=for-the-badge" alt="Status: Completed">

<br><br>

*An interactive Power BI report for exploring Superstore sales, profit, products, regions, and order details.*

</div>

---

# 📖 Project Overview

This project analyzes the **Sample Superstore** dataset using Power BI Desktop. I cleaned and transformed the data in Power Query, then created a two-page report with KPI cards, bar charts, slicers, filters, and interactive visuals.

The **Sales Overview** page focuses on Consumer and Corporate customers and uses a page-level Shipping Mode filter. The **Order Details** page provides a detailed transaction table and a chart of the top five sub-categories by sales.

---

# 🎯 Objectives

- Import and explore the Superstore dataset.
- Clean and transform data using Power Query.
- Compare sales and profit across categories and regions.
- Display key figures using KPI cards.
- Explore results with slicers, filters, and visual interactions.
- Present order-level information on a separate report page.

---

# 🛠️ Technologies Used

| Tool | Purpose |
|---|---|
| Power BI Desktop | Report creation and data visualization |
| Power Query | Data cleaning and transformation |
| Sample Superstore dataset | Source data |
| GitHub | Project documentation and version history |

---

# 🗃️ Dataset

| Item | Details |
|---|---|
| Dataset | Sample Superstore |
| Source | [Kaggle: Superstore Dataset](https://www.kaggle.com/datasets/vivek468/superstore-dataset-final) |
| Main fields | Order Date, Shipping Mode, Segment, Region, Category, Sub Category, Sales, Quantity, Discount, Profit |
| Original size | Approximately 9,994 rows |

> The **Sales Overview** page uses additional filters, so its figures differ from the unfiltered totals on the **Order Details** page.

---

# ⚙️ Data Preparation

I used Power Query to:

1. Import the dataset and promote the first row to column headers.
2. Check and correct column data types.
3. Rename columns for readability.
4. Check important fields for missing values and errors.
5. Keep the **Consumer** and **Corporate** segments.
6. Duplicate and split the order identifier to extract its region code.
7. Remove unnecessary columns, including Row ID, Country, and Postal Code.
8. Load the transformed data into Power BI.

The final Power Query contains **10 Applied Steps**.

---

# ✨ Dashboard Features

## 📈 Sales Overview

- Four KPI cards: **Total Sales, Total Profit, Units Sold, and Average Discount**.
- **Sales by Category** and **Profit by Region** bar charts.
- **Region** and **Category** dropdown slicers.
- A page-level filter for **Standard Class** and **Second Class** shipping.
- Cross-filtering between visuals.
- A coordinated dark header, red accents, and a 16:9 report layout.

## 📋 Order Details

- A transaction table with order, customer, product category, sales, and profit information.
- A **Top 5 Sub-Categories by Sales** bar chart.
- A visual-level Top N filter on the chart.
- A dark table style for clear separation from the chart.

---

# 📸 Report Screenshots

Save your final screenshots in a folder named `Screenshots` using these filenames:

| Screenshot | Description |
|---|---|
| `Sales_Overview.png` | KPI cards, slicers, and sales and profit charts |
| `Order_Details.png` | Top 5 chart and detailed order table |
| `Power_Query_Steps.png` | Power Query transformations and Applied Steps |
| `Filters_and_Interactions.png` | Evidence of filters or visual interactions |

## Sales Overview

![Sales Overview dashboard](Screenshots/Sales_Overview.png)

## Order Details

![Order Details report page](Screenshots/Order_Details.png)

## Power Query Transformations

![Power Query Applied Steps](Screenshots/Power_Query_Steps.png)

---

# 📂 Project Structure

```text
Superstore-Sales-Dashboard/
├── Superstore_Sales_PR1.pbix
├── README.md
├── Dataset/
│   └── Superstore_Dataset.csv
└── Screenshots/
    ├── Sales_Overview.png
    ├── Order_Details.png
    ├── Power_Query_Steps.png
    └── Filters_and_Interactions.png
```

> Rename `Superstore_Dataset.csv` in this example if your actual dataset has a different filename. If you include the custom background image in the repository, place it in an `Assets` folder.

---

# 🚀 How to Open the Report

1. Install **Power BI Desktop**.
2. Download or clone this repository.
3. Open `Superstore_Sales_PR1.pbix`.
4. If Power BI cannot find the dataset, open **Transform data → Data source settings** and update the source path to the dataset file on your computer.
5. Select values in the Region or Category slicers to explore the report. Click a chart bar to test cross-filtering.

---

# 🎥 Project Demo Video

**Video link:** [Watch the project demonstration](PASTE_YOUR_VIDEO_LINK_HERE)

The demonstration covers dataset import, Power Query transformations, report pages, formatting, filters, slicers, and visual interactions.

---

# 🎓 Learning Outcomes

Through this project, I practiced:

- Connecting Power BI to a file-based dataset.
- Inspecting and transforming data in Power Query.
- Choosing suitable aggregations for KPI cards.
- Building and formatting bar charts and tables.
- Applying visual-level and page-level filters.
- Creating interactive slicers and cross-filtering.
- Designing a consistent multi-page report.

---

# 👨‍💻 Author

**Sarth Thakar**
