# 🌱 OptiCrop – Smart Agricultural Production Optimization Engine

## 📖 Overview

OptiCrop is a Machine Learning-based crop recommendation system that helps farmers identify the most suitable crop based on soil nutrients and environmental conditions.

The application uses a trained **Random Forest Classifier** to analyze seven agricultural parameters and recommend the best crop along with prediction confidence, water requirement, suitable temperature range, and crop description.

---

## 🎯 Problem Statement

Selecting the right crop is essential for improving agricultural productivity. Traditional crop selection often depends on experience and local knowledge, which may not always provide optimal results.

OptiCrop uses Machine Learning to provide accurate crop recommendations based on soil and climatic conditions.

---

## ✨ Features

- 🌱 Crop Recommendation using Machine Learning
- 📊 Random Forest Model (99.32% Accuracy)
- 🎯 Prediction Confidence Score
- 💧 Water Requirement
- 🌡️ Suitable Temperature Range
- 📖 Crop Description
- ✅ Client-side Validation
- ✅ Server-side Validation
- 🔄 Reset Functionality
- 🌐 Responsive Web Interface

---

## 🛠️ Tech Stack

### Frontend

- HTML5
- CSS3
- Bootstrap
- JavaScript

### Backend

- Python
- Flask

### Machine Learning

- Scikit-learn
- Pandas
- NumPy
- Pickle

---

## 📂 Project Structure

```
OptiCrop/
│
├── data/
├── models/
├── static/
├── templates/
├── app.py
├── train.py
├── notebook.ipynb
├── requirements.txt
└── README.md
```

---

## 📊 Dataset

**Dataset:** Crop Recommendation Dataset

Input Features:

- Nitrogen
- Phosphorous
- Potassium
- Temperature
- Humidity
- Soil pH
- Rainfall

Output:

- Recommended Crop

---

## 🤖 Machine Learning Models

| Model | Accuracy |
|--------|---------:|
| Logistic Regression | 96.36% |
| K-Nearest Neighbors | 95.68% |
| Decision Tree | 98.64% |
| ⭐ Random Forest | **99.32%** |

Random Forest was selected as the final model.

---

## 🚀 Installation

Clone the repository

```bash
git clone https://github.com/Dharshansai-k/OptiCrop-Samrt-Agricultural-Production-Optimization-Engine
```

Create virtual environment

```bash
python -m venv venv
```

Activate virtual environment

Windows

```bash
venv\Scripts\activate
```

Install dependencies

```bash
pip install -r requirements.txt
```

Train the model

```bash
python train.py
```

Run the application

```bash
python app.py
```

Open

```
http://127.0.0.1:5000
```

---

## 💻 Sample Input

| Parameter | Value |
|-----------|------:|
| Nitrogen | 90 |
| Phosphorous | 42 |
| Potassium | 43 |
| Temperature | 22.5 |
| Humidity | 82 |
| Soil pH | 6.5 |
| Rainfall | 202 |

Expected Output:

```
Crop: Rice
```

---

## 🎥 Demo Video

Demo Video Link:

```
https://drive.google.com/file/d/1KNItLjFhLaOx5ngeXC4p1PvhdMhtLtmr/view?usp=sharing
```

---
---

## 🔮 Future Enhancements

- Weather API Integration
- Fertilizer Recommendation
- Disease Detection
- Cloud Deployment
- Mobile Application
- IoT Integration

---

## 👨‍💻 Developer

**Kalavakunta Dharshan Sai**

B.Tech CSE

RGUKT RK Valley

---

## 📄 License

This project was developed for academic purposes under the APSCHE AI & ML Internship Program.
