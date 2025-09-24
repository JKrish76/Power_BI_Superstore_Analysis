Superstore Profitability Analysis in Power BI

### [View the Full PDF Report](Superstore%20Analysis.pdf)

----------

## 📝 Project Summary

This project analyzes the Superstore dataset to identify key drivers of profitability and uncover actionable insights for business growth. The analysis revealed a critical disconnect between sales and profit, driven primarily by an aggressive discount strategy on specific products within underperforming regions.


----------

## 💡 Key Findings & Story

1. **Executive Summary:** While overall sales show a positive upward trend, a significant portion of our profit is being eroded by our discount strategy. The **'Tables' sub-category**, in particular, is consistently unprofitable when discounts exceed 20%.

2. **Geographic Insights:** These losses are most severe in the **Central region**, turning it into our least profitable area despite a high volume of sales.

3. **The Discount Trap:** A clear, negative correlation exists between discount levels and profit ratio. Products with discounts over 30% are almost always sold at a loss.

----------

## 🚀 Actionable Recommendations

To boost overall profitability, we must immediately **review and cap the discount levels** applied to underperforming product lines, starting with 'Tables' and 'Bookcases' in the Central region. A targeted operational review of this region is advised to address the specific product mix and pricing strategies.

----------

## 🛠️ Tools & Techniques

1. **Tool:** Microsoft Power BI
2. **Data Analysis:** Identified trends, geographic patterns, and product performance.
3. **DAX (Data Analysis Expressions):** Created a `Profit Ratio` measure for deeper analysis (`Profit Ratio = DIVIDE(SUM([Profit]), SUM([Sales]))`).
4. **Visualization:** Built an interactive, multi-page report with slicers and page navigation for a comprehensive user experience.
