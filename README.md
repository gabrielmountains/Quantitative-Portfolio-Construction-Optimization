# Investment Optimized Portfolio - Building a Dynamic Portfolio with ML for Maximized Return

This project aims to build a dynamic investment portfolio using machine learning and advanced data analysis techniques to maximize returns. By leveraging a mix of fundamental analysis, technical indicators, sentiment scores from news, and optimization strategies, the goal is to create an effective and well-balanced stock portfolio.

## Project Overview

### 1. Stock Data Retrieval and Ranking
Started by retrieving a comprehensive list of stock symbols and fetching key performance indicators (KPIs) such as P/E, P/B, ROE, D/E, and EPS. These metrics are used to calculate a composite score for each stock, helping to rank them and select the top 20 stocks for further analysis.

### 2. Technical Indicators and Model Implementation
Computed a variety of technical indicators like MA_10, MA_30, RSI, MACD, Bollinger Bands, ATR, Volume Change, and Volatility. Implemented different models (Random Forest, XGBoost, Gradient Boosting, Neural Networks, Transformers) to predict stock price direction. The models are trained on historical data using a rolling window approach to capture the most relevant trends, and evaluated on MSE and Direction Accuracy.

### 3. Sentiment Score from News Analysis
To enhance the feature set, calculated a sentiment score for each stock based on news analysis. This score is compsosite, computed from retrieved sentiment scores using an API that analyzes the sentiment of multiple news articles related to each stock, providing an additional predictive edge.

### 4. Portfolio Optimization with CVXPY
Once the predictions are made, used CVXPY to optimize the weight allocation in the portfolio. This helps in maximizing returns while managing risk effectively.

### 5. Enhancements and Future Work
The project is in the process of being enhanced with:
- **Risk Balancing:** Balancing the portfolio for risk by selecting negatively correlated stocks to reduce overall portfolio volatility.
- **Wider Investable Universe:** Implementing the same strategy for a broader range of investable assets such as options, futures, bonds, and ETFs.
- **Advanced Feature Engineering:** Incorporating additional features such as economic indicators, sector performance, and global financial news.
- **Hyperparameter Tuning:** Systematic tuning of model hyperparameters to improve predictive performance.
- **Ensemble Methods:** Combining predictions from multiple models to increase robustness and accuracy.
- **Real-time Data:** Integrating real-time data feeds to make the model predictions and portfolio adjustments more responsive to market changes.

## Results and Performance
The project demonstrates how machine learning models can predict stock price directions and optimize portfolio weight allocations. Results from different models are compared, highlighting their prediction accuracies and the overall portfolio performance.

Future work aims to validate the model's effectiveness in a live trading environment, assess the portfolio's performance over extended periods (backtest), and continuously refine the model with new data and techniques.

Feel free to explore the repository, contribute, and provide feedback! Constantly looking to improve and expand it.
