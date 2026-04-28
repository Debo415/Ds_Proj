# Ds_Proj
Crop_recommendation_model
🌾 Crop Recommendation System
A machine learning web application that recommends the most suitable crop to grow based on soil nutrients and climate conditions.

📌 Project Overview
Farmers often struggle to decide which crop to grow based on their soil and climate conditions. This project solves that problem using a Random Forest Classifier trained on soil and weather data to recommend the best crop with 99.5% accuracy.

📊 Dataset
Source: Kaggle - Crop Recommendation Dataset
Rows: 2200
Classes: 22 crops
Balance: Perfectly balanced — 100 samples per crop
Crops Covered
Rice, Maize, Chickpea, Kidneybeans, Pigeonpeas, Mothbeans, Mungbean, Blackgram, Lentil, Pomegranate, Banana, Mango, Grapes, Watermelon, Muskmelon, Apple, Orange, Papaya, Coconut, Cotton, Jute, Coffee

🧪 Features Used
Feature	Description	Range
N	Nitrogen content in soil	0 – 140
P	Phosphorus content in soil	5 – 145
K	Potassium content in soil	5 – 205
Temperature	Temperature in °C	8.83 – 43.68
Humidity	Relative humidity in %	14.26 – 99.98
pH	Soil pH value	3.50 – 9.94
Rainfall	Rainfall in mm	20.21 – 298.56
🤖 Model
Algorithm: Random Forest Classifier
Library: Scikit-learn
Pipeline: StandardScaler + RandomForestClassifier
Accuracy: 99.5%
Train/Test Split: 80/20 with stratification
📁 Project Structure
crop-recommendation-system/ ├── app.py # Streamlit web app ├── crop_recommendation_model.pkl # Trained Random Forest model ├── label_encoder.pkl # Label encoder for crop names ├── crop_recommendation.ipynb # Full Colab notebook └── README.md # Project documentation

📷 Web App
Enter the following inputs to get a crop recommendation:

Nitrogen, Phosphorus, Potassium values
Temperature and Humidity
Soil pH
Rainfall
The app instantly recommends the best crop for your conditions.

📈 Results
Metric	Value
Accuracy	99.5%
Model	Random Forest
Classes	22 crops
Test Samples	440
🛠️ Tech Stack
Python
Scikit-learn — ML model
Pandas & NumPy — Data processing
Matplotlib & Seaborn — Visualization
Streamlit — Web application
👤 Author
Deboborni Guha Roy
📄 License
This project is open source and available under the MIT License.
