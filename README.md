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
## Google Colab link
https://colab.research.google.com/drive/1JWuby5oYW8wqVXYyVO7FW_Mx9yYoElKk?usp=sharing

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
## 🎯 Conclusion  

In this project, we successfully developed a **Machine Learning-based Health Prediction Model** using **Random Forest and SVM classifiers**. The model achieved a high accuracy of **92.88% (Random Forest)** and **92.29% (SVM)**, demonstrating its effectiveness in predicting an individual's health status based on lifestyle factors.  

To make the model more accessible, we built a **Streamlit web application**, allowing users to input their details and receive real-time health predictions. Additionally, a **Flask API** was developed for seamless integration into other applications.  

### **Key Takeaways:**  
✔ **Lifestyle factors significantly impact health outcomes**, as observed from model insights.  
✔ **Random Forest performed slightly better** than SVM in classification accuracy.  
✔ **Streamlit provides an intuitive UI**, making the model user-friendly and interactive.  

### **Future Enhancements:**  
🚀 **Expand dataset size** for better generalization.  
🚀 **Include additional health indicators** such as BMI, heart rate, and stress levels.  
🚀 **Optimize hyperparameters further** to improve model performance.  
🚀 **Deploy as a cloud-based service** for real-world usability.  

This project serves as a **solid foundation** for future research in **AI-powered health assessment** and encourages the development of more personalized wellness applications.  

---

### **Streamlit application to predict Machine Learning-based Health Prediction Model :**  



https://github.com/user-attachments/assets/eebe6226-cd78-4410-9dcf-f4be15c13fc2

---
