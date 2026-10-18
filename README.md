# ☕ Coffee Sales Analytics Dashboard

An interactive **Power BI dashboard** for exploring coffee sales performance across time, products, and cities. The report brings key business metrics into one place to support sales monitoring and comparison.

![Coffee Sales Analytics Dashboard](screenshots/coffee-sales-dashboard.png)

> Add a screenshot of your dashboard at `screenshots/coffee-sales-dashboard.png` to display the preview above. If you use a different filename or folder, update the image path.

## 📌 Project Overview

This project analyzes coffee sales data using Microsoft Power BI. It summarizes overall revenue, customer reach, average sales value, order volume, monthly revenue trends, product performance, and city-level results.

## 🎯 Project Objectives

- Monitor headline sales KPIs in a single view.
- Understand how revenue changes over time.
- Identify products contributing the most revenue.
- Compare sales performance across cities.
- Make it easier to explore results using interactive product and city filters.

## 📊 Dashboard Highlights

### Key Performance Indicators

| KPI | Dashboard value | What it indicates |
|---|---:|---|
| Total Revenue | 6M | Overall revenue represented in the report |
| Unique Customers | 497 | Number of distinct customers |
| Average Sale | 584.35 | Average sales value shown on the dashboard |
| Total Orders | 10K | Total order count displayed in the report |

*Values are transcribed from the dashboard screenshot and may be rounded as displayed.*

### Revenue Trend

The monthly revenue line chart shows variation over the period from approximately **January 2023 to October 2024**. Revenue rises noticeably around late 2023, then drops during 2024, with smaller fluctuations afterward. This pattern is worth investigating alongside seasonality, promotions, product availability, and data completeness before drawing business conclusions.

### Product Performance

The product revenue chart highlights **Cold Brew Coffee Pack (6 Bottles)** as the highest-revenue product shown, at approximately **1.15M**. Other leading products visible include Coffee Beans (500g), Coffee Gift Hamper, Ground Espresso Coffee (250g), and Tote Bag with Coffee Design.

### City Performance

The city revenue chart shows **Pune** as the leading city by revenue, followed by **Chennai** and **Bangalore**. The dashboard also includes a city summary table with measures such as total revenue, total orders, and average sale, allowing comparisons across cities.

### Interactive Filters

- **Product Name** slicer to focus on selected products.
- **City Name** slicer to explore selected cities.
- Selecting slicers helps users investigate how the displayed KPIs and charts change for a chosen subset of the data.

## 🔍 Key Findings from the Dashboard

1. The report displays approximately **6M in total revenue** and **10K orders**, indicating the overall scale of sales represented in the dataset.
2. The dashboard shows **497 unique customers** and an **average sale of 584.35**.
3. **Cold Brew Coffee Pack (6 Bottles)** appears to be the strongest product by revenue among the products shown.
4. **Pune** leads the city revenue chart, with **Chennai** and **Bangalore** next.
5. Revenue has a visible peak in late 2023 and is lower through much of 2024 in the displayed trend. Validate the date coverage and business context before treating this as a confirmed underlying business trend.

## 🛠️ Tools & Skills Demonstrated

- **Microsoft Power BI** — dashboard development and data visualization
- **Data analysis** — KPI interpretation and performance comparison
- **Interactive reporting** — slicers and cross-filter exploration
- **Business storytelling** — presenting product, time, and city-level insights

If you used Power Query, DAX, Excel, SQL, or other tools during preparation, add them here only if they were part of your actual workflow.

## 📁 Repository Structure

```text
Coffee-Sales-Analysis-PowerBI/
├── Coffee_PowerBI_project.pbix
├── README.md
└── screenshots/
    └── coffee-sales-dashboard.png
```

The screenshot folder is optional. Adjust the file names above to match the actual files in your repository.

## 🚀 How to View the Project

1. Download `Coffee_PowerBI_project.pbix` from this repository.
2. Open the file using **Microsoft Power BI Desktop**.
3. If prompted, configure the data source or refresh the data as needed.
4. Use the Product Name and City Name slicers to explore the dashboard.

## 💡 Possible Future Improvements

- Add month-over-month and year-over-year growth measures.
- Include profit and margin analysis if those fields are available.
- Add targets and variance indicators to evaluate performance against goals.
- Improve accessibility with clear labels, consistent number formatting, and sufficient contrast.
- Document the data source, refresh process, and metric definitions.

## ⚠️ Notes

- KPI values and findings in this README are based on the supplied dashboard screenshot; they should be verified against the underlying Power BI model before publication.
- Do not publish confidential, personally identifiable, or licensed data without permission.
- A `.pbix` file may include imported data and data-source details. Review it before making the repository public.

## 👤 Author

**Mohd Zainuddin**

Power BI project focused on coffee sales analytics and interactive business reporting.
