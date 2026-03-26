📈 Stock Price Prediction
---

🚀 Machine Learning Project | Time Series Forecasting + Feature Engineering + Model Comparison
🌟 Month 1 | Task 2 | Internship Project at Arch Technologies ✅

 ---

📌 Task Description
---
Build a predictive model to forecast stock prices based on historical data.

- Perform data cleaning and preprocessing
- Create time-based features (lag, moving average, momentum, volatility)
- Analyze relationships between multiple stocks
- Train and compare models (Linear Regression vs LSTM)
- Evaluate model performance using RMSE & MAE
 ---
 
📂 Dataset
---
- Source: Stock Price Dataset (Kaggle)
- Features: Multiple stock prices (Stock_1 – Stock_5), Date
- Target Variable: Future price of Stock_1
 ---
 
🧰 Tools & Libraries Used
---
- Python (Pandas, NumPy)
- Scikit-learn
- TensorFlow / Keras
- Matplotlib / Seaborn
 ---
 
⚙️ Key Features Engineering
---

- Lag Features (1, 2, 3, 5, 10 days)
- Moving Average (7, 14, 30 days)
- Rolling Standard Deviation (Volatility)
- Returns (percentage change)
- Price Ratios & Spreads between stocks
- Momentum indicators
- Time-based features (day of week, month)
 ---
 
🤖 Model Evaluation
---

| Model	| RMSE	| MAE |
|-------|-------|------------------------|
| Linear Regression	| ✅ Best |	Low Error |
| LSTM	|❌ Poor	|High Error |


📌 Selected Model: Logistic Regression (as baseline/simple model reference)

 ---

📊 Business Insight
---
 
- Stock prices are highly influenced by short-term trends and momentum
- Inter-stock relationships significantly affect predictions
- Simpler models with strong feature engineering outperform complex models
- Market behavior varies across stocks → diversification is crucial
 ---
 
📚 Concepts Covered
---

- Time Series Analysis
- Feature Engineering for Financial Data
- Regression Modeling
- Model Evaluation (RMSE, MAE)
- Cross Validation (TimeSeriesSplit)
- Deep Learning (LSTM)
