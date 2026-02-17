*SDG Data Analysis & Visualization (Asia) — Food Loss/Waste + Farmer Incomes*

This project analyzes Asia’s progress toward two UN Sustainable Development Goal targets relevant to a supermarket circular-economy initiative:
- SDG 2 (Zero Hunger) — Target 2.3: Improve productivity and income of small-scale food producers, with emphasis on equity (e.g., gender and indigenous groups).
- SDG 12 (Responsible Consumption & Production) — Target 12.3: Reduce food loss and food waste across the supply chain.

The analysis is framed around a business case for All-Star Supermarket, which plans to launch an animal feed product line using food waste/by-products while building partnerships that support low-income and indigenous farmers across Asia.

Project Goals
- Assess trends in agricultural worker income (male vs female) over time across Asian countries.
- Measure food loss and food waste patterns across countries and categories.
- Explore relationships between food loss levels and agricultural worker income.
- Deliver an interactive Tableau dashboard and recommendations to support circular-economy strategy and more equitable supply chains.

Data Sources
- Income / Earnings (SDG 2.3.2): International Labour Organization (ILOSTAT) — average monthly earnings in rural areas and agriculture-related occupations, filtered to US dollars and segmented by sex.
- Food Loss & Food Waste (SDG 12.3.1): FAO / UN SDG Indicators Data Portal — country-level food loss (tonnes) and food waste (per capita and tonnes), including sector breakdowns such as Households (HHS), Out-of-Home Consumption (OOHC), and Retail (RTL).
- Licensing noted in the report: CC BY 4.0 (UNStat / ILO / FAO open data policy).

Tools & Methods
- Tools used: Microsoft Excel (data cleaning, pivoting, descriptive stats, correlations) and Tableau (data model + calculated fields + interactive dashboard).
- Key preparation steps:
  - Standardized income data to Currency: US dollars only.
  - Addressed missing values by imputing country-wise averages where appropriate; removed countries with excessive missingness to reduce bias.
  - For food waste datasets, restricted analysis to 2019–2022 for cross-country consistency (since only Japan had earlier coverage).
  - Excluded inconsistent country series where required (e.g., Bhutan’s missing early food-loss years) to avoid skew in comparisons.
  - Built a master Country–Year table to support reliable joins across sources and preserve combinations during integration in Tableau.

Dashboard (What’s Included)
- Income trend lines (2013–2023): male vs female agricultural worker income over time.
- Gender earnings comparison: side-by-side bars for male vs female earnings.
- Heatmaps: country-level intensity views for food loss (tonnes), food waste (tonnes), and agricultural worker earnings.
- Scatter plot: correlation view between food loss and income.
- Food-loss by item: ranked bar chart of top food items with highest loss.
- Interactive filters: country and year filters to explore patterns by region and time.

Key Findings
- Income declines (2013–2023): both male and female agricultural worker incomes show a substantial downward trend in the summarized view used in the report, with persistent gender gaps.
- Gender disparity: male earnings are consistently higher than female earnings across the period analyzed (reported average gap ~38% in the project summary).
- Country patterns: highest food loss and waste totals are concentrated in large economies (e.g., China and India in the dashboard view), while income levels vary widely across countries (e.g., highest in Hong Kong, China; lowest in Nepal in the report summary).
- Food loss vs income: the combined view indicates a negative relationship between food loss and agricultural worker income.
- Highest-loss items: vegetables are highlighted as a top contributor to food loss among the top-ranked items displayed.

Recommendations (Business + SDG-Aligned)
- Improve supply-chain efficiency (monitoring, logistics, storage/transport improvements) to reduce food loss.
- Use discounting/donation strategies near expiration to reduce retail waste.
- Repurpose high-loss food items/by-products into animal feed inputs where feasible.
- Support small-scale farmers with technology and improved agricultural practices; reduce financial and process barriers.
- Consider wage/compensation approaches that reduce gender disparity in agricultural earnings.
