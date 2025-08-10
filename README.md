# 🚖 Uber Trip Analysis & Forecasting

A complete Data Science project focusing on Uber trip demand patterns using FOIL Uber data from January–February 2015. The project applies EDA, machine learning forecasting, and model interpretability techniques to uncover insights about ride-hailing trends and peak demand.

---

## 📌 Objective

To identify the key factors influencing Uber trip counts and to build predictive models that forecast hourly/daily demand based on time, vehicle activity, and operational factors.

---

## 🧰 Tools & Technologies Used

- **Python** – Data Cleaning, Preprocessing, EDA, and Modeling
- **Google Colab** – Development Environment
- **Pandas, NumPy** – Data Manipulation
- **Matplotlib, Seaborn** – Data Visualization
- **Scikit-learn** – Model Building and Evaluation
- **XGBoost, Random Forest, Gradient Boosting** – Forecasting Models
- **SHAP** – Model Explainability and Interpretability
- **SQLite** – In-memory SQL Analysis
- **CSV** – Dataset Handling and Exporting Results

---

## 📁 Dataset

- Source: FOIL (Freedom of Information Law) Uber Jan–Feb 2015 dataset
- Total Rows: 31,683
- Features include:
  - `date` – Date of record
  - `dispatching_base_number` – Uber base code
  - `active_vehicles` – Number of active Uber vehicles
  - `trips` – Number of trips for that base & date

---

## 📊 Visualizations Created

1. **Daily Trips Line Plot** – Trend of trips over Jan–Feb 2015
2. **Heatmap** – Average trips by Weekday and Week number
3. **Bar Plot** – Average trips per weekday
4. **Hourly Aggregation** – Demand variations across hours of the day
5. **User Behavior Clustering** – Hour vs. weekday patterns (K-Means)
6. **SHAP Beeswarm Plot** – Global feature importance for trip prediction
7. **SQL Query Output** – Top Uber bases by trip volume

---

## 🧠 Key Insights

- Fridays and Saturdays consistently show the highest demand.
- Peak hours are during morning and evening commute times.
- Active vehicle count is strongly correlated with trip volume.
- Certain bases maintain consistently high trip counts across weeks.

---

## 📈 Model Building

- Models Used:
  - XGBoost Regressor
  - Random Forest Regressor
  - Gradient Boosting Regressor
- Evaluation Metric: Mean Absolute Percentage Error (MAPE)
- Ensemble prediction created using weighted averaging based on model MAPE scores.
- Model Interpretation: SHAP visualizations for global and local feature impact.

---

## 🧾 Output & Export

- Cleaned dataset exported as: `uber_data_cleaned.csv`
- Forecast results saved as: `uber_trip_forecast.csv`
- EDA visuals, SHAP plots, and SQL outputs generated during execution

---

## 🔮 Future Scope

- Extend analysis to cover full-year datasets for seasonal insights
- Integrate weather and event data for enhanced predictions
- Deploy interactive dashboards via Streamlit or Flask
- Explore deep learning models (LSTM, Prophet) for time-series forecasting

---

## 🙌 Acknowledgements

- Dataset: NYC Taxi & Limousine Commission (via FOIL)
- Tools: Google Colab, SHAP, scikit-learn, XGBoost
- Inspired by: Real-world ride-hailing demand prediction systems

---

## 📬 Contact

**Nikita Gupta**  
📧 [Email](mailto:nikitagpt06@gmail.com)  
🔗 [LinkedIn](https://www.linkedin.com/in/nikita-gupta-790a54284/)  
💻 [GitHub](https://github.com/Nikita-Gupta-19)

