# Final_logistycs_project


## Project Overview

This project analyzes delivery performance across three Chinese cities (Shanghai, Hangzhou, and Chongqing) to identify SLA violations, quantify delay-related costs, and evaluate the business impact of operational improvements.


## Business Objective

- Measure SLA compliance
- Identify operational bottlenecks
- Estimate financial impact of delays
- Evaluate a delivery optimization scenario


## Dataset

- 465,384 deliveries
- 1,847 couriers
- 3 cities
- Analysis period: March 18 – April 11, 2024


## Tools

Python, Pandas, NumPy, Matplotlib, Seaborn, SciPy, Statsmodels, Jupyter Notebook


## Key Findings

- 20.6% of deliveries violate the 180-minute SLA
- 12.0% experience critical delays (>240 min)
- 77,624 deliveries are in the risk zone (120–180 min)
- Chongqing has the worst performance with a 37.4% SLA breach rate
- Delay costs account for 24.3% of total delivery spending
- Estimated delay cost: $626,739


## Optimization Scenario (-15% Delivery Time)

| KPI | Before | After |
|------|------:|------:|
| Avg delivery time | 132.8 min | 112.9 min |
| Problem deliveries | 96,043 | 71,582 |
| Delay cost | $626,739 | $439,091 |


### Business Impact

- 25.5% fewer problem deliveries
- $187,648 reduction in delay costs
- 4.5 million delay minutes eliminated
- 75,059 courier hours recovered
- Potential capacity increase without hiring additional couriers


## Recommendations

1. Prioritize operational improvements in Chongqing
2. Rebalance courier workload
3. Increase morning delivery capacity
4. Monitor deliveries approaching SLA limits
5. Improve predictive models with additional data sources
6. Implement operational KPI dashboards


## Skills Demonstrated

- Data Cleaning
- Exploratory Data Analysis
- Data Visualization
- KPI Analysis
- Cost Analysis
- Statistical Analysis
- Scenario Modeling
- Business Analytics


## Conclusion

The analysis shows that a relatively small operational improvement (-15% delivery time) can generate a disproportionately large business impact: 25.5% fewer SLA violations and nearly $188K in annual savings. The results highlight clear optimization opportunities and demonstrate how data analytics can support logistics decision-making.
