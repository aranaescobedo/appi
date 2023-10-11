<p align="center">
 <img width="100px" src=".images/azure-application-insights.svg" align="center" alt="Azure Application Insights" />
 <h2 align="center">Application Insights (APPI)</h2>
 <p align="center">This repository provides resources for managing and troubleshooting Azure Application Insights!</p>
</p>

## Prerequisites

- [A valid Azure account][azure-account]

## Usage
Each script in this folder is designed to perform a specific task with APPI. Before running a query, make sure to replace any placeholders with your own information.

## Script Descriptions

- **[data-usage-query.kql]**: This Kusto Query is intended to be run inside your Log Analytics workspace and is designed to analyze data usage for a specific Azure Application Insights resource over a specified time, summarizing data types and sizes.
- **[data-trends.kql]**: This Kusto query retrieves and processes data from Azure Application Insights for a specified application. It filters the data for a specific time range and summarizes it to calculate the logging amount in gigabytes. The results are presented in a time chart for visual analysis.

## Disclaimer
Please note that this is provided as-is and may not suit all use cases. Use at your own discretion and make sure to thoroughly test before deployment in a production environment.

[azure-account]: https://azure.microsoft.com/en-us/free
[data-usage-query.kql]: data-usage-query.kql
[data-trends.kql]: data-trends.kql

