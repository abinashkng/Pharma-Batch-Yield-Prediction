# Pharma-Batch-Yield-Prediction

OBJECTIVE: Predict batch yield based on process parameters

DATA: 100 pharmaceutical batches with temperature, humidity, mixing time, ingredient ratio

METHODOLOGY:
- Linear regression model
- Train/test split (80/20)
- Features: temperature, humidity, mixing_time, ingredient_ratio
- Target: batch_yield

RESULTS:
- R² score: 0.85 (model explains 85% of variance)
- RMSE: 2.3% (average prediction error)
- Most important feature: temperature (0.45 correlation)

INSIGHTS:
1. Temperature is strongest predictor of yield
2. Optimal temperature range: 65-70°C
3. Model can predict yield within ±2.3% accuracy

BUSINESS VALUE:
- Predict batch outcomes before completion
- Optimize process parameters
- Reduce rejected batches

TOOLS: Python, pandas, scikit-learn, matplotlib
