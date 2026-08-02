# Forest Weather Index (FWI) Prediction using Machine Learning

A Flask-based web application that predicts the **Forest Weather Index (FWI)** using a trained **Ridge Regression** model. Users can enter weather conditions through a clean web interface and instantly receive the predicted FWI value.

---

## 📌 Project Overview

The Forest Weather Index (FWI) is a numerical rating that indicates the potential intensity of forest fires based on weather conditions.

This project follows a complete Machine Learning workflow:

- Data Cleaning & Preprocessing
- Exploratory Data Analysis (EDA)
- Feature Engineering
- Model Training & Evaluation
- Model Serialization using Pickle
- Flask Web Application
- Responsive Frontend using HTML & CSS

---

## 🚀 Features

- Predict Forest Weather Index (FWI)
- Ridge Regression model
- StandardScaler preprocessing
- Real-time predictions through Flask
- Clean and intuitive interface

---

## 🛠️ Tech Stack

### Machine Learning

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn

### Backend

- Flask
- Pickle

### Frontend

- HTML5
- CSS3
- Jinja2
- Font Awesome

---

## 📊 Input Features

| Feature | Description | Unit |
|----------|-------------|------|
| Temperature | Air Temperature | °C |
| Relative Humidity | Relative Humidity | % |
| Wind Speed | Wind Speed | km/h |
| Rainfall | Daily Rainfall | mm |
| FFMC | Fine Fuel Moisture Code | Index |
| DMC | Duff Moisture Code | Index |
| ISI | Initial Spread Index | Index |
| Fire Class | Fire / Not Fire | Categorical |
| Region | Bejaia / Sidi Bel-Abbes | Categorical |

---

## 📁 Project Structure

```
Algerian-Forest-Fires/
│
├── application.py
├── requirements.txt
├── .gitignore
│
├── models/
│   ├── ridge.pkl
│   └── scaler.pkl
│
├── static/
│   └── css/
│       └── style.css
│
├── templates/
│   └── home.html
│
└── notebooks/
    └── EDA_and-FE.ipynb
    └── model_training.ipynb

```

---

## ⚙️ Installation

Clone the repository

```bash
git clone https://github.com/yourusername/Algerian-Forest-Fires.git
```

Move into the project directory

```bash
cd Algerian-Forest-Fires
```

Create a virtual environment

```bash
conda create -p .venv python=3.10
```

Activate the environment

```bash
conda activate .venv
```

Install the required dependencies

```bash
pip install -r requirements.txt
```

Run the Flask application

```bash
python application.py
```

Open your browser and visit

```
http://127.0.0.1:5000
```

---

## 📈 Machine Learning Workflow

1. Data Cleaning
2. Exploratory Data Analysis (EDA)
3. Feature Selection
4. Train-Test Split
5. Feature Scaling
6. Model Training
7. Hyperparameter Tuning
8. Model Evaluation
9. Model Deployment using Flask

---

## 📚 Dataset

**Algerian Forest Fires Dataset (2012)**

The dataset contains meteorological observations collected from two regions in Algeria:

- Bejaia Region
- Sidi Bel-Abbes Region

The target variable is the **Forest Weather Index (FWI)**.

---


## ⭐ If you found this project useful, consider giving it a star!
