# 🌿 Plant Disease Detection using Deep Learning

## 📌 Overview

This project detects plant diseases from leaf images using a deep learning model. It classifies images into three categories:

* Healthy
* Rust
* Fungus

The system provides predictions through both a Flask API and a Streamlit web interface.

---

## 🧠 Model Details

* CNN-based model trained on plant leaf dataset
* Input size: 225x225
* Image preprocessing with normalization
* Output: Nme  for each class it belong to 

---

## ⚙️ Tech Stack

* Python
* TensorFlow / Keras
* OpenCV
* Flask (API)
* Streamlit (UI)

---

## 🚀 Features

* Upload leaf image
* Real-time disease prediction
* Web interface using Streamlit
* Flask backend for API-based prediction

---

## 📂 Project Structure

```
plant-disease-detection/
│── app.py
│── model.h5
│── Model_Training.ipynb
│── requirements.txt
│── templates/
│── uploads/
│─static/
│── README.md
```

---

## ▶️ How to Run

### 1. Clone repo

```
git clone https://github.com/bibrajessica/plant-disease-detection.git
cd plant-disease-detection
```

### 2. Install dependencies

```
pip install -r requirements.txt
```

### 3. Run Flask app

```
python app.py
```

### 4. Run Streamlit UI

```
streamlit run app.py
```

---

## 📊 Output

The model predicts:

* Healthy 🌿
* Rust 🍂
* Fungus 🦠

---

## 🚀 Future Improvements

* Add more plant disease classes
* Improve accuracy using transfer learning (ResNet, EfficientNet)
* Deploy on cloud (AWS / Render)
* Add mobile-friendly UI

---

## 📌 Author

Jessica Bibra
AI/ML Engineer
