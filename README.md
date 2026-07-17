# 🚚 Delivery Prediction using Machine Learning

A machine learning web application built with **Streamlit** to predict whether a shipment will be delivered **on time** based on shipment, customer, and product information.

---

## 📌 Project Overview

This project predicts the delivery status of shipments using a trained **XGBoost Classifier**. It includes data preprocessing, feature engineering, model training, evaluation, and deployment through a user-friendly Streamlit interface.

---

## 🚀 Features

* Predicts on-time delivery status.
* Interactive Streamlit web interface.
* Data preprocessing using `ColumnTransformer`.
* One-Hot Encoding for categorical features.
* Standard Scaling for numerical features.
* Machine Learning model trained using **XGBoost**.
* Fast and accurate predictions.

---

## 🛠️ Tech Stack

* Python
* Streamlit
* Pandas
* NumPy
* Scikit-learn
* XGBoost
* Joblib
* Matplotlib
* Seaborn

---

## 📂 Project Structure

```text
Delivery_Prediction/
│── app.py
│── model.joblib
│── preprocessor.joblib
│── requirements.txt
│── README.md
│── .gitignore
│── Data_Cleaning.ipynb
│── Train.csv
│── train_dataset.csv
│── test_dataset.csv
```

---

## ⚙️ Installation

1. Clone the repository

```bash
git clone https://github.com/Chandu7569/Delivery_predictions.git
```

2. Navigate to the project directory

```bash
cd Delivery_predictions
```

3. Create and activate a virtual environment

**Windows**

```bash
python -m venv myenv
myenv\Scripts\activate
```

4. Install dependencies

```bash
pip install -r requirements.txt
```

5. Run the Streamlit application

```bash
streamlit run app.py
```

---

## 📊 Input Features

The model uses the following features:

* Warehouse Block
* Mode of Shipment
* Customer Care Calls
* Customer Rating
* Cost of Product
* Prior Purchases
* Product Importance
* Gender
* Discount Offered
* Weight in Grams

---

## 🤖 Machine Learning Pipeline

* Data Cleaning
* Exploratory Data Analysis (EDA)
* Feature Engineering
* Data Preprocessing

  * StandardScaler
  * OneHotEncoder
* Model Training using XGBoost
* Model Evaluation
* Model Serialization using Joblib
* Streamlit Deployment

---

## 📈 Model Output

The application predicts whether a shipment is:

* ✅ Delivered On Time
* ❌ Delayed

---

## 📦 Dependencies

```
pandas==2.2.2
streamlit==1.35.0
joblib==1.4.2
scikit-learn==1.7.2
numpy==1.26.4
matplotlib==3.9.0
seaborn==0.13.2
xgboost==2.1.0
```

---

## 📸 Application Preview

Add screenshots of your Streamlit application here after deployment.

---

## 🔮 Future Improvements

* Hyperparameter optimization
* Model explainability using SHAP
* Cloud deployment
* Batch prediction using CSV upload
* Model monitoring and retraining

---

## 👨‍💻 Author

**Chandra Sekhar**

GitHub: https://github.com/Chandu7569

---

## ⭐ Support

If you found this project helpful, consider giving it a ⭐ on GitHub.
