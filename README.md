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

🔄 Project Workflow
---

✅ 1. Data Overview & Cleaning

- Checked missing values and handled null data
- Verified data types and converted Date to datetime
- Sorted data by time (time-series consistency)
- Removed unnecessary columns

✅ 2. Exploratory Data Analysis (EDA)
- 📈 Visualization of stock price trends over time
- 📊 Analyzed distribution and volatility of each stock
- 🔗 Identified relationships and correlations between stocks
<img width="986" height="451" alt="image" src="https://github.com/user-attachments/assets/dc33b519-3626-4e69-9114-6ec4789c947e" />


✅ 3. Feature Engineering

- Lag Features (1, 2, 3, 5, 10 days)
- Moving Average (7, 14, 30 days)
- Rolling Standard Deviation (Volatility)
- Returns (percentage change)
- Price Ratios & Spreads between stocks
- Momentum indicators
- Time-based features (day of week, month)

✅ 4. Train-Test Split

- Applied time-based split (no random shuffle)
- Separated features (X) and target (y)

✅ 5. Scaling

Normalized features using MinMaxScaler (for LSTM)

✅ 6. Modeling

- Trained Linear Regression and LSTM models
- Compared performance between models

✅ 7. Model Evaluation

- 📉 Evaluated using RMSE and MAE
- 🏆 Selected best model based on lowest error

| Model	| RMSE	| MAE |
|-------|-------|------------------------|
| Linear Regression	| ✅ Best |	Low Error |
| LSTM	|❌ Poor	|High Error |


📌 Selected Model: Logistic Regression (as baseline/simple model reference)

<img width="1035" height="528" alt="image" src="https://github.com/user-attachments/assets/a83828df-6ee3-4e36-8a0b-a90e8897e818" />


✅ 8. Feature Importance

- Identified key drivers: lag features, momentum, spread
- Analyzed impact of each feature on prediction
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
