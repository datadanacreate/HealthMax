# HealthMax

HealthMax is a fictitious market leader in the shampoo industry. In this project, I analyzed their data to identify growth opportunities related to Net Revenue Management and came up with actionable insights to grow the business. 

## Year Over Year Growth

I started by calculating Key Performance Indicators (KPIs) such as market share and value growth on various time dimensions such as year-to-date (YTD) and moving annual total (MAT).

## Year to Date

The dataset contains unit and value sales per month for all years from 2018 to 2023. I looked at different time periods to calculate the Year-To-Date (YTD) for all the dataset points by using a SUMIFS() function.

## Moving Annual Total

Calculated the Moving Annual Total (MAT) for all the dataset points using a longer period than YTD.

## Market Share

Create a new PivotTable to calculate the total value sales per year, per brand in a new worksheet called "Market Share" to see how HealthMax's brands evolved and if there are regional differences.

# Net Revenue Management

I focused on two pillars of Net Revenue Management (NRM): Brand Portfolio Pricing and Mix Management. I calculated important KPIs such as net sales contribution and gross margin. I also used brand Portfolio Pricing to identify the correct price for HealthMax's consumers while also using Mix Management techniques to help HealthMax launch a new product and expand into a new subcategory.

## Profitability Matrix

HealthMax wanted to shift investments in between its products so I made a list of product prioritizations in function of their net sales and their profitability. I started by calculating the net sales for each product.

*(Imported data from internal_sales_data.csv)*

## Gross Margin

I made a scatter plot to compare the gross margin to the net sales contribution for the different products.

## New Category Opportunity

While looking at the brand mix, I noticed that HealthMax is only active in 2 out of the 5 shampoo subcategories and that it might be interesting to launch a new product to enter a new subcategory. To do so, I identified the fastest growing subcategory (in units), Organic, and made an estimation of the total Organic subcategory size for 2024.

Looking at the historic trend, I estimated that this category size for full year 2024 will be 20% higher than the March 2023 MAT values.

My estimated total units sold in 2024 in Organics was $1,020,899.

## New Product Launch

HealthMax had two possible products that fit in the Organic Shampoo category that can be launched in the beginning of 2024. I identified the best candidate by making an estimation of expected net sales, gross profit, and gross margin for both products.

*(Imported data new_product_launch.csv)*

# Optimizing Net Revenue

## Price Pack Architecture

The smallest shampoo size in HealthMax's portfolio is 100ml. Research has shown that people that travel are looking for shampoo bottles of 50ml so HealthMax is looking to create a smaller shampoo size. I calculated the potential of a smaller shampoo bottle:

I decided to launch the best rotating product, the Starbust Ultra Soft 100ml, in a 50ml format.

*Assumptions: 
The Volume 2022 will be 10% of the volume of the 100ml pack in 2022.
The retail price is a 50% mark-up of the price per ml of the 100ml pack.
The Net Price is $2.30 and the COGS amount to $0.70.*

The new 50ml Starburst Ultra Soft product will produce $365,960 in Net Sales.

## Promotion Management

HealthMax played three different promotions on the Shinez brand in 2022. To build the strategy for 2024,I analyzed which promotions are the most effective by calculating the ROI for each.

*(Imported promotion_analysis.csv)*

## Forecasting

I forecasted the full year 2023 and 2024 using the Forecast Sheet function.

## Waterfall

After calculating different opportunities based on the NRM pillars, I created a waterfall graph to show how these initiatives will have an impact on the company's net sales of 2024 compared to natural growth.

Look up the generated Net sales of the launch of the Organic shampoo (product 2) and the 50ml shampoo.
Let's assume the growth initiatives don't cannibalize each other.

The 2024 sales estimate is all the initiatives added together (including the natural growth) for a total of **$21,411,568.78**.

 As shown, the NRM initiatives generate more net sales than natural growth.								

## Conclusion

In conclusion, I analyzed the full shampoo category, discovered interesting insights, and identified the key players in the market. I calculated important KPIs like growth and market share, but also calculated more complex metrics like YTD and MAT to better support my analysis. I also forecasted the net sales for the coming year and showed that the NRM initiatives can unlock extra growth potential. Finally, I prepared clear strategic recommendations on how the company can increase its net sales and profitability.
