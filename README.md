# 🏠 Real-Estate-price-Predication
Developed a cross-platform Real Estate Price prediction model using regression model, achieving a prediction accuracy of 85%. 
Implemented data preprocessing techniques including normalization, and dataset splitting, handling over 10,000 city 
records to ensure robust training and validation process. 
Optimized model parameter using grid search(chatgpt) and cross- validation, resulting in a 20% reduction in prediction error. 
Integrated a user-friendly web interface to input property details and display predicted prices, enhancing accessibility and usability.

A machine learning project that predicts real estate property prices based on features like location, square footage, number of bedrooms, and bathrooms. This project demonstrates the use of data preprocessing, feature engineering, model training, and deployment for real-world regression tasks.

## 📌 Features

- 📊 Exploratory Data Analysis (EDA)
- 🧹 Data preprocessing and cleaning
- 🛠️ Feature engineering
- 🤖 Machine learning model for price prediction
- 📈 Model evaluation (R² Score, RMSE)
- 🌐 Web interface using Flask (optional)
- 📁 Exported model using `joblib` or `pickle`

## 🛠️ Tech Stack

- Python 3.x
- Jupyter Notebook / VS Code
- Pandas, NumPy
- Scikit-learn
- Matplotlib, Seaborn
- Flask (for deployment)
- Joblib / Pickle (for saving model)

## 🧠 Algorithms Used

- Linear Regression (baseline)
- Lasso & Ridge Regression
- Decision Tree Regressor
- Random Forest Regressor
- 🧪 Sample Prediction
Once the app is running, input features like:

Location: "Bangalore"

Area: 1200 sqft

Bedrooms: 3

Bathrooms: 2

And get an estimated price like: ₹ 75 Lakhs

📊 Model Evaluation
R² Score: ~0.85

RMSE: ~₹ 7.5 Lakhs

Cross-validation used for robust performance

📌 Future Improvements
 Add more cities and advanced location encoding

 Use geospatial data (lat/long)

 Add support for real-time datasets via APIs

 Improve frontend design

 Dockerize the application

🤝 Contributing
Contributions are welcome! Fork the repo, create a branch, make changes, and open a pull request.

📄 License
This project is licensed under the MIT License
