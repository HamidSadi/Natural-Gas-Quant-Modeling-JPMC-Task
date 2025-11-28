# Natural Gas Storage Optionality Valuation  
### Advanced Quantitative Research Project  
*(OU Model • Monte-Carlo Simulation • Time-Series Decomposition • Forward Curve Construction)*

This project delivers a complete quantitative analysis of natural gas market data, building a forward curve from monthly observations, calibrating a mean-reversion model, performing Monte-Carlo simulations, and valuing intrinsic and extrinsic storage optionality.

It is based on the structure of **J.P. Morgan Quantitative Research Virtual Experience – Task 1**, but extended into a full professional-grade quant workflow.

---

## 📌 Key Features

### ✔ Comprehensive Time-Series Analysis
- Exploratory Data Analysis (EDA)
- STL seasonal decomposition
- Trend / seasonal / residual inspection
- ADF & KPSS stationarity tests
- ACF & PACF correlation structure
- Rolling volatility analysis
- Distributional analysis of residuals

### ✔ Forecasting Models
- Holt-Winters Exponential Smoothing (ETS)
- ARIMA(2,1,2) forecasting
- Comparison of forecast behaviors

### ✔ Forward Curve Construction
- Monthly-to-daily interpolation via Cubic Splines
- Seasonal component reconstructed from STL
- Trend extended 1 year into the future
- Fully corrected date-handling to prevent misalignment
- Professionally styled forward curve visualization

### ✔ Ornstein–Uhlenbeck (OU) Mean-Reversion Calibration
- Calibration of κ (mean reversion speed)
- θ (long-run equilibrium)
- σ (volatility)
- Widely used model for commodity spot/forward dynamics

### ✔ Monte-Carlo Simulation (OU Process)
- 300+ price paths simulated over 365 days
- OU dynamics:
  \[
  dP_t = \kappa(\theta - P_t)\,dt + \sigma\, dW_t
  \]
- Simulated price distribution used for optionality estimates

### ✔ Storage Optionality Valuation
- **Intrinsic Value**: max–min of forward curve
- **Extrinsic Value**: expected value of simulated spreads
- **Total Storage Value = Intrinsic + Extrinsic**
- Mirrors real natural-gas physical storage economics





