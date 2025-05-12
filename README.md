# Olist Dataset Analysis - Identifying Underperforming Sellers(Descriptive Data Analysis)

## Background

The **Olist** dataset provides data about an e-commerce platform, which includes information about sellers, their products, customer reviews, and various operational costs. This dataset allows us to analyze different factors that influence a seller's overall performance, including financial aspects and customer feedback.

In this analysis, the goal was to identify **underperforming sellers** on the Olist platform by analyzing their **overall profit** and factoring in two specific costs:
- **Bad review costs**: Costs related to negative customer feedback.
- **Tech costs**: Operational costs associated with platform use.

## Objective

The objective of this analysis was to determine how much profit could have been saved by terminating contracts with underperforming sellers. Instead of using machine learning models or evaluations, this analysis is **descriptive** in nature, focusing on data exploration and identifying trends.

## Methodology

The following steps were taken in the analysis:
1. **Data Exploration**: Explored the dataset to understand the key variables, such as seller IDs, products, review scores, and operational costs.
2. **Underperforming Sellers Identification**: Sellers were identified as underperforming if their **overall profit** was outweighed by **bad review costs** and **tech costs**.
   - Profit = Sales Revenue - (Bad review costs + Tech costs)
   - Sellers with a **negative** or **low overall profit** after accounting for these costs were flagged as underperforming.

3. **Descriptive Statistics**: Various descriptive statistics were calculated to understand the distribution of profits, costs, and the number of underperforming sellers.

## Key Findings

- A significant portion of sellers experienced higher operational costs due to bad reviews and tech-related issues, leading to **reduced profitability**.
- Sellers that were categorized as underperforming could have contributed more profit if they were removed from the platform, but this analysis is only based on raw descriptive data and does not predict potential savings or improvements.

## Conclusion

This analysis sheds light on the profitability of sellers on the Olist platform and highlights the impact of customer reviews and tech-related costs. By understanding these factors, the platform could potentially focus on improving seller performance, leading to overall cost savings and enhanced profitability.

## Requirements

- **Python**
- Libraries:
  - pandas
  - matplotlib
