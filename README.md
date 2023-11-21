# EnergyPrediction-Arima-Transformer

## 1) Energy Consumption.xlsx:

The provided dataset, Energy Consumption.xlsx, captures monthly energy consumption over a span of 50 years, from June 1970 to May 2020. Each data point in the Excel file represents the energy consumption value for a specific month. This comprehensive record serves as the foundation for the exploratory analysis and time series modeling conducted in the following Jupyter Notebooks.

## 2) Arima.ipynb:

This Jupyter Notebook is a crucial part of the Energy Consumption Prediction Project, encompassing the exploratory analysis. It includes a stationarity check using ADF tests, identification of trends and periodicity through visual inspection and decomposition, and the removal of trends and periodic components using techniques such as differencing, decomposition, or Fourier transformation. The notebook covers model selection considerations, such as ARIMA, SARIMA, or other advanced options, based on insights from the exploratory analysis. It also details model order estimation, evaluation using diagnostic tests on residuals, and selection criteria employing AIC and BIC. The forecasting stage involves predicting future values on a validation set, ensuring a robust and accurate approach to energy consumption prediction.

## 3) Transformer.ipynb:

This Jupyter Notebook is a vital component of the Energy Consumption Prediction Project, focusing on time series analysis and deep learning. It details a comprehensive feature extraction process, including lag features, rolling statistics, interaction features, seasonal features, rate of change, cumulative sum, EWMA statistics, additional statistics, z-scores, and log returns. The modeling approach adopts the Transformer model for its ability to capture temporal dependencies and handle irregular patterns. Post-modeling evaluation includes ACF and PACF analysis, Shapiro-Wilk tests, and histogram distribution analysis for residuals. The notebook concludes with valuable recommendations, emphasizing dynamic feature selection, consistent feature scaling, incorporation of temporal features, and a commitment to continuous model improvement. The holistic approach showcased integrates feature engineering, advanced techniques, and meticulous model evaluation for robust energy consumption predictions.
