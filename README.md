# Power BI Basket Analysis Report

This repository contains a Power BI report based on basket analysis techniques. The report utilizes various key metrics such as Support, Confidence, Expected Confidence, and Lift to analyze purchasing data and reveal products that are frequently bought together.
<img width="1062" alt="image" src="https://github.com/hikaruminagawa/powerBi_basket_analysis/assets/96165184/ddd61154-b09b-42d2-83d6-b3cd2e4e202b">

## Key Metrics:
- **Support**: Indicates how often items are purchased together.
- **Confidence**: The likelihood of purchasing Item Y when Item X is bought.
- **Expected Confidence**: The proportion of all customers who purchase Item Y.
- **Lift**: Measures the increase in the likelihood of buying Item Y when Item X is purchased.

## Data Transformation:
The original data is reshaped from a receipt-line format into a structured format suitable for analysis.

## Basket Analysis Table:
A new table is created to facilitate the basket analysis.

## Visualizations:
Scatter plots are used to visualize the Support and Lift values, with filters applied to focus on significant associations.

## Reference:
The report is inspired by an article on Qiita, which provides a comprehensive guide on conducting basket analysis using Power BI. You can find the article [here](https://qiita.com/spumoni/items/ad94ce6eef6ef7d0c61c).

## Usage:
To view the report, simply clone this repository and open the `.pbix` file with Power BI Desktop.

## Contributing:
Contributions to improve the report are welcome. Please feel free to fork the repository and submit a pull request.

