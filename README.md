

# 🏥 AI Medical Diagnosis System

### Advanced Multi-Disease Prediction & Healthcare Guidance Web App

An AI-powered healthcare web application built using **Machine Learning + Streamlit** that predicts multiple diseases and provides intelligent health recommendations including diet, yoga, home remedies, emergency advice, and nearby doctor search.

---

## 🚀 Live Demo

👉 **[Open AI Medical Diagnosis System](https://ai-medical-diagnosis-tushant.streamlit.app/)**


## 📌 Project Overview

The **AI Medical Diagnosis System** is an interactive web-based platform designed to assist users in predicting various medical conditions using trained machine learning models.

This system integrates:

* 🧠 Predictive Machine Learning Models
* 📄 OCR-based Lab Report Analyzer
* 📊 Real-time Disease Prediction
* 🩺 Health Guidance System
* 📍 Nearby Doctor & Hospital Finder

The application is developed as a practical implementation of AI in healthcare diagnostics.

---

## 🎯 Diseases Covered

The system predicts the following conditions:

* 🩸 Diabetes
* ❤️ Heart Disease
* 🧠 Parkinson’s Disease
* 🫁 Lung Cancer
* 🧬 Hypo-Thyroid

Each prediction includes:

* Result (Positive / Negative)
* Probability score (if available)
* Diet recommendations
* Yoga & exercise suggestions
* Daily home remedies
* Emergency precautions
* Medication precautions
* Nearby specialist search

---

## 🚀 Key Features

### 🔹 1. Multi-Disease Prediction

Users can manually enter medical values or upload reports to receive AI predictions.

### 🔹 2. OCR-Based Lab Report Analyzer

Users can upload lab report images.
The system extracts medical values using **pytesseract OCR** and automatically fills prediction forms.

### 🔹 3. Intelligent Health Guidance

For each disease, the system provides:

* Preventive measures
* Recommended diet
* Foods to avoid
* Yoga asanas
* Home remedies
* Emergency medical guidance

### 🔹 4. Nearby Doctor & Hospital Finder

Integrated Google Maps search for:

* Cardiologists
* Endocrinologists
* Neurologists
* Pulmonologists

Based on selected disease and location.

### 🔹 5. Prediction History

Stores user prediction records during session.

### 🔹 6. Clean & Interactive UI

Modern glassmorphism UI design with background effects and interactive components.

---

## 🧠 Machine Learning Models

The system uses **Random Forest Classifiers** trained on real-world medical datasets.

### Models Included:

* `diabetes_model.sav`
* `heart_disease_model.sav`
* `parkinsons_model.sav`
* `lungs_disease_model.sav`
* `Thyroid_model.sav`

Models are loaded dynamically from the `Models/` folder.

---

## 📊 Technologies Used

### 🔹 Programming Language

* Python

### 🔹 Framework

* Streamlit

### 🔹 Machine Learning

* scikit-learn
* Random Forest Classifier

### 🔹 Data Handling

* pandas
* numpy

### 🔹 Visualization

* matplotlib
* seaborn

### 🔹 OCR

* pytesseract

### 🔹 Image Processing

* Pillow (PIL)

---

## 📂 Project Structure

```
AI-Medical-Diagnosis-System/
│
├── app.py
├── requirements.txt
├── README.md
│
├── Models/
│   ├── diabetes_model.sav
│   ├── heart_disease_model.sav
│   ├── parkinsons_model.sav
│   ├── lungs_disease_model.sav
│   └── Thyroid_model.sav
│
├── datasets/
│   ├── diabetes_data.csv
│   ├── heart_disease_data.csv
│   ├── parkinson_data.csv
│   ├── hypothyroid.csv
│   └── survey lung cancer.csv
│
├── notebooks/
│   ├── Heart_Disease_Prediction.ipynb
│   ├── Lung_Cancer.ipynb
│   ├── Parkinson's_Disease_Detection.ipynb
│   └── Thyroid.ipynb
```

---

## ▶ How To Run The Project Locally

### Step 1: Clone Repository

```
https://github.com/tushant687/AI-Medical-Diagnosis-System/tree/main
cd AI-Medical-Diagnosis-System
```

### Step 2: Install Dependencies

```
pip install -r requirements.txt
```

### Step 3: Run Application

```
streamlit run app.py
```

The app will open in your browser.

---

## 📈 Sample Use Case

1. Upload medical lab report image
2. OCR extracts values like:

   * Glucose
   * TSH
   * Cholesterol
3. Click prediction button
4. Get:

   * AI result
   * Health advice
   * Nearby doctors

---

## 🔐 Data Privacy

* No external data storage
* No cloud database
* Session-based temporary storage only
* Google Maps used only for doctor search

---

# 📷 Dashboard Preview
 <img width="1816" height="886" alt="Screenshot 2026-02-15 171917" src="https://github.com/user-attachments/assets/4b42a08f-b2ad-4ffe-b7a7-0af47dd8637e" />
 
<img width="1887" height="747" alt="Screenshot 2026-02-15 171934" src="https://github.com/user-attachments/assets/ad371952-1392-4716-a794-4f60c3232ea7" />
<img width="1431" height="811" alt="Screenshot 2026-02-15 171949" src="https://github.com/user-attachments/assets/9b43e855-20ba-4522-8f15-6b2cb9bda8a3" />
<img width="1859" height="827" alt="Screenshot 2026-02-15 172011" src="https://github.com/user-attachments/assets/6acc9903-8292-430c-9db3-73c6f17d7659" />
<img width="1492" height="835" alt="Screenshot 2026-02-15 172050" src="https://github.com/user-attachments/assets/28e290ed-840a-4181-9921-1dcc6dc1b071" />
<img width="1439" height="810" alt="Screenshot 2026-02-15 172110" src="https://github.com/user-attachments/assets/0ae098f6-5ebe-42ac-8fb9-f8c413d94e4f" />


---

## ⚠ Important Disclaimer

This application is for **educational and informational purposes only**.

* It does NOT replace professional medical advice.
* AI predictions may not be 100% accurate.
* Always consult a qualified healthcare professional.

---

## 👨‍💻 Developed By

Tushant Kumar

Under the supervision of
Ms. Srishti Agarwal (Assistant Professor)

Meerut Institute of Technology, Meerut

---
