# 📦 Supply Chain Management System – Machine Learning Based

---

## 🧾 Objective

The primary objective of this project is to **optimize and forecast different components** of supply chain management, such as **demand forecasting**, **inventory optimization**, and **supplier performance analysis**, using machine learning models.

---

## 🚀 Features – Key Functionalities

* 🔍 **Demand Forecasting**: Predict future demand using time-series and regression models.
* 📦 **Inventory Optimization**: Maintain optimal stock levels to reduce holding and shortage costs.
* 🛒 **Supplier Performance Evaluation**: Analyze and rank suppliers based on performance metrics.
* 📊 **Dashboard Visualization**: Interactive charts to track supply chain KPIs.
* ⚠️ **Risk Prediction**: Detect potential disruptions in the supply chain using classification techniques.

---

## 🧰 Technology Used

| **Component**       | **Technology Stack**                                     |
| ------------------- | -------------------------------------------------------- |
| **Languages**       | Python                                                   |
| **Libraries**       | Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn, Plotly |
| **ML Frameworks**   | Scikit-learn, XGBoost, Prophet (for time series)         |
| **Visualization**   | Streamlit (for interactive dashboards)                   |
| **Data Storage**    | CSV, SQLite (optional integration)                       |
| **Version Control** | Git, GitHub                                              |

---

## ⚙️ How It Works – Project Workflow

1. **Data Collection**: Import datasets related to supply chain operations (sales, inventory, supplier logs).
2. **Preprocessing**: Clean, normalize, and engineer features for model readiness.
3. **Model Training**: Apply suitable ML models (forecasting, classification, clustering).
4. **Evaluation**: Measure performance using RMSE, MAE, accuracy, F1-score, etc.
5. **Visualization**: Display key metrics using interactive dashboard.
6. **Prediction**: Users input data and get real-time predictions or recommendations.

---

## 📥 Data Collection

* **Source**: Kaggle Supply Chain Dataset and synthetic data generation
* **Description**: Dataset includes order date, product type, inventory status, delivery performance, and supplier score
* **Method**: Downloaded via Kaggle API and processed using Python scripts

---

## 🎮 Controls (If Interactive)

* Input parameters for forecast (product ID, region, date range)
* Filter suppliers based on score threshold
* Adjust inventory reorder thresholds
* Real-time prediction through Streamlit form inputs

---

## 🧠 ML Techniques Used

* **Linear Regression / Random Forest** – For demand prediction
* **XGBoost Classifier** – For supply chain risk prediction
* **K-Means Clustering** – For supplier segmentation
* **Prophet** – For time-series forecasting
* **PCA (Optional)** – For dimensionality reduction in high-dimensional datasets

---

## 🏋️ Model Training

* **Train/Test Split**: 80/20
* **Cross-Validation**: 5-fold used for hyperparameter tuning
* **Feature Importance**: Visualized using SHAP and feature importance plots

---

## 📤 Output Explanation

* **Forecast Graphs**: Plots showing predicted vs actual demand
* **Risk Alerts**: Binary label output showing “At Risk” or “Stable”
* **Supplier Rank**: Normalized performance score from 0 to 100
* **Inventory Health Score**: Composite score based on holding cost, shortage risk, and lead time

---

## 🔮 Future Work

* Integrate with real-time APIs for live data streaming
* Add anomaly detection for logistics tracking
* Deploy with Docker + FastAPI for scalable production use

---


