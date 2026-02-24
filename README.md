# ❤️ AI Heart Attack Prediction System

A full-stack Machine Learning web application that predicts the risk of a heart attack using medical parameters. The system uses a Random Forest Classifier trained on clinical data and provides real-time predictions through an interactive and animated web interface.

---

## 🚀 Features

* Predict heart attack risk using ML model
* Modern animated frontend (React + Tailwind CSS)
* Fast backend API using Flask
* Real-time prediction results
* Professional medical UI design
* REST API integration
* Fully responsive design

---

## 🧠 Machine Learning Model

Algorithm used:

* Random Forest Classifier

Input features:

* Age
* Gender
* Heart Rate
* Systolic Blood Pressure
* Diastolic Blood Pressure
* Blood Sugar
* CK-MB
* Troponin

Output:

* Heart Attack Risk (0 = No Risk, 1 = Risk)
* Risk Probability (%)

---

## 🏗️ Project Structure

```
heart_attack_prediction-main/
│
├── backend/
│   ├── app.py
│   ├── heart_model.pkl
│
├── src/
│   ├── components/
│   ├── pages/
│
├── index.html
├── package.json
├── vite.config.ts
```

---

## ⚙️ Installation and Setup

### 1. Clone the repository

```
git clone https://github.com/yourusername/heart-attack-prediction.git
cd heart-attack-prediction
```

---

### 2. Install frontend dependencies

```
npm install
```

Run frontend:

```
npm run dev
```

Frontend runs at:

```
http://localhost:5173
```

---

### 3. Setup backend

Go to backend folder:

```
cd backend
```

Install dependencies:

```
pip install flask flask-cors numpy scikit-learn
```

Run backend:

```
python app.py
```

Backend runs at:

```
http://127.0.0.1:5000
```

---

## 🔗 API Endpoint

Prediction endpoint:

```
POST /predict
```

Example JSON input:

```
{
  "age": 45,
  "gender": 1,
  "heart_rate": 80,
  "systolic_bp": 130,
  "diastolic_bp": 85,
  "blood_sugar": 120,
  "ck_mb": 4.5,
  "troponin": 0.02
}
```

Output:

```
{
  "prediction": 0,
  "probability": 0.12
}
```

---

## 🛠️ Technologies Used

Frontend:

* React
* TypeScript
* Tailwind CSS
* Vite
* Framer Motion

Backend:

* Python
* Flask
* Scikit-learn
* NumPy

Machine Learning:

* Random Forest Classifier
* Pandas
* Scikit-learn

---

## 📊 Model Accuracy

Accuracy achieved:

```
98.78%
```

---

## 🎯 Use Cases

* Medical risk assessment
* Healthcare applications
* Educational ML projects
* Clinical decision support systems

---

## 👨‍💻 Author

Developed by: Abdul Karim

---

## 📄 License

This project is for educational and research purposes.
