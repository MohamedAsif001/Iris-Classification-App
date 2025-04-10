# 🌼 Iris Flower Classification - Machine Learning Web App

This project is a complete end-to-end machine learning application built with **Streamlit** for classifying Iris flowers into one of three species — **Setosa**, **Versicolor**, or **Virginica** — based on user input. It includes model building, saving, and deployment as a web app.

---

## 📌 Project Overview

The **Iris dataset** is a classic dataset in the field of machine learning. It contains 150 records of iris flowers, each with 4 features:
- Sepal length (cm)
- Sepal width (cm)
- Petal length (cm)
- Petal width (cm)

Each flower belongs to one of three species:
- **Iris-setosa**
- **Iris-versicolor**
- **Iris-virginica**

This project aims to:
- Train a machine learning model to classify the species based on the input features
- Build an interactive web interface using Streamlit for real-time predictions
- Deploy the app for public use

---

## 🎯 Goals of This Project

✅ Train and evaluate a classification model on the Iris dataset  
✅ Save the trained model using `joblib`  
✅ Build a clean and interactive frontend using Streamlit  
✅ Deploy the app on **Streamlit Community Cloud**  
✅ Document the project for ease of understanding and reuse  

---

## 🛠️ Tools & Technologies Used

| Tool           | Purpose                            |
|----------------|------------------------------------|
| **Python**     | Programming language               |
| **Scikit-learn**| Model building & evaluation      |
| **Streamlit**  | Web app framework for ML apps      |
| **Joblib**     | Model serialization                |
| **Pandas/Numpy** | Data handling & manipulation     |

---

## ⚙️ How the Project Works

### 1. **Model Training**
- The model is built using the Random Forest Classifier from scikit-learn.
- The dataset is split into training and testing sets.
- After training, the model is evaluated and saved as `model.pkl`.

### 2. **Streamlit App**
- Users input the flower measurements using sliders.
- The app loads the saved model.
- The model predicts the species based on inputs.
- The prediction is displayed on the screen instantly.

### 3. **Deployment**
- The app is hosted on **Streamlit Community Cloud**, making it accessible from any browser.
- The app is lightweight and can be run locally with minimal setup.

---


