# Prophet and ARIMA Modelling for Time Series Forecasting

### Student Details
- **Name:** Mhle L.  
- **Student Number:** 22322987  

---

## 📊 Project Overview
This project applies **ARIMA** and **Facebook Prophet** models to forecast pollution levels from a multivariate time series dataset.  

We follow the **full data science life cycle**:
1. **Data Upload & Extraction** – Manually upload and extract dataset from Kaggle.
2. **Data Understanding** – Explore dataset structure, types, missing values, duplicates.
3. **Data Preparation & Cleaning** – Convert date columns, handle missing values, set index.
4. **Data Visualization** – Plot time series and perform seasonal decomposition.
5. **ARIMA Forecasting** – Build and evaluate ARIMA model.
6. **Prophet Forecasting** – Build and evaluate Prophet model.
7. **Model Comparison** – Compare ARIMA vs Prophet with MAE, RMSE, and MAPE.
8. **Conclusion** – Identify the better model for this dataset.

---

## 📂 Dataset
- **Source:** [Kaggle – LSTM Datasets (Multivariate & Univariate)](https://www.kaggle.com/datasets/rupakroy/lstm-datasets-multivariate-univariate?resource=download)  
- **Files included:**
  - `LSTM-Multivariate_pollution.csv` → main dataset with pollution time series.  
  - `pollution_test_data1.csv` → secondary test dataset.  

---

## 📈 Models & Evaluation
- **Models used:** ARIMA, Prophet  
- **Metrics:** MAE, RMSE, MAPE  

**Findings:**  
Prophet outperformed ARIMA across all evaluation metrics, making it the better forecasting model for this dataset.

---

## 📹 References
- [YouTube: ARIMA vs Prophet Forecasting Explained][(https://www.youtube.com/watch?v=M2etf-FcM6c) ](https://youtu.be/FRPq1b5Qbv0?si=5TRHpZEGnyI8xllY) 
- [Kaggle Dataset](https://www.kaggle.com/datasets/rupakroy/lstm-datasets-multivariate-univariate?resource=download)



## ✅ Conclusion
Prophet proved to be the better forecasting model, achieving lower **MAE, RMSE, and MAPE** compared to ARIMA.  
This project demonstrates how time series forecasting can be applied to real-world environmental datasets using Python.

