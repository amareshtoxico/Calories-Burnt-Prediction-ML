

# 🔥 Calories Burnt Prediction – Machine Learning Web Application
[![Live Demo](https://img.shields.io/badge/Demo-Live%20App-success?style=for-the-badge&logo=render)](https://calories-burnt-prediction-ml.onrender.com)

An end-to-end **Machine Learning powered web application** that predicts the number of calories burnt during physical activity based on user fitness and health parameters.

This project is built as a **portfolio-grade ML system**, combining a clean machine learning pipeline, Flask backend, and a modern enterprise-style dark UI with interview-friendly demo features.

---

## 🚀 Key Highlights

- 🔢 Accurate **Calories Burnt Prediction** using a trained regression model  
- 🎥 **Auto-Demo Mode** for instant project demonstration in interviews  
- 📊 **Prediction Confidence Bar** for result interpretability  
- 🧪 Robust **Input Validation & Error Handling**  
- 🌙 Modern **Dark UI (Enterprise-grade design)**  
- 📱 Fully **Responsive Layout**  
- ⚡ Fast predictions using pre-trained model & scaler  

---

## 🧠 Machine Learning Workflow

1. User enters fitness and workout details  
2. Numerical features are scaled using a trained `StandardScaler`  
3. Scaled features are combined with categorical inputs  
4. A regression model predicts calories burnt  
5. Results are displayed with confidence visualization  

---

## 🛠️ Technology Stack

### Frontend
- HTML5  
- CSS3 (Custom Dark UI)  
- Responsive Grid Layout  

### Backend
- Python  
- Flask  

### Machine Learning
- NumPy  
- Scikit-learn  
- Regression Model  
- Feature Scaling (StandardScaler)  

---

## 📂 Project Structure

```

calories-burnt-prediction-ml/
│
├── app.py                 # Flask application
├── reg_model.pkl          # Trained ML model
├── scalar.pkl             # Feature scaler
│
├── templates/
│   └── index.html         # UI template
│
├── static/
│   └── style.css          # Custom styling
│
└── README.md

````

---

## ▶️ How to Run the Project Locally

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/amareshtoxico/calories-burnt-prediction-ml.git
cd calories-burnt-prediction-ml
````

### 2️⃣ Create & Activate Virtual Environment

```bash
python -m venv venv
venv\Scripts\activate   # Windows
```

### 3️⃣ Install Dependencies

```bash
pip install flask numpy scikit-learn
```

### 4️⃣ Run the Application

```bash
python app.py
```

### 5️⃣ Open in Browser

```
http://127.0.0.1:5000
```

---

## 🎥 Auto-Demo Mode (Interview-Ready Feature)

The **Auto-Demo** button automatically generates realistic fitness inputs and produces predictions instantly.

**Why it’s useful:**

* No manual data entry required
* Perfect for live interviews and quick demos
* Demonstrates the full ML pipeline in one click

---

## 🎯 Use Cases

* Fitness & health analytics platforms
* Workout tracking systems
* Machine Learning portfolio project
* Flask + ML integration reference
* Academic and learning purposes

---

## 🔮 Future Improvements

* Real confidence score using model uncertainty
* Model explainability (Feature importance / SHAP)
* Cloud deployment (Render / Railway)
* User activity history & analytics dashboard

---

## 👨‍💻 Author

**Amaresh Virupakshi**
Machine Learning & Python Developer



