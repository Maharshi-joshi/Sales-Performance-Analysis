# Sales-Performance-Analysis

## Introduction
This repository contains a comprehensive analysis of sales performance metrics, including win rate, sales cycle length, average revenue, and average deal size. The insights provided here are based on data from a CRM dataset, and the results are visualized through an interactive Tableau dashboard.

This project focuses on analyzing key sales metrics to assess performance and identify areas for improvement. The analysis was conducted using the following steps:
The data is downloaded from Maven Analytics and contains records of a fictitous company that sells hardware to other businesses. It has records of sales, products, comapanies, sales agents and managers.

The data organized using Excel, where key metrics were calculated, and tables were structured and pivot tables were created for further analysis. An interactive Tableau dashboard was created to visualize the metrics. The dashboard includes bar charts, line charts, area charts, and tables, allowing for detailed exploration of the data. Key insights were derived from the visualizations, focusing on performance by sales agents, managers, sectors, and products. These insights are presented in the sections below, with actionable recommendations for optimizing sales strategies.

This structured approach ensures that the analysis is comprehensive, data-driven, and easily interpretable, enabling stakeholders to make informed decisions.


## Table of Content
- [Win Rate Analysis](#win-rate-analysis)
- [Sales Cycle Length](#sales-cycle-length)
- [Average Revenue](#average-revenue)
- [Average Deal Size](#average-deal-size)
- [Interactive Dashboard](#interactive-dashboard)
- [Conclusion](#conclusion)


## Win Rate Analysis

Win rate is a crucial metric that measures the success of sales efforts, represented by the percentage of closed deals relative to the total opportunities. This analysis focuses on identifying top performers and understanding how win rates vary across different managers and over time.

- **Top Performers:** The top three sales agents in terms of win rate are Reed Clapper (65.4%), Garret Kinder (60.98%), and Donn Cantrell (57.45%). Notably, these top performers have either low or no deals in the engaging stage, indicating their effectiveness in quickly closing deals.
- **Manager Influence:** Two of the top three performers, Reed Clapper and Garret Kinder, are managed by Rocco Neubert, suggesting that his management style or strategies may be contributing to their success. Rocco Neubert and Cara Losch seems to have the highest win rate with the least total sales opportunities and both also belong from the East regional office.
- **Areas for Improvement:** Melvin Marxen, another manager, appears to have the lowest average win rate among his sales agents, indicating potential areas for development within his team.
- **Win Rate Trends:** The win rate fluctuates significantly month by month, with March, June, September, and December standing out as the months with the highest win rates, each reaching approximately 80%. This pattern suggests potential seasonality in deal closures.

  ![image](https://github.com/user-attachments/assets/33d5124c-a5d3-4777-bb45-3fce3a183180)



## Sales Cycle Length

The sales cycle length measures the average number of days it takes for a customer to move from the opportunity stage to the closed deal stage. This metric is crucial for building sales forecasts, setting sales targets, and evaluating sales efficiency.

- **Lost vs. Won Deals:** The average sales cycle length for lost deals is approximately 41 days, while for won deals, it extends to about 52 days. This difference may indicate that deals taking longer to close tend to be more successful.
- **Impact of Win Rate:** Sales agents with higher win rates tend to have slightly shorter sales cycle lengths compared to those with lower win rates, suggesting a possible correlation between efficiency and success.
- **Trends Over Time:** The number of days required to complete a sale has been decreasing significantly over recent quarters, which may reflect improvements in sales processes or market conditions.
- **Sector Differences:** The Software and Telecommunications sectors have the longest sales cycle lengths for won deals, while the Marketing sector has the shortest. This variation could be due to the complexity or urgency of deals in different industries.
- **Manager Performance:** Rocco Neubert, the manager with the highest overall win rate, also oversees the team with the shortest sales cycle length, indicating strong management practices that contribute to both speed and success.


## Average Revenue

Average revenue measures the total revenue generated by all sales opportunities. This metric can be broken down by different products and sectors to identify where the most revenue is being generated.

- **Sector Insights:** The Technology, Medical, and Retail sectors have the highest number of sales opportunities, but this does not necessarily translate into higher average revenue.
- **High Revenue Sectors:** The Entertainment, Software, and Finance sectors have the highest average revenue despite having fewer sales opportunities, indicating a higher value per opportunity in these sectors.
- **Retail Sector Performance:** The Retail sector has the highest total sales, which aligns with its large number of sales opportunities, justifying its overall revenue contribution.
- **Product Performance:** The GTX Pro, GTX Plus Pro, and MG Advanced products have generated the highest sales, and they also boast higher win rates, suggesting that these products are both popular and effective in closing deals.

  ![image](https://github.com/user-attachments/assets/a1c83068-291e-4934-9887-3b501fa8e5c7)


 ## Average Deal Size

The Average Deal Size, also referred to as the Average Selling Price, represents the average dollar amount of each closed deal.

- **Quarterly Trends:** The average deal size was lowest in Quarter 1, then increased in Q2 and remained stable afterward. This trend may reflect changes in sales strategies or market conditions as the year progressed.
- **Manager Comparison:** Rocco Neubert has the highest average deal size at $2,837.26, paired with the highest win rate of 52%. In contrast, Dustin Brinkmann has the lowest average deal size at $1,465.01, despite handling more opportunities than Rocco. This suggests differences in deal value management between these managers.
- **Monthly Insights:** The average deal size peaked in April, June, and October, which also corresponded with higher win rates. July, however, was the worst month, with a significant drop in both metrics.
- **Individual Performance:** Elase Gluck and Rosalina Dieter, both under Celia Rouche's management, achieved the highest average deal sizes despite having fewer total won opportunities. This suggests that they might be handling more expensive products or deals with higher individual values.

  ![image](https://github.com/user-attachments/assets/11b7353d-9c8b-4dd0-a093-72cb1b9466a1)


## Interactive Dashboard

Explore the interactive Tableau dashboard to dive deeper into key metrics:

- **Win Rate by Sales Agents**: Compare agent performance and success rates.
- **Sales Cycle Length**: Analyze the average time taken to close deals.
- **Average Revenue by Sectors**: Track revenue trends across sectors over time.
- **Average Deal Size by Managers**: See which managers are handling the largest deals.

Use the filters to customize the data view, and hover over data points for additional insights.

[Access the dashboard here](https://public.tableau.com/app/profile/maharshi.joshi6633/viz/CRM-Analysis/Dashboard1).

  ![Screenshot 2024-08-24 133324](https://github.com/user-attachments/assets/f9dd2084-1a65-4944-a465-fbc71615ff8c)


## Conclusion 

This analysis offers key insights into sales performance, focusing on metrics like win rate, sales cycle length, average revenue, and deal size. The findings highlight top-performing agents, sectors, and products, providing a foundation for optimizing sales strategies and improving efficiency. 

Looking ahead, future analysis could include predictive analytics to forecast trends, customer segmentation to tailor strategies, and integration with marketing data to evaluate campaign effectiveness. These enhancements will drive deeper insights and help maintain a competitive edge.


  


