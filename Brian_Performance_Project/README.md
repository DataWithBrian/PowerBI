****Brian Performance Report – Power BI****

_**Dynamic Power BI dashboard with SWITCH logic, virtual tables, and drill-downs for KPI tracking and profitability segmentation**_

📖 _**Overview**_

The Brian Performance Report is a dynamic Power BI dashboard built to analyze performance across Sales, Gross Profit, and Quantity.

Users can:

- Select either 2023 or 2024 to compare year-to-date performance.

- Switch between multiple perspectives (Sales, GP, Quantity) dynamically.

- Drill down from Month → Country → Product for deeper analysis.

- Segment accounts into quadrants to highlight champions, risks, and growth opportunities.

✨ Key Features

- Dynamic KPI Tracking: YTD, PYTD, YTD vs PYTD variance, and GP%, all slicer-driven.

- Dynamic Scatter Plot: GP% vs Sales, Gross Profit, or Quantity, with quadrant segmentation.

- Context-Aware Drill-Downs: YTD vs PYTD chart allows Month → Country → Product analysis, adapting to the metric selected.

- Virtual Tables + SWITCH Logic: One set of visuals serves multiple perspectives without duplication.

- Dynamic Titles: Auto-update with Year + Metric selections (e.g., “YTD Sales – 2023”).

- Conditional Formatting: KPI variances show green (positive) or red (negative).

- Scatter Enhancements: Average lines, zoom slider, and outlier detection for clarity.

🛠 Technical Implementation

- Virtual Date Table: Powers YTD, PYTD, and variance calculations.

- Virtual Values Table: (Sales, GP, Quantity) drives metric selection.

- SWITCH Measures: Provide dynamic YTD, PYTD, variance, and GP% values.

- Dynamic Titles: Context-aware chart titles based on slicers.

- Conditional Formatting: Variance indicators for quick performance interpretation.

- Drill-Downs: Hierarchy (Month → Country → Product) that dynamically adapts to the chosen metric.

👉 Highlight: By combining SWITCH logic with virtual tables, one set of visuals serves multiple analytical perspectives (Sales, GP, Quantity), without duplicating charts or measures.

💡 What I Learned

This project helped me grow in three areas:

_Advanced DAX & Modeling:_

- Built virtual tables for Dates and Values.

- Applied SWITCH to create dynamic KPIs.

- Learned to keep the model clean and scalable.

_Dynamic Dashboard Design:_

-Created slicer-driven dynamic titles.

- Built context-aware drill-downs (Month → Country → Product).

- Applied conditional formatting for intuitive KPIs.

_Actionable Data Storytelling:_

- Enhanced scatter plots with averages, zoom sliders, and outlier detection.

- Practiced account segmentation into quadrants.

- Learned to convert insights into business recommendations.

📊 **_Insights (2024 Example)_**

- YTD Sales = 3.57M vs PYTD = 3.71M → decline of 135.9K, though GP% stayed at ~39.1%.

- Canada & Colombia showed the steepest declines.

- April recorded the sharpest monthly drop.

_Quadrant Segmentation:_

- High Sales – High GP% → champions (retain & replicate).

- High Sales – Low GP% → margin drainers (fix margins).

- Low Sales – High GP% → hidden gems (profitable growth).

- Low Sales – Low GP% → limited value (deprioritize/restructure).

- Outliers: Highlighted benchmark accounts (profitable leaders) and margin risks (high sales but thin GP%).

🎯 _**Recommendations**_

- Scale Low Sales – High GP% accounts.

- Fix High Sales – Low GP% accounts through pricing/cost changes.

- Deprioritize Low Sales – Low GP% accounts unless turnaround potential exists.

- Benchmark High Sales – High GP% accounts.

- Investigate Canada, Colombia, and the April dip.

🎥 _**Demo Walkthrough**_

Here’s how a business leader might use the report:

- Set Context: Select 2024 and Sales → visuals update to “YTD Sales – 2024”.

- Check KPIs: Sales down 135.9K vs PYTD (red variance).

_Drill Down:_

- Month view → April is the weakest.

- Country → Canada & Colombia underperform.

- Product → see specific weak categories.

- Switch Metric: Change slicer to Gross Profit → scatter shows GP% vs GP.

- Zoom & Outliers: Inspect margin-draining vs hidden gem accounts.

👉 In just a few clicks, leaders move from a yearly overview to granular product insights.

🔧 _**Quick Start**_

- Open Plant_Performance Report.pbix in Power BI Desktop.

- Use the Year slicer (2023/2024) and Values slicer (Sales, GP, Quantity).

- Drill into YTD vs PYTD chart: Month → Country → Product.

🧰 _**Skills Demonstrated**_

- Power BI Dashboard Design

- DAX (SWITCH, Virtual Tables, Time Intelligence, Dynamic Titles)

- Drill-Down Hierarchies (Month → Country → Product)

- KPI Tracking with Conditional Formatting

- Scatter Segmentation & Outlier Analysis

- Business Insights & Data Storytelling

With this simple yet powerful visual, decision-makers can instantly see which accounts to grow, which to fix, and which to let go — turning raw performance data into a clear roadmap for action.
