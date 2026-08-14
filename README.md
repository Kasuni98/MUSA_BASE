# 🍌 MUSA-BASE: Mobile Application for Banana Farmers

> **A comprehensive mobile application designed to minimize challenges in banana production during pre-harvest and post-harvest periods.**

---

## 📌 Project Overview
**Musa-Base** is a user-friendly mobile application developed as a 4th-year research project at the **Sri Lanka Institute of Information Technology (SLIIT)**. It leverages cutting-edge technologies—including **Machine Learning (ML), IoT-based approaches, Natural Language Processing (NLP), and Image Processing**—to enhance the quality, productivity, and sustainability of banana cultivation for both smallholder and commercial producers.

---

## 📄 Publication & Citation
This research has been published in the **2023 International Conference on Innovative Computing, Intelligent Communication and Smart Electrical Systems (ICSES)**, IEEE, Chennai, India[cite: 3].
* **DOI:** `10.1109/ICSES60034.2023.10465553`[cite: 3]
* **IEEE Xplore Link:** [https://ieeexplore.ieee.org/document/10465553](https://ieeexplore.ieee.org/document/10465553)[cite: 3]

---

## 🛠️ In-Depth Tools & Technologies Used

### 1. Frontend Development & Mobile Platform
* **Framework:** **Flutter**[cite: 3]
* **Target Platform:** Android-compatible mobile devices[cite: 3]

### 2. Core Modules, Algorithms & Technologies

| Module | Technologies & Algorithms Used | Key Functionality |
| :--- | :--- | :--- |
| **Crop Yield & Harvest Prediction** | • Machine Learning Classifiers (KNN, Decision Tree, Random Forest, SVM, Logistic Regression, Naive Bayes, Gradient Boosting)[cite: 3]<br>• Time-series data conversion (lag differencing and data scaling)[cite: 3] | Predicts banana harvest quantity and optimal harvest time using plant properties (variety, agroclimatic region, plant density, soil pH, sunlight, watering schedule, leaves, and height)[cite: 3]. |
| **Disease Identification (Image Processing)** | • **Mask-RCNN** (Instance Segmentation)[cite: 3]<br>• Fuzzy Logic (for infection severity grading)[cite: 3]<br>• Comparative models tested: ANN, Random Forest, SVM, Decision Tree, Naive Bayes, and Minimum Distance Classifier[cite: 3] | Automatically detects and classifies plant diseases and pest symptoms from leaf and plant images to minimize crop loss[cite: 3]. |
| **Bilingual Chatbot** | • **Random Forest Algorithm** (selected based on evaluation metrics)[cite: 3]<br>• Custom Knowledge Base[cite: 3] | Provides interactive conversational support in both **Sinhala and English** to diagnose diseases, symptoms, and recommend preventive treatments[cite: 3]. |
| **Watering & Fertilizer Recommendations** | • **Gradient Boosting Classifier** (selected via ROC-AUC analysis)[cite: 3]<br>• Custom CNN (for soil image classification)[cite: 3]<br>• Weather API & Soil Moisture Sensors[cite: 3] | Generates personalized irrigation schedules and fertilizer plans by analyzing soil properties, moisture levels, and real-time weather data[cite: 3]. |

---

## 🔍 System Architecture & Data Methodology
* **Data Sources:** Integrates banana plant images, IoT sensor data (soil moisture), weather parameters (temperature, humidity, and rainfall via Weather API), and user questionnaire feedback[cite: 3].
* **Evaluation Metrics:** Models were rigorously evaluated using precision, recall, F1-score, accuracy, confusion matrices, and ROC-AUC curves[cite: 3].

---

## 📦 Getting Started & Installation

### Prerequisites
* Flutter SDK installed
* Python 3.x environment
* PostgreSQL database configured
