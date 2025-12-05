📑 Global Food Price Volatility Forecast (2001–2030)Project OverviewThis project provides a comprehensive time-series analysis and forecasting application for Global Food Price Inflation from 2001 through 2030.The core finding is that global food security has entered a new era of permanently elevated inflation (stabilizing near $9.7\%$ , $10\%$ through 2030), primarily driven by structural external shocks. The analysis clearly distinguishes between predictable structural risk and unpredictable domestic volatility.
🛠️ Methodology and Core Technology
The forecasting engine utilizes a robust Seasonal Autoregressive Integrated Moving Average with Exogenous Regressors (SARIMAX) model.
Element,Description,Purpose in Project
Model,"SARIMAX(p, d, q) x (P, D, Q, s) with Exogenous Regressors (X)","Chosen to explicitly include the impact of non-cyclical, external shocks on long-term trends."
Exogenous Variables (X),"Binary shock flags for the 2008 Crisis, COVID-19, and the Ukraine Conflict/Fertilizer Shock.","Used to measure the permanent, structural impact of these events, which established the new 10% inflation baseline."
Interactive App,Built using Plotly and IPywidgets (for notebook demonstration).,"Allows users to select any country and generate a real-time, 60-month forecast plot with a 95% Confidence Interval."
