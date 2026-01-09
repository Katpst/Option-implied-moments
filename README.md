This project studies how option prices can be used to recover risk-neutral
probability distributions and moments (mean, variance, skewness, kurtosis)
of a future underlying variable.

We implement and compare multiple option-implied methods and show that
higher-order moments are weakly identified in practice due to limited
strike coverage.

### Methods implemented

- **Breeden–Litzenberger (1978)**  
  Non-parametric recovery of the risk-neutral density via price curvature.

- **Spline-smoothed BL estimator**  
  Practical implementation with finite-sample regularization.

- **Model-free moment diagnostics (BKM framework)**  
  Used for robustness and identification analysis (illustrative).


