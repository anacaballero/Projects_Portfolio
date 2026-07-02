# Applied Data Science — Project Portfolio

Applied projects across demand forecasting, risk classification, and statistical analysis.

---

## Bike-Sharing Demand Forecasting

Neural network for time-series demand prediction, applied to a public bike rental system to optimize fleet allocation across stations.

**Problem:** Operators need to pre-position bikes based on expected demand. Under-stocking loses customers; over-stocking wastes capital. The model predicts hourly ridership from weather, time-of-day, and calendar features.

**Approach:** Feedforward neural network with full manual implementation — forward pass, backpropagation, and stochastic gradient descent. Feature engineering includes one-hot encoding of cyclical time variables and min-max normalization of continuous inputs.

**Stack:** `Python` `NumPy` `pandas` `matplotlib`

---

## Loan Default Prediction

Comparative evaluation of four classification algorithms on historical loan application data, predicting default risk across borrower profiles.

| Model | Metric |
|---|---|
| k-Nearest Neighbors | Jaccard + F1 |
| Decision Tree | Jaccard + F1 |
| Support Vector Machine | Jaccard + F1 |
| Logistic Regression | Jaccard + F1 + Log Loss |

**Stack:** `Python` `scikit-learn` `pandas` `NumPy`

---

## Statistical Inference Studies (R)

Three inferential analyses on large public datasets:

**BRFSS dataset** — Health and BMI distributions across the US population by gender; significance testing of demographic differences.

**GSS (1972–2012)** — Political leaning differences by race; hypothesis testing and confidence interval estimation.

**Movie audience scores** — Linear regression model for predicting ratings; feature selection, multicollinearity analysis, and model diagnostics.

**Stack:** `R` `ggplot2` `dplyr` `tidyr`
