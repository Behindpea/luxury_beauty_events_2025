# 💎 Luxury Cosmetics Pop-Up Event Success Drivers Analysis

## 📝 Overview
This project analyzes the performance of a global portfolio of luxury cosmetics pop-up events to identify key drivers of success and deliver actionable, data-driven strategy recommendations to optimize future event rollouts.

The analysis follows the six steps of the data analysis process: Ask, Prepare, Process, Analyze, Share, and Act.

## 🎯 Business Task
The primary objective was to answer the Head of Marketing's core business question: "What are the key drivers of a successful pop-up event in terms of revenue maximization and inventory efficiency?"

The analysis focused on measuring the impact of five main variables:

* Brand Performance (Revenue & Units Sold)

* Location (Region, City, and Location Type)

* Event Strategy (Event Type vs. Sell-Through Rate)

* Efficiency (Lease Length vs. Daily Revenue)

* Seasonal Trends (Quarterly/Monthly Performance)

## 📊 Data Source

The analysis uses the dataset [Luxury Cosmetics Popup Events 2025](https://www.kaggle.com/datasets/pratyushpuri/luxury-beauty-cosmetics-popup-events-kpi-2025), a public dataset available on Kaggle.

Scope: global pop-up events across multiple luxury beauty brands, including 2133 records. 

## 🛠️ Methodology and Tools

**Tools**
* SQL (Google BigQuery): Used for data ingestion, cleaning, transformation, and analytical querying.

* Tableau: Used for data visualization and building the final interactive dashboard.

**Key Processing Steps (SQL)**
1. Data Cleaning: Handled missing values (e.g., filled `city` nulls with 'Unknown') and filtered incomplete event data.
2. Feature Engineering: Created essential analytical columns:

  - `total_revenue` (calculated from `price_usd * units_sold`).

  - `start_quarter` and `start_month` (for seasonal analysis).

More details in [Luxury_beauty_events_2025.md](https://github.com/Behindpea/luxury_beauty_events_2025/blob/main/Luxury_beauty_events_2025.md) file.

## 💡 Key Findings
![](dashboard.png)
* Top 5 brands by total revenue include: YSL Beauty, Estée Lauder, Sisley-Paris, Hourglass, and Chanel.
* Location types impact
    - sales based on order: High Street, Airport Duty-Free, Art/Design District, Department Store Atrium, Luxury Mall.
    - footfall based on order: High Street, Airport Duty-Free, Luxury Mall, Department Store Atrium, Art/Design District.
* Flash Events are your most effective event type, outperforming all others—including Mobile Pop-Up Trucks, Standalone Pop-Ups, Mall Kiosks, and Shop-in-Shops—in terms of both total revenue and average sell-through. The listed event types follow a strict descending order of effectiveness across both metrics.
* The medium lease duration (31-90 days) has a greater average units sold `1953` than the short lease duration (1-30 days) `1892`.
* The second quarter has the greatest total revenue, and the fourth quarter has the least revenue in the year 2025.

## 📈 Actionable Recommendations
Based on the analysis, the following recommendations are provided to the Head of Marketing:

* **Prioritize High-Efficiency Locations**: Given the superior efficiency, we should allocate 15% of the 2026 pop-up budget to High Street locations, specifically targeting high-traffic streets in Europe and Latin America, to ensure inventory is precisely matched to concentrated demand.
* **Duration and Timing Recommendation**: We should mandate a maximum lease length of 90 days for all future standalone pop-ups. Furthermore, shift the launch date for high-value brands like YSL Beauty, Estée Lauder to Quarter 2 to align with peak demand and achieve a 65% projected revenue uplift.
* **Event Format Recommendation**: Expand the use of the Mobile Pop-Up Truck partnership with Givenchy Beauty, Fenty Beauty, or Dior to increase volume, and deploy Flash Events only in high-footfall locations (like high street) to quickly sell through limited-edition or excess stock due to their higher sell-through capacity.
* **Product/SKU Recommendation**: Increase investment and event frequency by 15% in the European and Latin America markets, while placing a 6-month moratorium on new pop-ups in the Asia-Pacific region until a new market study can determine a better strategic fit or product mix.

## 🧑‍💻 Connect me - Giang Nguyen

[GitHub](https://github.com/Behindpea/) | [LinkedIn](https://www.linkedin.com/in/giangnh217/)
