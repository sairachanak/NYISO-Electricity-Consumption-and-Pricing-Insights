NYISO Electricity Pricing and Load AnalysisProject OverviewThis project analyzes New York Independent System Operator (NYISO) electricity market data to predict pricing, detect anomalies, and forecast demand using real-time streaming data. The system processes time-series electricity data using PySpark Structured Streaming and machine learning models.Course: Applied Big Data Analytics - GWU
Dataset: NYISO Electricity Pricing and Load Data

Predict Locational Based Marginal Prices using historical load demand patterns
Linear Regression and Random Forest models implemented
Achieved RMSE of 8-9 for Linear Regression model
Feature engineering with lag features and exponential weighted moving averages
2. Anomaly Detection in Price Spikes

ARIMA-based time series anomaly detection
Identifies unusual price spikes due to grid conditions, congestion, or losses
Dynamic thresholding using Median Absolute Deviation (MAD)
Real-time anomaly flagging in streaming data
3. Load Demand Forecasting

Forecast Integrated Load based on historical LBMP and grid conditions
Incorporates marginal costs from congestion and transmission losses
Time-series modeling with temporal features
