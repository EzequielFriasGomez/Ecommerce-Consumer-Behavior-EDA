[🇪🇸 Leer versión en Español](README_ES.md)

# Sales & Seasonality Analysis: Electronics Sector

**Project Overview** This repository contains the data cleaning process and exploratory data analysis (EDA) for a simulated e-commerce dataset. The main goal was to take raw data, find actual purchasing patterns, and use them to optimize the company's ad spend.

**The Business Problem** The company was spending its marketing budget blindly across all demographics and seasons. We needed to answer two straightforward questions to stop wasting resources: Who is actually buying our products, and when?

**What I Did** Using Python and Pandas, I built a data cleaning pipeline:
- Standardized currency strings into workable numeric formats.
- Segmented customers into custom, logical age brackets.
- Mapped purchase dates to group transactions by season.
- Exported a clean, relational-ready dataset for Power BI visualization.

**What the Data Shows** The final dashboard revealed two hard truths about our market:
1. **Purchasing power matters:** The 35-50 age bracket brings in nearly double the revenue of the 18-25 group. High-ticket electronics require disposable income, making older millennials and Gen X our core demographic.
2. **Summer is a dead zone:** Revenue hits rock bottom during the Summer ($2.46k) and spikes to its absolute peak during the Fall ($4.08k).

**The Strategic Move** Based on these numbers, the business recommendation is direct: cut back the ad spend targeting younger demographics and drastically reduce the marketing budget during the Summer. That money should be reallocated to aggressive Fall campaigns aimed squarely at the 35-50 age group.

**Tools Used:** Python (Pandas) | Microsoft Power BI
