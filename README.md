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
5. **Insights & Recommendations**:
   - Provide actionable insights for inventory optimisation and strategic planning.

---

## Results
- Accurate forecasts for product categories, capturing seasonal variations and demand patterns.
- Improved understanding of market trends and their impact on sales.
- Recommendations for inventory management to reduce costs and enhance profitability.

---

## How to Run
1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/ForecastEdge.git
   ```
2. Navigate to the project directory:
   ```bash
   cd ForecastEdge
   ```
3. Install required libraries:
   ```bash
   pip install -r requirements.txt
   ```
4. Open the Jupyter Notebook:
   ```bash
   jupyter notebook
   ```
5. Run the notebook `Solution.ipynb` to explore the analysis and forecasting models.

---

## Future Work
- Incorporate real-time data for continuous forecasting updates.
- Explore advanced interpretability methods (e.g., SHAP, LIME) to enhance trust in AI-assisted decision-making.
- Extend the model to include promotional and external factors for improved accuracy.

---

## License
This project is licensed under the MIT License. See the `LICENSE` file for details.

