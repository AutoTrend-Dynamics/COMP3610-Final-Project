# COMP3610-Final-Project

# Predicting Vehicle Listings Price Using Machine Learning

This project presents a machine learning-based solution to help dealers, sellers and car buyers understand used car prices through data exploration, predictive modeling, a dashboard interface, and an API for programmatic price prediction.


## API
A FastAPI that returns car price predictions from the trained Random Forest model for real-time predictions.

### Example input
```bash
{
  "Rating": 4.5,
  "Mileage": 50000,
  "Year": 2018,
  "Make": "Honda",
  "State": "NY",
  "EngineType": "Gasoline"
}
```

### Example Output
```bash
{
  "predicted_price": 16230.50
}
```
Output: Predicted Price (USD)


API can be accessed: http://127.0.0.1:8002/docs (API code must be running in background)


## Streamlit Dashboard

Live Dashboard can be accessed: https://car-pricing-advisor.streamlit.app/

To run locally:

```bash
streamlit run dashboard/dashboard.py
