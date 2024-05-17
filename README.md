# M5-Forcasting-Accuracy

## Slides & Kaggle Link
[Slides link](https://docs.google.com/presentation/d/1je-sG98GJZwzrhGTfzMmSXuKxgYhRlcM/edit?usp=sharing&ouid=113313002084083777814&rtpof=true&sd=true)  
[Kaggle Competition link](https://www.kaggle.com/competitions/m5-forecasting-accuracy)

## Introduction
This project is part of the Kaggle competition "M5 Forecasting - Accuracy." The objective of this competition is to forecast daily sales for Walmart, considering the hierarchical structure of product categories and store locations. Accurate forecasts will help with better product allocation, inventory management, and overall operational efficiency.

## Data
The dataset provided for this competition includes:
- **Sales Data:** Daily sales data for various products.
- **Calendar Data:** Information about special events, holidays, and other important dates.
- **Price Data:** Historical price data for each product.

The full dataset can be accessed from the Kaggle competition page: [M5 Forecasting - Accuracy datasets](https://www.kaggle.com/competitions/m5-forecasting-accuracy/data)

## Methodology
1. **Data Exploration:**
   - Understanding the structure of the dataset.
   - Visualizing sales trends and identifying patterns.

2. **Feature Engineering:**
   - Creating new features based on the calendar data (e.g., holidays, weekends).
   - Encoding categorical variables (e.g., product categories, store IDs).

3. **Modeling:**
   - Training various machine learning models, including:
     - Linear Regression
     - `Light Gradient Boosting Machines (Light GBM)`
     - `LSTM Neural Networks`
   - Evaluating model performance using appropriate metrics (RMSE).

4. **Hyperparameter Tuning:**
   - Using cross-validation to tune the hyperparameters of the models to improve accuracy.

## Results
- **Model Performance:** The performance of each model is evaluated using the Rooted Mean Squared Error (RMSE) metric.
- **Feature Importance:** Analyzing which features contribute most to the accuracy of the forecasts.
- **Visualizations:** Graphical representation of the forecasts compared to the actual sales data.

