# Gold-Price-Prediction-Using-Market-Indices
This project involves building and deploying a machine learning model to predict gold prices based on other key market indicators. The model leverages historical data from commodities, indices, and financial instruments, including Crude Oil prices, Silver prices, the Dollar Index, the S&P 500, and Interest Rates.

The primary objective is to provide accurate gold price predictions, assisting traders, investors, and financial analysts in making informed decisions.
# Key Features:

   * Data Collection and Processing:
        Historical price data for gold and related market indices were collected from Yahoo Finance using the yfinance Python library.
        Features include lagged values, moving averages, and volatility metrics to capture trends and relationships between markets.

  * Model Development:
        A machine learning model was trained using advanced algorithms such as XGBoost to predict daily gold prices.
        Performance was evaluated using metrics like Mean Squared Error (MSE) and R² score to ensure high accuracy.

   * Model Deployment:
        The trained model was serialized using the pickle library for efficient storage and reusability.
        A user-friendly web application was built using the Streamlit framework, allowing users to input key market data and receive gold price predictions instantly.

   * User Interface:
        The app includes an intuitive interface where users provide inputs for features like Crude Oil Price, Silver Price, Dollar Index, and more.
        Predictions are displayed in real-time with visual insights for better decision-making.

# Applications:

  * Financial Analysis: Helps analysts predict the impact of market fluctuations on gold prices.
    Investment Strategy: Assists investors in identifying opportunities based on market trends.
  * Risk Management: Supports risk assessment by correlating gold prices with other economic indicators.
