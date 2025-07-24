# OPTIMIZATION-MODEL
# 🧬 Cancer Prediction Web Application
This project is a machine learning-based web application designed to predict whether a tumor is benign or malignant based on various medical input features. It is built using Python and deployed using the Flask framework, offering a simple and intuitive web interface where users can input tumor data and receive predictions in real-time. The machine learning model used in this project is trained on the widely used Breast Cancer Wisconsin Diagnostic Dataset.

# 🧠 Project Description
Cancer prediction is one of the most critical and sensitive tasks in the healthcare domain. Early diagnosis can significantly increase the survival rate, reduce treatment costs, and improve patient outcomes. This project aims to build an intelligent system that aids in the early detection of breast cancer using machine learning techniques.

The backend of the system uses Python with the scikit-learn library to train a classification model (e.g., Logistic Regression or Random Forest). The trained model is saved using joblib and deployed through a Flask web server. The user interface is built using HTML and allows users to enter values for several tumor-related features (like mean radius, mean texture, etc.). After submitting the form, the model processes the input and returns the result: "Benign" or "Malignant".

# ⚙️ Technologies and Libraries Used
Python 3.x – Main programming language
Flask – Web framework used to create the API and serve the frontend
Scikit-learn – Machine learning library used for model training and evaluation
Pandas & NumPy – Data processing and numerical operations
Joblib – Model serialization
HTML/CSS – For the frontend web form
