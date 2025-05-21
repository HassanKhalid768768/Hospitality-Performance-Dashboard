
# Hospitality Performance Dashboard

## Overview
This Power BI dashboard provides actionable insights into hospitality unit performance across different regions. It tracks key metrics such as revenue, occupancy, pricing, profitability, guest satisfaction, and operational risk, enabling data-driven decisions to optimize business performance.

## Features
- Revenue and Net Profit analysis with target comparisons
- Occupancy rates through nights booked vs. nights available
- Pricing performance against market benchmarks (ADR vs Market ADR)
- Guest experience metrics including average rating, repeat guests, and five-star percentages
- Operational quality and flagged event tracking
- Risk assessment using churn risk flags
- Time series analysis for monthly trends

## Data Fields
| Field Name          | Description                                    |
|---------------------|------------------------------------------------|
| Month               | Month of record                                |
| UnitID              | Unique identifier for each unit                |
| Region              | Geographic region                              |
| NightsAvailable     | Number of nights available                      |
| NightsBooked       | Number of nights booked                         |
| ADR_PKR            | Average Daily Rate in PKR                        |
| MarketADR_PKR      | Market Average Daily Rate in PKR                 |
| Revenue_PKR        | Total revenue generated in PKR                   |
| RevPARTarget_PKR   | Revenue per Available Room target in PKR        |
| NetProfit_PKR      | Net profit in PKR                                |
| GrossMarginPct     | Gross margin percentage                          |
| RepeatGuestPct     | Percentage of repeat guests                       |
| FiveStarPct        | Percentage of five-star ratings                   |
| TTL_Days           | Time to live or operational days                  |
| CostPerNewUnit_PKR | Cost per new unit in PKR                           |
| OpsQualityScore    | Operational quality score                          |
| FlaggedEventsCount | Count of flagged operational events                |
| ChurnRiskFlag      | Flag indicating churn risk (Yes/No)                |
| AvgGuestRating     | Average guest rating                               |

## Usage
1. Open the Power BI Desktop application.
2. Load the `.pbix` dashboard file.
3. Connect to your data source or load sample data.
4. Use slicers to filter by month, region, or unit.
5. Explore visuals including waterfall charts, bar charts, line charts, heatmaps, and more.

## Installation
- Download [Power BI Desktop](https://powerbi.microsoft.com/desktop/).
- Clone this repository or download the `.pbix` file.
- Open the `.pbix` file in Power BI Desktop.

## Contribution
Feel free to fork the project and submit pull requests with improvements or new visualizations.

## License
This project is licensed under the MIT License.
