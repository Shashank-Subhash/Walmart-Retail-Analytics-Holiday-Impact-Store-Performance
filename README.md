                      **Walmart Retail Sales Analysis**
**Project Overview**
This project analyzes Walmart’s weekly sales data across 45 stores from February 2010 to November 2012. The objective is to evaluate store performance, identify the impact of holidays, and assess the influence of external factors such as fuel prices, inflation (CPI), unemployment rates, and temperature.
The analysis demonstrates the ability to work with real-world retail data, apply statistical and visualization techniques, and translate findings into actionable business insights.

**Objectives**
  Identify top-performing and most volatile stores.
  Compare holiday and non-holiday weekly sales.
  Explore seasonal and semester-based sales patterns.
  Assess the relationship between economic/environmental variables and sales performance.
  Present findings through clear visualizations and correlations.

**Dataset**

**Source:** Walmart weekly sales dataset (45 stores).
**Timeframe:** 2010-02-05 to 2012-11-01.
**Key Columns:**
  Store: Store identifier (1–45)
  Date: Week ending date
  Weekly_Sales: Total weekly sales (USD)
  Holiday_Flag: 1 = Holiday week, 0 = Non-holiday week
  Temperature: Average weekly temperature (°F)
  Fuel_Price: Average regional fuel price (USD/gallon)
  CPI: Consumer Price Index
  Unemployment: Regional unemployment rate (%)

**Tools and Technologies**
**Language:** Python
**Libraries:** Pandas, NumPy, Matplotlib, Seaborn
**Environment:** Jupyter Notebook

**Methodology**
**Data Preparation**
  Imported dataset and verified data quality.
  Confirmed dataset contained no missing values.

**Exploratory Data Analysis (EDA)**
  Distribution of weekly sales across stores.
  Identification of the store with maximum sales and the store with the highest sales variability.

**Holiday Impact Analysis**
  Calculated mean weekly sales for non-holiday periods.
  Compared against holiday weeks to measure seasonal uplift.

**Time-Based Analysis**
  Aggregated sales data monthly and by semester to evaluate seasonal trends.

**External Factors**
  Examined relationships between weekly sales and external indicators (fuel price, CPI, unemployment, temperature).
  Identified negligible effects from fuel price and temperature, with moderate correlation from unemployment and CPI.

**Correlation Analysis**
  Created a heatmap to summarize positive and negative correlations between weekly sales and all numeric variables.

**Key Findings**

  Store #20 consistently achieved the highest weekly sales.
  Holiday weeks (particularly Thanksgiving and Christmas) generated significantly higher sales compared to non-holiday weeks.
  Fuel prices and temperature showed minimal correlation with sales.
  Unemployment rates and CPI demonstrated measurable influence on consumer spending behavior.
  Strong seasonal sales patterns were observed, supporting the case for time-based forecasting models.

**Business Implications**

  Walmart can improve holiday preparedness by aligning promotions, inventory, and staffing with peak demand periods.
  Stores with high sales volatility should be prioritized for supply chain optimization.
  Monitoring economic conditions such as unemployment and CPI can guide pricing and promotional strategies.
  The findings provide a foundation for predictive modeling and sales forecasting to support strategic planning.
