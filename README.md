# Real-Estate-Price-Prediction
 A machine learning web application that predicts home prices in Bangalore based on user input — including area (square feet), number of BHKs, bathrooms, and location. The project uses a regression model trained on real estate data and is deployed via a simple Flask-powered UI.



 Features

- Cleaned and preprocessed Bangalore housing dataset
- Feature engineering including one-hot encoding for location
- Trained a Linear Regression model using Scikit-learn
- Predicts prices based on:
  - Total square feet
  - Number of bedrooms (BHK)
  - Number of bathrooms
  - Location
- Frontend form for input
- Real-time price prediction via Flask backend



 Technologies Used

- Python (Pandas, NumPy, Scikit-learn)
- Jupyter Notebook (for data exploration and model training)
- Flask (backend API for serving predictions)
- HTML/CSS/JavaScript (frontend interface)
- PyCharm (for development)



How It Works

1. User enters square footage, selects BHK, bathrooms, and location from the form.
2. Frontend sends the data to the Flask server via a POST request.
3. Flask uses the trained model to predict the price.
4. The estimated price is returned and shown on the UI.

---



