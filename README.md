# Air_Quality
# 🌫️ Air Quality Analysis and Forecasting

## 📌 Objective
Analyze and model air quality data in India to understand pollution patterns and predict future air quality levels.

---

## 📂 Dataset
- **Period**: 2015–2020
- **Size**: ~320,000 records
- **Features**: City, Date, PM2.5, PM10, NO2, SO2, CO, O3, Temperature, Wind Speed, Humidity

---

## 🛠️ Tools & Libraries
- `Python`
- `Pandas`, `NumPy`, `Matplotlib`, `Seaborn`
- `Scikit-learn`, `XGBoost`
- `Streamlit` *(for interactive dashboard - optional)*

---

## 📊 Key Steps

### 🔹 1. Data Cleaning
- Handled **missing values** using imputation techniques.
- Detected and removed outliers using **IQR method**.
- Converted timestamps and ensured consistency in data types.

### 🔹 2. Exploratory Data Analysis (EDA)
- Identified most polluted cities and seasons.
- Correlation between weather conditions and pollutant levels.
- Visualized time trends using line plots and heatmaps.

### 🔹 3. Feature Engineering
- Created new features like `AQI_Category` and `Season`.
- Applied rolling averages for smoothing.

### 🔹 4. Machine Learning Modeling
- Used **XGBoost Regression** to predict PM2.5 levels.
- Compared with **Linear Regression** and **Random Forest**.
- Evaluation using `RMSE`, `MAE`, and `R²`.

### 🔹 5. Dashboard (Optional)
- Built an interactive dashboard using **Streamlit**.
- Users can select a city and see pollution trends and forecasts.

---

## 📈 Results
- Best model: **XGBoost** with RMSE = `7.9` and R² = `0.91`
- Visual insights: Delhi and Kanpur had highest pollution levels.
- Seasonal peaks observed in **Winter** due to low wind speed.


---

## 🧠 What I Learned
- Real-world handling of large environmental datasets (320k+ rows)
- Imputing environmental sensor data using ML
- Building regression models for time-series-like data
- Deploying dashboards for public use

---

## 📌 Future Work
- Integrate weather APIs for real-time prediction
- Use LSTM model for time-series forecasting
- Apply models to other countries’ data (e.g., Spain, Egypt)

---

## 🙋 About Me
I'm **Abdelrahman Ahmed**, a Junior Data Scientist passionate about solving real-world problems using data.  
Check out more of my work on [GitHub](https://github.com/YourUsername) and [LinkedIn](https://linkedin.com/in/YourProfile).
