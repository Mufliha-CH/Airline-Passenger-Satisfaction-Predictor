# ✈️ Airline Passenger Satisfaction Predictor

A Machine Learning web application that predicts whether an airline passenger is **Satisfied** or **Neutral/Dissatisfied** based on passenger details, flight information, and service ratings.

---

## 📌 Project Overview

This project uses an **XGBoost Classifier** to predict airline passenger satisfaction. The model is trained on airline passenger data and deployed as an interactive **Streamlit** web application.

Users can enter passenger information such as travel class, flight distance, service ratings, and delays to receive an instant prediction.

---

## 🚀 Features

- Predict passenger satisfaction in real time
- Interactive Streamlit web application
- User-friendly interface
- Data preprocessing and feature scaling
- Label encoding for categorical features
- Machine Learning model using XGBoost

---

## 🛠️ Technologies Used

- Python
- Streamlit
- Pandas
- NumPy
- Scikit-learn
- XGBoost
- Joblib

---

## 📂 Project Structure

```
Airline-Passenger-Satisfaction-Predictor/
│
├── app.py
├── Airline_Prediction.ipynb
├── ml prjct.csv
├── project org.pkl
├── scaler.pkl
├── le.pkl
├── le1.pkl
├── le2.pkl
├── le3.pkl
├── requirements.txt
├── README.md
└── images/
    ├── home.png
    └── satisfied.png
```

---

## 📷 Application Screenshots

### 🏠 Home Page

![Home](images/home.png)

---

### ✅ Prediction Result

![Satisfied](images/satisfied.png)

---

## ⚙️ Installation

Clone the repository

```bash
git clone https://github.com/yourusername/Airline-Passenger-Satisfaction-Predictor.git
```

Move into the project folder

```bash
cd Airline-Passenger-Satisfaction-Predictor
```

Install the required libraries

```bash
pip install -r requirements.txt
```

Run the Streamlit application

```bash
streamlit run app.py
```

---

## 📊 Model

**Algorithm**

- XGBoost Classifier

**Preprocessing**

- Label Encoding
- Feature Scaling
- Data Cleaning

---

## 🎯 Future Improvements

- Probability score for predictions
- Model explainability using SHAP
- Cloud deployment
- Dark mode UI
- Batch prediction using CSV upload

---

## 👩‍💻 Author

**Mufliha CH**

- LinkedIn: https://www.linkedin.com/in/mufliha-ch
- GitHub: https://github.com/Mufliha-CH

---

⭐ If you found this project helpful, consider giving it a star!
