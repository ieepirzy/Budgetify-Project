# Algorithms Wiki — For Personal Finance App Development
*Curated algorithms & methods for forecasting, behavioral modeling, and adaptive learning.*

---

## 1. Time Series Forecasting (Financial Prediction)

### ARIMA (AutoRegressive Integrated Moving Average)
- Use Case: Predicting future financial data based on past trends.
- Notes: Handles non-stationary data. Good for univariate time series.
- Links:  
[Wikipedia](https://en.wikipedia.org/wiki/Autoregressive_integrated_moving_average)

---

### SARIMA (Seasonal ARIMA)
- Use Case: Same as ARIMA but better for data with clear seasonality (e.g., monthly spending spikes).
- Notes: Adds seasonal components.

---

### Prophet (Meta/Facebook)
- Use Case: Forecasting with messy, real-world data (missing values, trend shifts).
- Notes: Designed for business forecasting. Easy to use.
- Links:  
[Prophet Official](https://facebook.github.io/prophet/)

---

### Holt-Winters Method (Exponential Smoothing)
- Use Case: Quick forecasting with smoothing techniques.
- Notes: Great for trend + seasonality.

---

## 2. Behavioral Modeling & Prediction

### Markov Chains
- Use Case: Predict next user action based on current state (e.g., spending behavior patterns).
- Notes: Memoryless property — future depends only on present state.
- Links:  
[Wikipedia](https://en.wikipedia.org/wiki/Markov_chain)

---

### Hidden Markov Models (HMM)
- Use Case: Modeling unobservable behavior patterns (latent variables).
- Notes: Useful for inferring "why" behind actions.

---

### Clustering Algorithms
- K-Means  
- DBSCAN  
- Gaussian Mixture Models (GMM)

Use Case: Grouping users by behavior type automatically.

---

## 3. Learning Algorithms (Adaptive Systems)

### Reinforcement Learning
- Use Case: Teaching the app to nudge users better over time based on reward feedback (habits formed, goals met).
- Algorithms:  
- Q-Learning  
- Deep Q Networks (DQN)  
- Policy Gradient Methods  
- Links:  
[Wikipedia](https://en.wikipedia.org/wiki/Reinforcement_learning)

---

### Anomaly Detection Algorithms
(Detecting unusual spending)

- Isolation Forest  
- One-Class SVM  
- Autoencoders (Neural Nets)  

Use Case: Notify user of unusual activity (fraud alert, abnormal spend).

---

## 4. Other Relevant Concepts

### Kalman Filter
- Use Case: Real-time estimation with noisy data (live transaction feeds).
- Notes: Widely used in control systems and financial signal processing.
- Links:  
[Wikipedia](https://en.wikipedia.org/wiki/Kalman_filter)

---

## Recommended Reading Order:
1. Time Series Forecasting (ARIMA → Prophet → Holt-Winters)
2. Markov Chains & Clustering (Behavior Prediction)
3. Reinforcement Learning Basics
4. Anomaly Detection Techniques
5. Kalman Filter (Advanced)

---

> "*Knowledge is power — structured knowledge is acceleration.*"

