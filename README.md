# 🌱 Crop Recommendation System

## Overview

The Crop Recommendation System is a web-based application designed to assist farmers and agricultural experts in identifying the most suitable crop for cultivation based on soil and environmental factors. The system leverages machine learning to analyze key parameters such as Nitrogen, Phosphorus, Potassium, Temperature, Humidity, pH level, and Rainfall. By processing this data, the application delivers accurate crop suggestions tailored to local conditions.

**Dataset used:** [Crop Recommendation Dataset (Kaggle)](https://www.kaggle.com/datasets/atharvaingle/crop-recommendation-dataset)

---

## Features

* 🌾 **User-Friendly Interface** – Simple form for entering soil and climate data.
* 🤖 **ML-Powered Predictions** – Trained model recommends the best crop.
* 🎨 **Responsive UI** – Built with HTML, CSS, and Bootstrap for clean usability.
* ⚡ **Fast & Efficient** – Quickly processes inputs to generate recommendations.
* 📈 **Scalable** – Future-ready for additional environmental features and advanced ML integration.

---

## Technologies Used

* **Frontend:** HTML, CSS (Bootstrap)
* **Backend:** Flask (Python)
* **Machine Learning Model:** scikit-learn
* **Dataset:** Crop Recommendation Dataset (CSV)

---

## How It Works

1. User enters soil nutrients (N, P, K) and climate conditions (temperature, humidity, pH, rainfall).
2. Data is preprocessed and fed into the trained ML model.
3. The model predicts the most suitable crop.
4. The recommended crop is displayed on the web interface.

---

## Example Usage

**Input:**
Nitrogen = 50, Phosphorus = 30, Potassium = 20, Temperature = 25°C, Humidity = 70%, pH = 6.5, Rainfall = 100 mm

**Output:**
🌾 *Rice is the best crop to be cultivated right now.*

---

## Future Enhancements

* 🌍 Integration with real-time weather APIs for dynamic predictions.
* 📊 Use of advanced ML models (Random Forest, Deep Learning) for higher accuracy.
* 📡 Mobile app integration for broader accessibility.

---

## License

This project is open-source and distributed under the **MIT License**.
