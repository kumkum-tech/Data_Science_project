# 🚗 Car Price Prediction ML App

![Python](https://img.shields.io/badge/Python-3.12-blue)
![Streamlit](https://img.shields.io/badge/Streamlit-Deployed-red)
![Machine Learning](https://img.shields.io/badge/Machine-Learning-green)
![Status](https://img.shields.io/badge/Status-Live-success)

A Machine Learning-powered web application that predicts the selling price of used cars based on vehicle specifications and historical market data. The application provides instant price predictions through an interactive Streamlit interface.

## 🌐 Live Demo

**Try the App:** https://datascienceproject-ccyxqq4mzcdn3r3f7dvygo.streamlit.app/

---

## 📖 About The Project

Determining the right price for a used car can be challenging. This project leverages Machine Learning to estimate a vehicle's selling price based on important factors such as brand, manufacturing year, kilometers driven, fuel type, transmission type, seller type, and ownership history.

The goal is to provide users with a quick, data-driven estimate that can help buyers and sellers make informed decisions.

---

## ✨ Features

* 🚀 Real-time car price prediction
* 📊 Machine Learning-based estimation
* 🎯 User-friendly Streamlit interface
* ⚡ Instant prediction results
* 🌐 Accessible from any device
* 📱 Clean and responsive design
* 🔍 Multiple vehicle attributes supported

---

## 🛠️ Tech Stack

### Programming Language

* Python 3.12

### Data Science & Machine Learning

* Pandas
* NumPy
* Scikit-learn

### Web Framework

* Streamlit

### Model Serialization

* Pickle

### Version Control

* Git
* GitHub

### Deployment

* Streamlit Community Cloud

---

## 🤖 Machine Learning Workflow

### Data Preprocessing

* Data Cleaning
* Handling Missing Values
* Feature Selection
* Data Transformation
* Encoding Categorical Variables

### Model Training

The model was trained using historical used-car sales data and optimized to predict selling prices based on vehicle specifications.

### Input Features

| Feature            | Description                     |
| ------------------ | ------------------------------- |
| Car Brand          | Vehicle manufacturer            |
| Manufacturing Year | Year of production              |
| Kilometers Driven  | Total distance traveled         |
| Fuel Type          | Petrol, Diesel, CNG, etc.       |
| Seller Type        | Dealer or Individual            |
| Transmission Type  | Manual or Automatic             |
| Ownership History  | First Owner, Second Owner, etc. |

### Output

* Predicted Selling Price of the Car

---

## 📊 Dataset Information

The dataset includes various attributes related to used cars:

* Car Name
* Year
* Selling Price
* Kilometers Driven
* Fuel Type
* Seller Type
* Transmission
* Owner Type

The dataset was cleaned and preprocessed before being used for training the Machine Learning model.

---

## 🚀 Getting Started

### Clone the Repository

```bash
git clone https://github.com/kumkum-tech/Data_Science_project.git
cd Data_Science_project
```

### Create Virtual Environment

```bash
python -m venv venv
```

### Activate Virtual Environment

#### Windows

```bash
venv\Scripts\activate
```

#### Linux / macOS

```bash
source venv/bin/activate
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

### Run the Application

```bash
streamlit run app.py
```

The application will start locally and open in your browser.

---

## 📂 Project Structure

```text
Data_Science_project/
│
├── app.py                 # Streamlit Application
├── model.pkl              # Trained Machine Learning Model
├── requirements.txt       # Project Dependencies
├── README.md              # Documentation
└── dataset/               # Dataset Files
```

---

## 🎯 How It Works

1. Select the Car Brand.
2. Choose Manufacturing Year.
3. Enter Kilometers Driven.
4. Select Fuel Type.
5. Choose Seller Type.
6. Select Transmission Type.
7. Choose Ownership Category.
8. Click Predict.
9. View the Estimated Selling Price.

---

## 📸 Application Preview

### Home Screen

*Add screenshot here*

### Prediction Result

*Add screenshot here*

---

## 🔮 Future Enhancements

* Support for more vehicle brands
* Advanced Machine Learning models
* Price trend visualization
* Model performance dashboard
* REST API integration
* Mobile-friendly enhancements
* Vehicle recommendation system

---

## 📈 Use Cases

* Used Car Sellers
* Used Car Buyers
* Automobile Market Analysis
* Educational Machine Learning Projects
* Data Science Portfolio Showcase

---

## 👨‍💻 Author

### Kumkum Rastogi

Computer Science Engineering Student

Interested in:

* Data Science
* Artificial Intelligence
* Machine Learning
* Data Analytics

### Connect With Me

* GitHub: https://github.com/kumkum-tech
* LinkedIn: https://www.linkedin.com/

---

## ⭐ Show Your Support

If you found this project useful:

⭐ Star this repository

🍴 Fork the project

📢 Share it with others

---

## 📜 License

This project is created for educational and learning purposes.

   ```

## Live Deployment
Deploy to Streamlit Community Cloud with a single click:
[![Deploy to Streamlit](https://static.streamlit.io/badges/streamlit_badge_black_white.svg)](https://share.streamlit.io/deploy?repository=jaidevxr/car-price-prediction-streamlit&branch=main&main_file=CarPredictionStreamlit.py)
