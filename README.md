# Flight Booking Prediction (✈️ British Airways)

![image alt](https://github.com/parthgiht/British-Airways-Customer-Buying-Behavior-Prediction/blob/a6f9588ab2d310d6e45dc895e1073959a0191bc6/British%20Airways-1.jpg)

## ❓ Problems:
-  Modeling	lounge	eligibility	at	Heathrow	Terminal	3
-  Predicting	customer	buying	behaviour

## 🎯 Overview 
This project aims to predict customer behavior in flight bookings using machine learning techniques. By analyzing various features such as purchase lead time, flight hour, length of stay, and geographical factors, we build models to understand and forecast booking patterns. The project involves exploratory data analysis (EDA) and the application of RandomForest and XGBoost algorithms to predict a target variable, likely related to booking completion or flight delay likelihood.

## 🧠 Technologies used 
- **Python**: Core programming language for data analysis and modeling.
- **Pandas**: Data manipulation and analysis.
- **Numpy**: Numerical computations.
- **Matplotlib**: Data visualization.
- **Seaborn**: Enhanced data visualization.
- **Scikit-learn**: Machine learning algorithms and tools.
- **RandomForest**: Decision tree framwork for advanced modeling.
- **XGBoost**: Gradient boosting framework for advanced modeling.


## 📁 Project Structure
- Data Analysis:
  - Contain exploratory data analysis (EDA) od a flight booking dataset.
  - Includes statistical summaries (eg., describe() output for columns like `num_passengers`, `purchase_lead`, `length_of_stay`, `flight_hour`, and `flight_duration`).
 
- Model Prediction:
   - Focuses on data preprocessing, including handling missing values and encoding categorical variables.
   - Implements training, evaluation, and feature importance analysis using RandomForest and XGBoost models.
   - Visualizes the top 10 important features identified by each model.
   - Model evaluation metrics:
      - **Accuracy**, **Precision**, **Recall**, **F1-Score**, **ROC-AUC**


## 🔑 Key Findings 
- RandomForest Model:
   - Top predictors include `purchase_lead`, `flight_hour`, and `length_of_stay`, emphasizing the role of booking timing and trip duration.
   - Other significant features: num_passengers and flight_duration, highlighting group size and travel time influences.

- XGBoost Model:
   - Emphasizes geographical factors, with `booking_origin` (e.g., Australia, Malaysia, Taiwan) as a key predictor.
   - Specific routes (e.g., ICNPEN, PENTPE, BTUPER) also play a critical role, suggesting route-specific patterns or efficiencies.
 
- Exploratory Data Analysis (EDA):
   - The correlation heatmap reveals relationships between numerical features, aiding in understanding data structure.
   - Statistical descriptions provide insights into feature distributions (e.g., average purchase_lead of ~84 days, flight_duration ranging from 4.67 to 9.5 hours).
 
     
