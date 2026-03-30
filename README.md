# Asset Management Optimization Platform (AMOP)

An applied research project focused on improving investment decision-making through portfolio analytics, inflation-aware insights, forecasting, and interactive dashboards.

## Project Overview

The Asset Management Optimization Platform (AMOP) was developed to help investors and portfolio managers make more informed decisions in an increasingly complex financial environment. The project addresses a common challenge in investing: many users struggle to start, manage, and monitor portfolios effectively because financial data is often fragmented, difficult to interpret, and not translated into actionable insights.

AMOP brings together financial market data, inflation data, portfolio analysis, and forecasting into one analytics-driven solution. The goal is to simplify portfolio decision-making by helping users understand inflation impact, compare asset performance, and explore optimized portfolio strategies.

## Problem Statement

In an inflationary and volatile market environment, passive savings lose value over time and investors often lack clear guidance on where and how to invest. Existing tools may provide large volumes of data, but they do not always convert that data into simple, user-focused portfolio insights.

This project was designed to address that gap by building a platform that supports:

- better financial decision-making
- efficient portfolio monitoring
- inflation-aware investment analysis
- data-driven portfolio optimization

## Objectives

The main objectives of this project were to:

- understand investor pain points through a user-centered research approach
- collect and prepare relevant financial and inflation datasets
- identify strong and weak asset performers using analytical measures
- compare forecasting approaches for financial time series
- generate inflation-adjusted and portfolio-level insights
- present findings through intuitive dashboards for easier decision-making

## Data Used

The project combines multiple financial and economic datasets, including:

- inflation data
- country-level stock market indices
- NASDAQ-100 stock data
- trading volume data
- simulated customer savings profile data

These datasets were used to study market growth, inflation effects, asset performance, and portfolio outcomes over time.

## Analytical Approach

The project followed a structured analytics workflow:

1. **User research and design thinking**  
   Investor pain points were explored through surveys, interviews, empathy mapping, personas, and journey analysis.

2. **Data collection and preparation**  
   Financial and inflation datasets were sourced, cleaned, validated, and structured for analysis.

3. **Exploratory analysis**  
   Trends, distributions, outliers, skewness, and kurtosis were examined to understand market and inflation behaviour.

4. **Feature engineering**  
   Additional variables such as growth rates and performance indicators were created to improve interpretability.

5. **Asset ranking**  
   Compound Annual Growth Rate (CAGR) was used to identify top- and bottom-performing assets.

6. **Forecasting and modelling**  
   Different modelling approaches were explored, including traditional machine learning models and time series models. VAR emerged as the strongest forecasting approach for the selected assets.

7. **Dashboard delivery**  
   Insights were translated into interactive dashboards to support portfolio monitoring and investment decision-making.

## Key Features

- inflation-aware portfolio analysis
- top asset ranking
- portfolio growth comparison
- global market trend analysis
- unrealised gain analysis
- scenario-based investment insights
- interactive dashboard storytelling
- forecasting-driven portfolio recommendations

## Key Insights

Some of the main outcomes of the project include:

- inflation has a major effect on real investment value and should be considered in portfolio decisions
- portfolio optimization can significantly improve long-term growth compared to passive strategies
- analytical ranking methods help identify stronger-performing assets more clearly
- time series forecasting provided better support for financial prediction than standard regression-based machine learning models in this context
- interactive dashboards made complex analysis easier to interpret and use

## Tools and Technologies

- **Python** for data collection, cleaning, transformation, and modelling
- **yfinance API** for financial market data extraction
- **Tableau / Power BI** for dashboarding and visual analytics
- **Excel / CSV** for structured data handling and intermediate storage
