# FinanceKPI_Dashboard
Key Fianance KPIs Analytics using POWER BI
Power BI Sales Performance Dashboard
Overview
This Power BI dashboard provides an interactive analysis of sales performance KPIs over a 14-month period. It helps businesses track actual sales versus target sales, understand key trends, and analyze salesperson performance. The dashboard also leverages AI-generated insights to highlight significant changes in sales patterns, helping decision-makers take proactive steps.

Objectives
The goal of this dashboard is to:

Provide a comprehensive sales performance analysis using interactive visualizations.
Compare actual vs. target sales and analyze variance trends.
Identify high-performing and underperforming salespersons.
Utilize AI-driven insights to detect sales trends and fluctuations automatically.
Enhance user experience with slicers, bookmarks, and dynamic filtering.
Key Features & Functionalities
1. Sales Performance Overview
Displays Total Sales Actual and Total Sales Target for the reporting period.
Highlights monthly and year-to-date (YTD) variances.
Shows a percentage variance indicator, allowing quick insights into deviations from the target.
2. Sales Trends Analysis
Bar Chart Visualization: Compares actual vs. target sales over 14 months.
Trend Indicators: Positive and negative variances marked with visual cues (e.g., red for decline, green for growth).
AI-Generated Insights: Detects unusual patterns, such as a 24.87% decline in sales over the last 3 months.
3. Salesperson Performance Breakdown
Individual Sales Analysis: Displays each salesperson’s actual vs. target sales.
Performance Variance Table: Highlights over/underachievement with conditional formatting.
Trend Sparklines: Shows each salesperson’s sales pattern over time.
4. Interactive Features for Enhanced Usability
Slicers & Filters: Users can filter data by time period, salesperson, and sales category.
Bookmarks & Navigation: Custom buttons allow seamless transitions between key insights.
Drill-Through Capability: Enables deep dives into specific sales trends per region or product.
Power BI Techniques Used
1. Data Modeling
Established one-to-many relationships between sales, targets, and salesperson datasets.
Optimized data schema to improve query performance.
2. Data Transformation (Power Query)
Imported raw sales data and cleaned inconsistencies.
Used Power Query Editor for:
Handling missing values.
Standardizing date formats.
Merging & appending tables for comprehensive analysis.
3. DAX Calculated Measures
Total Sales Actual = SUM(Sales[ActualSales])
Total Sales Target = SUM(Sales[TargetSales])
Sales Variance = [Total Sales Actual] - [Total Sales Target]
Variance % Calculation = DIVIDE([Sales Variance], [Total Sales Target]) * 100
4. AI-Generated Insights
Integrated Power BI Smart Narratives to generate automated insights on sales trends.
Detected sales downturns and fluctuations dynamically based on past data trends.
5. Interactive UI Enhancements
Implemented bookmarks & navigation buttons for better user experience.
Used slicers & filters for interactive analysis based on date and salespersons.
Business Impact
Faster Decision-Making: Management can quickly identify sales shortfalls and take corrective actions.
Performance Benchmarking: Helps evaluate individual salespersons’ contributions and identify training needs.
Strategic Planning: AI insights assist in forecasting future sales trends based on historical data.
Enhanced Reporting: Provides a visually appealing and easy-to-use dashboard for executives and analysts.
How to Use the Dashboard
Download the Power BI (.pbix) file from the repository.
Open it in Power BI Desktop or Power BI Service.
Explore the insights using slicers and interactive visualizations.
Use the AI-generated insights to understand key trends in sales performance.
Modify data sources (if required) to analyze your own sales data.
Future Enhancements
Predictive Sales Forecasting using advanced DAX and AI models.
Integration with live data sources (SQL, Azure, Power BI Service).
Custom tooltips and drill-through analysis for deeper insights.
Mobile-optimized version for better accessibility.
Conclusion
This Power BI dashboard provides a powerful, data-driven approach to monitoring sales performance, enabling businesses to make informed decisions. By integrating DAX calculations, AI insights, and interactive features, this report delivers valuable business intelligence in a visually compelling format.

Connect me @sarathvatyam@gmail.com for any feedback.
