# Power BI Sales Report

This repository contains a Power BI report that visualizes key sales metrics and trends. The report provides insights into sales performance, product analysis, and regional sales distribution. 
It is designed to help stakeholders make data-driven decisions by providing interactive and easy-to-understand visualizations.

## Files

- `First Report.pbix`: The main Power BI report file.

## How to Use

1. Download the `First Report.pbix` file.
2. Open it using Power BI Desktop.
3. Explore the visualizations and data insights within the report.

## Visualizations Included

- **Sales Performance Overview**: A summary of overall sales performance including total sales, number of transactions, and average sales per transaction.
- **Monthly Sales Trends**: Line charts showing sales trends over time, helping to identify seasonal patterns and growth rates.
- **Product Analysis**: Bar charts and tables highlighting top-selling products and categories.
- **Regional Sales Distribution**: Maps and heatmaps showing sales distribution across different regions, enabling regional performance comparison.
- **Customer Insights**: Demographic analysis of customers to understand the target audience and customer behavior.

## Data Source

The data used in this report is fictional and created for demonstration purposes. It includes sales data across various products, regions, and customer demographics.

## Key DAX Measures

Some of the key DAX measures used in this report include:
- `Total Sales`: `SUM(Sales[SalesAmount])`
- `Average Sales per Transaction`: `AVERAGE(Sales[SalesAmount])`
- `Total Transactions`: `COUNTROWS(Sales)`

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

## Author

This report was created by Sanjida Rahman Supti. For any questions or feedback, please contact me at ssupti@uoguelph.ca.

## Additional Resources

- [Power BI Documentation](https://docs.microsoft.com/en-us/power-bi/)
- [DAX Guide](https://dax.guide/)

