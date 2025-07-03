# Time Series Sales Forecasting using Machine Learning & Statistical Models

A comprehensive time series forecasting project using ML and statistical models to predict future retail sales and support strategic decision-making.

## 🎯 Objectives

- Anticipate consumer demand across stores and product categories.
- Optimize inventory levels and reduce overstocking or understocking.
- Use external variables (holidays, promotions, oil prices, etc.) to enhance forecast accuracy.

## 📊 Dataset

Sourced from the Favorita Grocery Sales dataset. Key files:

- `train.csv`: Historical sales data (2013–2017)
- `test.csv`: Data for future predictions
- `transactions.csv`: Store-level transaction volume
- `oil.csv`: Daily oil prices
- `holidays_events.csv`: Local and national holiday events
- `stores.csv`: Metadata about stores

## 🧠 Approach & Methodology

1. **Data Preprocessing**  
   - Missing value treatment, outlier handling  
   - Feature scaling (MinMax) and encoding (One-hot)

2. **Feature Engineering**  
   - Promotional flags, holiday indicators, date decomposition

3. **Modeling Techniques**  
   - Linear Regression  
   - Random Forest Regressor  
   - Gradient Boosting Regressor  
   - ARIMA (for univariate time series)

4. **Evaluation Metrics**  
   - MSE, RMSE, RMSLE, MAE

5. **Best Performing Model**  
   - Random Forest with hyperparameter tuning

6. **Streamlit Interface**  
   - Upload data, select model, visualize actual vs predicted sales  
   - View forecasting output interactively

## 🖥️ Streamlit Features

- View and explore training/test datasets  
- Compare model performances  
- Forecast and visualize future sales  
- Interactive UI with options like `pandas.ai` integration

## 🔮 Future Scope

- **Custom Dashboards**: Interactive filtering and drill-down capability  
- **Geo-Spatial Analysis**: Map-based sales insights  
- **Cloud Deployment**: Serverless architecture using AWS/GCP/Azure

## 📁 Files Included

- `Time Series Sales Forecasting.ipynb`: Main implementation notebook  
- `Time Series Sales Forecasting (comparison of models).ipynb`: Model performance comparison  


## 📌 Conclusion

This project provides a robust forecasting solution for retail sales leveraging both machine learning and classical time series methods, with an extensible Streamlit interface for end-user interaction.

## 📝 License

This project is open-source and available for educational and non-commercial use.
