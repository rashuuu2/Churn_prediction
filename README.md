# 🔍 Customer Churn Prediction System (Machine Learning)

An end-to-end **Customer Churn Prediction project** built using **Machine Learning**, designed to identify customers who are likely to stop using a service based on their behavior and profile data.

This project demonstrates the complete ML lifecycle — from **data preprocessing and model training** to **deployment through a web application**.

---

## 🚀 Project Overview

Customer churn is a critical business problem in subscription-based industries. Retaining customers is far more cost-effective than acquiring new ones.

This project helps businesses:
- Predict customer churn in advance  
- Identify high-risk customers  
- Take data-driven retention actions  

The trained machine learning model is deployed via a **web interface** for real-time predictions.

---

## 📁 Dataset Description

The dataset used in this project contains customer-level information such as:

- Customer Demographics  
- Account Information  
- Service Usage Details  
- Billing & Payment History  
- Churn Status (Yes / No)  

These features are processed and transformed to build an accurate churn prediction model.

---

## 🧠 Machine Learning Pipeline

### 🔹 Data Processing
- Handling missing values  
- Encoding categorical features  
- Feature scaling and transformation  

### 🔹 Model Training
- Train-test split  
- Model selection and training  
- Performance evaluation  

### 🔹 Model Deployment
- Trained model saved using Pickle  
- Integrated into a web application for predictions  

---

## 📊 Model Output

The model predicts:
- **Customer Will Churn**
- **Customer Will Not Churn**

This output helps businesses proactively target customers at risk.

---

## 🛠️ Tools & Technologies Used

- Python  
- NumPy  
- Pandas  
- Scikit-Learn  
- Streamlit / Flask  
- Pickle  
- Jupyter Notebook  

---
📁 Project Structure
churn_prediction/
│
├── data/                 # Dataset (if included)
├── notebook/             # EDA & model training notebooks
├── app.py                # Web application
├── churn_model.pkl       # Trained ML model
├── requirements.txt      # Project dependencies
├── req.txt               # Alternate dependency file
├── runtime.txt           # Deployment runtime configuration
├── .gitignore
└── README.md

1️⃣ Clone the Repository

```bash
git clone https://github.com/rashuuu2/Churn_prediction.git
cd Churn_prediction

2️⃣ Create a Virtual Environment
python -m venv venv

Activate it:
Windows
venv\Scripts\activate

3️⃣ Install Dependencies
pip install -r requirements.txt

▶️ Run the Application
streamlit run app.py

🌍 Deployment
This project is deployment-ready and can be hosted on:
- Render

⭐ Feedback & Contributions
If you like this project, feel free to star ⭐ the repository.
Contributions, suggestions, and improvements are always welcome!

👤 Author
Rashi
Machine Learning Enthusiast
GitHub: https://github.com/rashuuu2




