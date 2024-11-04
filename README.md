# Superstore Returns Analysis

## Project Overview
This project analyzes Superstore's return data to help identify the root causes of high return rates and suggest actionable strategies for reducing both the volume and frequency of returned orders.

## Dataset
- **Dataset Used**: `Superstore.xls`
- **Contents**: Order and returns data from a fictional Superstore, containing details on sales, product categories, regions, and return status.

## Project Link
View the Tableau Public dashboard here: [Superstore Returns Analysis on Tableau Public](https://public.tableau.com/app/profile/ruby.nunez/viz/SuperstoreReturns_17306857754200/MinimizingReturnsAnIn-DepthAnalysisofReturnsforSuperstore)

## Introduction
The Superstore has been experiencing a high number of returned orders, which impacts its profitability. The goal of this project is to identify the factors contributing to returns and recommend data-driven strategies for minimizing these returns, thereby increasing overall profitability.

## Project Objectives
1. Identify primary drivers of product returns across regions, categories, and sub-categories.
2. Determine if certain times of the year see a spike in returns.
3. Propose actionable steps to reduce return rates and improve operational efficiency.

## Methodology
1. **Data Integration**: Combined Orders and Returns tables with a Left Join to identify both returned and non-returned orders.
2. **Calculated Field**: Created a field to represent returns, with "Yes" values as 1 and "null" values as 0, to compute return rates.
3. **Visualization**: Used Tableau to create targeted visualizations including scatter plots, bar charts, and maps, focused on:
   - Correlation between sales and returns.
   - Return rates by product category, customer, geographic area, and time.
4. **Dashboard Design**: Developed a dashboard summarizing key insights and recommendations.

## Visual Representations
- **Scatterplot**: Shows correlation between total sales and return rate by sub-category.
- **Bar Chart**: Displays return rates by product category and by specific customers prone to returns.
- **Map**: Illustrates geographic distribution of return rates, highlighting areas with concentrated returns.
- **Time Series**: Tracks return trends over the year, identifying peak return months.
- **Composite Charts**: Combines multiple factors to highlight high-return areas by region and category.

## Key Findings
- **Profit Centers**: Copiers in both the East and West regions are top profit centers.
- **Loss Makers**: Tables in the East and South regions result in the highest losses.
- **High Return Products**: Machines have the highest return rate, while Binders have the highest total returns.
- **Geographic Insights**: Utah has the highest return rate, with California leading in total returns.
- **Seasonal Trends**: Returns peak in September for Furniture and Technology, and in December for Office Supplies.

## Conclusion
Superstore experiences the highest return rates in specific states and product categories, with significant returns in the West region, particularly for Office Supplies and Machines. Both high return rates and total returns need addressing to reduce overall impact.

## Recommendations for Improvement
- **Focus on Regions**: Reduce or optimize sales in Colorado, Oregon, and Tennessee, which exhibit high return rates.
- **Product Strategy**: Discontinue low-performing products like Tables and Supplies while increasing focus on profitable categories such as Copiers, Phones, and Accessories.
- **Seasonal Advertising**: Implement targeted efforts to manage returns during peak periods (e.g., August-September and December).

## Future Directions
- **Enhanced Customer Insights**: Explore customer behavior further to identify patterns that predict returns.
- **Return Policy Adjustments**: Modify policies based on products and regions with historically high return rates.
- **Regular Monitoring**: Develop a dynamic dashboard to monitor returns in real-time for proactive management.

By implementing these recommendations, Superstore can improve profitability, reduce operational costs associated with returns, and enhance customer satisfaction.
