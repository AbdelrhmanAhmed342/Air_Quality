# Air Quality Prediction

Predicting PM2.5 air pollution levels using machine learning. This project involves comprehensive data analysis, feature engineering, and model building with XGBoost.

**🔗 [Open Full Project in Google Colab](https://colab.research.google.com/github/AbdelrhmanAhmed342/Air_Quality/blob/main/Air%20Quality.ipynb)**

## Project Overview
This project aims to forecast PM2.5 concentrations based on historical air quality data from multiple Indian cities. The workflow includes data cleaning, exploratory data analysis (EDA), feature engineering, model training with XGBoost, and evaluation.

## Technical Highlights
- **Data Handling:** Processed over 320,000+ rows of temporal sensor data.
- **Feature Engineering:** Created time-based features (hour, day, month) and lag features.
- **Model:** Built an XGBoost Regressor for forecasting.
- **Tools:** Pandas for data wrangling, Scikit-learn for ML, Matplotlib/Seaborn for visualization.

## Results
The XGBoost model successfully captured trends in air pollution data and provided accurate forecasts, demonstrating the effectiveness of tree-based models for temporal environmental data.

## How to Use
The best way to explore this project is to open the Jupyter notebook in Colab using the link above. It requires no setup and runs in the cloud.

### Run Locally
1. Clone the repo: `git clone https://github.com/AbdelrhmanAhmed342/Air_Quality.git`
2. Install requirements: `pip install -r requirements.txt`
3. Open the notebook: `jupyter notebook "Air Quality.ipynb"`

## Dataset
Source: [Air Quality Data - Indian Cities](https://www.kaggle.com/datasets/rohanrao/air-quality-data-in-india) (Kaggle)
