# 🚗 Predictive Analytics for Fair Valuation in the Indian Used Car Market  

## 📌 Project Overview  
The used car market in India is highly dynamic, with prices influenced by multiple factors such as brand, model, mileage, vehicle condition, and market trends. This variability often makes it difficult for sellers to determine accurate prices and for buyers to assess whether a listed price is fair.  

This project leverages **Machine Learning (ML)** to build a **Used Car Price Prediction Model** trained on the **CarDekho dataset**, enabling accurate, data-driven valuation of used cars.  

---

## 🎯 Objectives  
- Develop a robust ML model for predicting used car prices.  
- Ensure accurate and reliable estimates for both buyers and sellers.  
- Enhance market transparency and efficiency through data-driven insights.  

---

## 🛠️ Tech Stack  
- **Programming Language:** Python  
- **Libraries & Frameworks:**  
  - Data Processing: `pandas`, `numpy`  
  - Visualization: `matplotlib`, `seaborn`  
  - Machine Learning: `scikit-learn`, `xgboost`  
- **Environment:** Jupyter Notebook / Google Colab  
- **Dataset:** CarDekho Used Car Price Dataset  

---

## 📂 Dataset Description  

| Feature            | Description |
|--------------------|-------------|
| `car_name`         | Full name of the car (brand + model) |
| `brand`            | Brand name of the car |
| `model`            | Specific model name |
| `seller_type`      | Type of seller (dealer, individual, etc.) |
| `fuel_type`        | Type of fuel (Petrol, Diesel, CNG, LPG, Electric) |
| `transmission_type`| Transmission system (Manual/Automatic) |
| `vehicle_age`      | Age of the vehicle in years |
| `mileage`          | Mileage (km per litre) |
| `engine`           | Engine capacity in cc |
| `max_power`        | Maximum power in BHP |
| `seats`            | Number of seats |
| `selling_price`    | Price of the used car (**target variable**) |

---

## 🔄 Project Workflow  

1. **Importing Libraries and Dependencies**  
2. **Understanding the Dataset**  
3. **Data Preprocessing**  
   - Handling missing values  
   - Encoding categorical features  
   - Feature scaling  
4. **Exploratory Data Analysis (EDA)**  
   - Distribution analysis  
   - Correlation analysis  
   - Feature importance  
5. **Feature Selection**  
6. **Train-Test Split**  
7. **Model Selection**  
   - Gradient Boosting  
   - XGBoost Regressor  
   - Random Forest Regressor  
8. **Hyperparameter Tuning**  
   - `GridSearchCV` / `RandomizedSearchCV`  
9. **Model Evaluation**  
   - RMSE, MAE, R² Score  
10. **Conclusion & Insights**  

---

## 📊 Model Performance  

### Gradient Boosting Regressor  
- Train R²: **0.9841** | Test R²: **0.9376**  
- Test RMSE: **216,663** | Test MAE: **100,032**  

### XGBoost Regressor  
- Train R²: **0.9764** | Test R²: **0.8730**  
- Test RMSE: **309,164** | Test MAE: **112,356**  

### Random Forest Regressor  
- Train R²: **0.9775** | Test R²: **0.9353**  
- Test RMSE: **220,703** | Test MAE: **102,046**  

✅ **Best Model:** Gradient Boosting Regressor (highest test R² and best generalization)  

---

## ✅ Conclusion  
- The **Gradient Boosting model** emerged as the best performer, achieving a Test R² of **0.9376**, ensuring strong predictive capability and generalization.  
- **Random Forest** performed competitively, while **XGBoost** showed slight deterioration after tuning.  
- This model provides **fair valuation insights** for both buyers and sellers in the Indian used car market.  

---

## 📌 Benefits  

- **For Sellers:** More accurate pricing, faster sales, and improved profit margins.  
- **For Buyers:** Better decision-making by identifying competitively priced vehicles.  
- **For Market:** Greater transparency, trust, and efficiency.  

---

## 📜 Future Enhancements  

- Deploy the model as a **web app** using Flask / FastAPI + Streamlit/Dash.  
- Incorporate **real-time market trend data** for dynamic pricing.  
- Explore **deep learning approaches** for further performance improvement.  

---

## 📎 References  

- **Dataset:** [Kaggle - CarDekho Used Car Price Prediction](https://www.kaggle.com/code/manishkr1754/cardekho-used-car-price-prediction/input)  
- **Libraries:** [scikit-learn](https://scikit-learn.org), [XGBoost](https://xgboost.readthedocs.io)  
