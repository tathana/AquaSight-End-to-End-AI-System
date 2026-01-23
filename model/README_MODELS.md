## Model Usage Guide

### Production Models
- ARIMA models are used for Secchi Depth and TSI.
- SVM (RBF) models are used for Chlorophyll-a.

### Research Models
- LSTM (Full Feature) models are trained for TSI
  for performance comparison with literature.

All models are trained using time-based splits and evaluated
using RMSE and MAE metrics.
