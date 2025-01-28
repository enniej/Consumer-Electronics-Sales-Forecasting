# Consumer-Electronics-Sales-Forecasting
An advanced Python-based sales forecasting system that leverages machine learning to predict consumer electronics sales patterns and optimize inventory management.
![image](https://github.com/user-attachments/assets/7cde1be6-ff85-43de-9781-33e6a6019d5b)

## Overview
Aeda Electronics operates in the fast-paced consumer electronics industry, where managing inventory efficiently is a critical challenge. The company's ability to maintain optimal stock levels is hampered by:
- **Demand Variability**: Unpredictable spikes in sales during product launches or holiday seasons.
- **Product Life Cycles**: Short life spans of electronics products.
- **Seasonal Trends**: Changing sales patterns across seasons.
- **Supplier Relations**: Over-ordering or under-ordering can impact supplier relationships.

This project leverages advanced statistical methods and time series models to forecast sales accurately, enabling Aeda Electronics to make informed inventory decisions and improve operational efficiency.

---

## Rationale for the Project
Accurate sales forecasting is essential for Aeda Electronics to:
- **Reduce Costs**: Minimise storage costs and avoid stockouts.
- **Enhance Customer Satisfaction**: Meet customer demand with readily available products.
- **Gain a Competitive Edge**: Stay agile and respond quickly to market changes.
- **Maximise Profitability**: Prevent overstock and understock scenarios.

---

## Objectives
1. Develop accurate sales forecasts for each product category.
2. Identify seasonal trends and demand patterns to optimise inventory management.

---

## Data Description
The dataset includes the following features:
- **Product ID**: Unique identifier for each product.
- **Category**: Product category (e.g., smartphones, laptops).
- **Price ($)**: Price of the product.
- **Sales Volume**: Number of units sold.
- **Date**: Date of sale.
- **Season**: Season of the year (e.g., winter, summer).
- **Market Trend Index**: Represents external factors influencing the electronics industry.
- **Competitor Activity Score**: Measures competitors' influence in the market.
- **Consumer Confidence Index**: Indicates consumer sentiment.
- **Product Specifications**: Additional details about the product.

---

## Tech Stack
The project employs the following technologies and tools:
- **Python Libraries**: Pandas, NumPy, Matplotlib, Scikit-learn, Statsmodels, Prophet
- **Environment**: Jupyter Notebook

---

## Project Scope
1. **Data Collection**: 
   - Gather historical sales and market data from various sources.
2. **Data Processing**: 
   - Cleanse and preprocess the data, addressing missing values and outliers.
3. **Exploratory Data Analysis**: 
   - Identify trends, correlations, and seasonal patterns using visualisations and statistical methods.
4. **Model Development**: 
   - Build and optimise time series models such as ARIMA, Exponential Smoothing, and Prophet.
5. **Model Evaluation**: 
   - Assess model performance using metrics such as MAE, RMSE, and MAPE.

---

## Implementation Steps
1. **Exploratory Data Analysis (EDA)**:
   - Conduct univariate, bivariate, and multivariate analysis to understand the dataset.
   - Visualise sales trends, seasonal patterns, and correlations.
2. **Feature Engineering**:
   - Create new features to capture seasonality, market trends, and product characteristics.
3. **Model Development**:
   - Train and evaluate models, including:
     - ARIMA
     - Exponential Smoothing
     - Prophet
4. **Forecasting**:
   - Generate sales forecasts for various product categories and time periods.
  
     ---

## Results
- Accurate forecasts for product categories, capturing seasonal variations and demand patterns.
- monthly forecasting is more accurate than weekly forecasting for all models
- From the three models (Prophet, ARIMA and Exponential Smoothing) tested, Prophet Model had the best performance.
- Improved understanding of market trends and their impact on sales.
- Recommendations for inventory management to reduce costs and enhance profitability.

    
     ---
  
 **Insights & Recommendations**:
   - ### Insights & Recommendations

     #### Data Integrity and Quality:
     - **Missing Values**: There are no missing values in the dataset, ensuring data completeness for robust analysis.
     - **Duplicate Rows**: The dataset contains no duplicate entries, which simplifies preprocessing and avoids data redundancy.

     #### Category-Level Insights:
     - The dataset includes four main product categories: **Laptop, Tablet, Smartphone, and Accessories**.
     - Tablets constitute the largest category, with 34,370 entries, suggesting high demand or significant market activity in this segment.

     #### Price Analysis:
     - The average product price is approximately £106.81, with a range between £40.51 and £181.80.
     - Accessories are likely to have lower average prices compared to Laptops and Smartphones, which may influence sales volume trends.

     #### Market Trends:
     - The **Market Trend Index** and **Competitor Activity Score** exhibit standardised distributions centred around zero. These metrics could be used to identify market booms or slumps and competitive pressures over time.

     #### Sales Volume Distribution:
     - The average sales volume is **122 units**, with some products achieving volumes as high as 306 units. High-sales products should be prioritised for inventory planning and promotions.

     #### Consumer Confidence Index:
     - The average consumer confidence score is 70, with a range from 40 to 99. This metric is critical for understanding demand sensitivity and aligning inventory with consumer sentiment.

     #### Seasonality and Trends:
     - Products are categorised into four seasons (**Spring, Summer, Autumn, Winter**). The majority of sales data are recorded for **Spring**, indicating potential seasonal peaks.
     - Further analysis is needed to link specific product categories to seasonal demand patterns.

   - ### Actionable Recommendations:

     #### Inventory Optimisation:
     - Focus on maintaining higher stock levels for Tablets, given their significant market activity.
     - Leverage sales forecasts to align inventory levels with seasonal peaks, especially during Spring.

     #### Market Strategy:
     - Monitor the **Market Trend Index** and **Competitor Activity Score** to anticipate shifts in market demand and adjust pricing or promotional strategies accordingly.
     - Capitalise on products with high sales volumes by bundling them with Accessories to boost overall revenue.

     #### Consumer Confidence Alignment:
     - Use consumer confidence data to predict and manage demand fluctuations, ensuring sufficient inventory during periods of high confidence.

     #### Price-Based Targeting:
     - For price-sensitive customers, promote Accessories and lower-cost Tablets. Highlight the premium features of Laptops and Smartphones to justify their pricing.

     #### Seasonal Promotions:
     - Develop targeted promotional campaigns for Spring, which shows the highest sales activity, to maximise revenue during this period.
     - Introduce clearance sales for outdated products before seasonal demand shifts.

---

## Future Work
- Incorporate real-time data for continuous forecasting updates.
- Explore advanced interpretability methods (e.g., SHAP, LIME) to enhance trust in AI-assisted decision-making.
- Extend the model to include promotional and external factors for improved accuracy.



