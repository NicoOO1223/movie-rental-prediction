# 🎬 Movie Rental Prediction (ML Project)

This project uses **machine learning models** to predict how long a movie rental will last, based on features such as film attributes, rental rates, and special features.  

## 📌 Project Overview
- Dataset: `rental_info.csv`
- Target: `rental_length_days` (difference between `rental_date` and `return_date`)
- Models:
  - Lasso Regression (feature selection + prediction)
  - Random Forest Regressor (best performance)
- Evaluation Metric: Root Mean Squared Error (RMSE)

## 🛠️ Features Used
- `release_year` – year the movie was released  
- `amount` – rental amount  
- `rental_rate` – cost of renting  
- `length` – runtime (minutes)  
- `replacement_cost` – replacement cost of the film  
- `deleted_scenes`, `behind_the_scenes` – special features flags  
- Rating dummies: `NC-17`, `PG`, `PG-13`, `R`  

## 📊 Results
- **Lasso Regression**: Provided feature selection and identified most relevant predictors.
- **Random Forest**: Achieved the best accuracy with an RMSE of ~XX days (replace with your value).

### Example Feature Importance (Random Forest)
- `rental_rate` – most significant predictor
- `replacement_cost` – important cost-related feature
- `release_year` – moderate effect
- Special features (`deleted_scenes`, `behind_the_scenes`) – minor effect


