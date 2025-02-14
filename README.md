# 🏋️‍♂️ Fitness & Lifestyle Prediction Model  

## 🔍 Overview  
This project is part of **NEXUS’25 - DIGITAL VJTI (INNOVIZE Round 1)**. The goal is to develop a **Machine Learning model** that predicts whether an individual is healthy or not based on their **physical fitness, diet, activity level, sleep habits, mindfulness, and career choices**. Additionally, we built a **Streamlit web application** to provide an interactive platform for users to input their details and get real-time predictions.  


We used **Random Forest and SVM models** to classify individuals as **healthy (1) or unhealthy (0)** and visualized **decision boundaries** for analysis.  

---

## 📂 Dataset Details  
The dataset consists of **6,000 entries**, with the following attributes:  

- **phy_fitness** (Physical Fitness Level)  
- **diet_preferences**  
- **activity_level**  
- **sleep_habits**  
- **mindfulness**  
- **career**  
- **gender**  
- **daily_avg_steps**  
- **daily_avg_calories**  
- **Target Variable**: `is_healthy` (**1 = Healthy, 0 = Unhealthy**)  

---

## 🛠️ Technologies Used  
✅ **Python**  
✅ **Pandas, NumPy** (Data Preprocessing)  
✅ **Scikit-Learn** (Machine Learning Models)  
✅ **Matplotlib, Seaborn** (Visualization)  
✅ **Flask** (API Deployment)  
✅ **Streamlit** (Web App for Predictions)  
✅ **Google Colab / Jupyter Notebook**  

---

## 📊 Model Training & Performance  
We trained and tested **two ML models**:  

- **Random Forest Classifier**  
- **Support Vector Machine (SVM)**  

📌 **Final Accuracy Scores:**  
✅ **Random Forest Classifier** – **Accuracy: 92.88%**  
✅ **Support Vector Machine (SVM)** – **Accuracy: 92.29%**  

---

## 📈 Decision Boundary Visualization  
To analyze model predictions, we plotted a **decision boundary** using **phy_fitness** and **mindfulness** attributes.  



---


