
# Sydney Olympic Park Apartment Price Prediction – Linear Regression Project

My first data science project ever, this project explores predicting apartment prices in SOP (State of Property) using regression techniques. The goal is to determine which factors most influence property prices and how well a model can generalise predictions based on historical data.

---

## Dataset

The dataset was collected manually through data from real estate websites (realestate.com.au and domain.com.au), and contains records of apartment sales and includes variables, namely:

- Address
- Number of Bedrooms
- Number of Bathrooms
- Number of Parking Spots
- Study Room (Yes or No)
- Area in m²
- Sale price (target)

The dataset is provided as `property.csv` in the project directory.

---

## Models and Methods

The notebook walks through:
- **Data Cleaning & Preprocessing**
- **Train/Test Split and Training Models**
- **Model Evaluation**
  - Metrics: RMSE, R²

---

## Results Summary

- The regression model captured the general price trends effectively. (0.845 R² Score on best model)
