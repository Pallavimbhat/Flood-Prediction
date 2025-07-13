# 🌊 Flood Prediction Using AI - EDA and ML/DL Approach

## 🔍 1. Overview
This project develops an AI-based flood prediction system using **Machine Learning (ML)** and **Deep Learning (DL)** techniques.  
By analyzing data on rainfall, river discharge, soil moisture, and atmospheric pressure, it predicts flood occurrence, severity, and timing.  
It combines exploratory data analysis (EDA), supervised learning models, and spatial visualizations to aid disaster preparedness and decision-making.

## 🎯 2. Objectives
- Build a robust, data-driven flood prediction model using ML & DL.
- Process and analyze environmental data for effective model training and testing.
- Evaluate multiple models: Naïve Bayes, KNN, SVM, Random Forest, ANN, LSTM.
- Visualize data distributions and geographic patterns to derive actionable insights.

## 📊 3. Dataset
- Sources: government portals, Kaggle, GitHub.
- ~3,500 records with 15 features (both numerical and categorical).
- Target: `level` indicating flood risk or severity class.

## ⚙️ 4. Methodology
1. **🧹 Data Preprocessing**
   - Handle missing values using mean, median, or mode.
   - Encode categorical data (label or one-hot encoding).
   - Scale numerical features for consistency.

2. **📊 Exploratory Data Analysis (EDA)**
   - Create scatterplots, boxplots, distribution plots, heatmaps to explore relationships and spot outliers.

3. **🤖 Model Training & Evaluation**
   - ML: Naïve Bayes, KNN, SVM, Random Forest, Bootstrap Forest.
   - DL: ANN, LSTM (for time-series).
   - Split data into 80% train and 20% test.
   - Metrics: Accuracy, Precision, Recall, F1-score, R².

4. **🗺️ Visualization & Interpretation**
   - Use Taylor diagrams to compare models on correlation, standard deviation, RMSE.
   - Apply SHAP analysis to understand feature impact.
   - Map spatial differences in flood risk across regions.

## 🏆 5. Results
- LSTM achieved highest accuracy (~98-99%) for time-series forecasting.
- Random Forest offered a strong balance of performance and interpretability.
- SHAP revealed Full Reservoir Level and Storage as most influential.
- Geographic analysis showed high variability in regions like Kerala and Himachal Pradesh.

## 📈 6. Key Visuals
- Scatterplots of cumulative rainfall vs water level.
- Boxplots comparing water levels across states.
- Taylor diagrams for model performance.
- GMDH and ANFIS graphs revealing deeper feature interactions.

## 🚀 7. Future Work
- Integrate real-time IoT and drone data for richer predictions.
- Explore advanced hybrid & ensemble techniques like XGBoost, LightGBM.
- Develop interactive dashboards for policy makers and local agencies.
- Standardize datasets and metrics to improve cross-study comparisons.
