![Power BI](https://img.shields.io/badge/Power%20BI-Data%20Analysis-yellow)
![DAX](https://img.shields.io/badge/DAX-Measures-blue)
![Power Query](https://img.shields.io/badge/Power%20Query-ETL-green)

## Project Overview

This project analyses key Nigerian economic indicators from 2015 to 2025 using Microsoft Power BI.

The dashboard brings together data on GDP growth, population, inflation, monetary policy rates, Brent crude oil prices, and official exchange rates to identify major economic trends and relationships over time.

The project demonstrates how data from multiple authoritative sources can be cleaned, transformed, modelled, and visualised to produce an interactive economic dashboard.

## Project Objective

The objective of this project is to analyse Nigeria's economic performance between 2015 and 2025 and communicate the major trends through an interactive Power BI dashboard.

The analysis focuses on:

- GDP growth
- Population growth
- Inflation
- Monetary Policy Rate (MPR)
- Brent crude oil prices
- Official exchange rates

The dashboard allows users to select individual years and dynamically explore how the indicators changed over the study period.

## Business Questions

The analysis aims to answer the following questions:

1. How did Nigeria's GDP growth change between 2015 and 2025?
2. How did inflation evolve over the period?
3. How did the Monetary Policy Rate change over time?
4. How did Brent crude oil prices move alongside GDP growth?
5. How did the official exchange rate change during the period?
6. What relationship can be observed between inflation and monetary policy?
7. What relationship can be observed between inflation and the exchange rate?
8. How did Nigeria's population change between 2015 and 2025?
9. What major economic patterns can be identified from the combined indicators?

## Data Sources

The analysis uses data from the following authoritative sources:

| Indicator | Source | Period |
| GDP Growth | World Bank | 2015–2025 |
| Population | World Bank | 2015–2025 |
| Inflation | IMF | 2015–2025 |
| Brent Crude Oil Price | FRED | 2015–2025 |
| Monetary Policy Rate (MPR) | Central Bank of Nigeria (CBN) | 2015–2025 |
| Official Exchange Rate | Central Bank of Nigeria (CBN) | 2015–2025 |

## Tools & Technologies

- Microsoft Power BI
- Power Query
- DAX
- Microsoft Excel
- GitHub
- Markdown

## Data Preparation

The datasets were prepared and transformed before being used in the Power BI dashboard.

Key preparation steps included:

- Importing data from multiple economic sources.
- Cleaning and standardising column names.
- Converting columns to appropriate data types.
- Standardising the year field across datasets.
- Removing unnecessary columns and records.
- Restructuring datasets where required for analysis.
- Creating a dedicated `DimYear` table covering 2015–2025.
- Establishing relationships between the year dimension and economic indicator tables.
- Creating DAX measures for dashboard KPIs and trend analysis.
- Validating the results against the source datasets.

## Data Model

A dedicated `DimYear` table was created to provide a consistent time dimension across the economic datasets.

The model connects the year dimension to the individual indicator tables, allowing the dashboard to respond consistently to year selections and slicers.

### Main Tables

- `DimYear` — Year dimension used for filtering and relationships
- `GDP` — GDP growth data
- `Population` — Population data
- `Inflation` — Inflation data
- `MPR Clean` — Monetary Policy Rate data
- `Brent Price` — Brent crude oil price data
- `Exchange Rate` — Official exchange-rate data

## DAX & Measures

DAX measures were created to calculate and display key economic indicators dynamically.

Examples include:

- GDP Growth
- Inflation
- Average Brent Price
- Average MPR
- Average Exchange Rate
- Lastest Population

These measures allow KPI cards and visualisations to respond dynamically to year selections and other dashboard filters.

## Dashboard Features

The Power BI dashboard includes:

- KPI cards for key economic indicators
- GDP growth trend analysis
- Inflation trend analysis
- Population trend analysis
- Brent crude oil price trend
- Monetary Policy Rate trend
- Official exchange-rate trend
- GDP Growth vs Brent Price comparison
- Inflation vs MPR comparison
- Exchange Rate vs Inflation comparison
- Interactive year slicer
- Dynamic filtering across dashboard visuals

## Key Insights & Analysis

### 1. GDP Growth and the 2020 Economic Shock

Nigeria's GDP growth declined sharply from 2.21% in 2019 to -6.37% in 2020. This represents the most significant contraction in the dataset.

GDP growth subsequently recovered to 1.11% in 2021 and increased to 4.32% in 2022.

This period highlights the significant economic disruption experienced in 2020 and the subsequent recovery in economic activity.

### 2. Rising Inflation

Inflation increased substantially during the later years of the period.

The inflation rate reached 33.24% in 2024 before declining to 23.01% in 2025.

The trend indicates a significant deterioration in price stability during the later part of the period.

### 3. Monetary Policy Tightening

The Monetary Policy Rate remained relatively moderate during much of the earlier period but increased substantially in the later years.

The MPR reached 27.29% in 2025.

The increase reflects a much tighter monetary-policy environment during a period of elevated inflation.

### 4. Exchange Rate Depreciation

The official exchange rate increased significantly over the 2015–2025 period.

The rate reached approximately ₦1,518 per US dollar in 2025, representing a substantial change from the earlier years of the dataset.

The sharp movement in the exchange rate coincided with a period of increased inflation and monetary-policy tightening.

### 5. Brent Crude Oil Prices

Brent crude oil prices experienced significant fluctuations throughout the period.

Prices fell sharply around 2020 before recovering strongly in subsequent years. The dataset records the highest annual average Brent price at approximately $100.93 in 2022.

The movement in oil prices is particularly relevant to Nigeria because crude oil remains an important component of the country's external and fiscal position.

### 6. Population Growth

Nigeria's population increased consistently throughout the period.

The population reached approximately 237.5 million in 2025, demonstrating continued growth in the country's demographic base.

Population growth has important implications for economic planning, employment, infrastructure, public services and consumer demand.

### Overall Finding

The dashboard shows that Nigeria's economic environment changed considerably between 2015 and 2025.

The most notable developments were the sharp economic contraction in 2020, the subsequent recovery in GDP growth, rising inflation, substantial exchange-rate movements and significant increases in the Monetary Policy Rate during the later years.

The analysis highlights how multiple economic indicators can move together during periods of economic stress, while also recognising that correlation between indicators does not necessarily imply direct causation.

## Dashboard Preview

The interactive Power BI dashboard provides an overview of Nigeria's key economic indicators from 2015 to 2025.

### Dashboard Overview

![Nigeria Economic Indicators Dashboard](https://github.com/Wani212/Nigeria-Economic-Indicators-Dashboard/blob/main/03%20Images/Screenshot%202026-08-10%20082401.png)

The dashboard includes KPI cards, trend analysis, comparative visuals and an interactive year slicer to support exploration of Nigeria's economic performance.

## Limitations

- The analysis covers the period 2015–2025.
- The dashboard focuses on selected macroeconomic indicators and does not represent every factor affecting Nigeria's economy.
- The analysis identifies trends and relationships but does not establish causality.
- Differences in data definitions, frequency and methodology between sources may affect direct comparisons.
- Exchange-rate figures represent the official exchange-rate series used in the dataset.
- The dashboard is designed for analytical and educational purposes rather than economic forecasting.

## Future Improvements

Potential improvements to the project include:

- Incorporating additional economic indicators such as unemployment, interest rates, government debt and trade balance.
- Adding monthly or quarterly analysis where reliable data is available.
- Developing forecasting models for inflation, GDP growth and exchange rates.
- Performing statistical correlation and regression analysis.
- Adding automated data-refresh functionality.
- Comparing Nigeria's economic performance with other African economies.
- Developing a more detailed economic-shock analysis for major events such as the COVID-19 pandemic and oil-price shocks.

## Conclusion

This project demonstrates the use of Power BI, Power Query and DAX to transform economic data from multiple sources into an interactive analytical dashboard.

The analysis highlights major changes in Nigeria's economic environment between 2015 and 2025, including the 2020 economic contraction, subsequent GDP recovery, rising inflation, significant exchange-rate movements and monetary-policy tightening.

The project demonstrates practical skills in data cleaning, data modelling, DAX, visualisation, trend analysis and data storytelling.

## Author

**Udoekpo Uwana Promise**

Data Analysis Portfolio Project

Tools: Power BI | Power Query | DAX | Excel
