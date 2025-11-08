# 🚗 Car Price Prediction System — Machine Learning Model  

## 📘 Project Description  
The **Car Price Prediction System** is a Machine Learning-based project that predicts the **resale value of cars** using key automobile attributes such as **Car Name, Year, Selling Price, Present Price, Kilometers Driven, Fuel Type, Seller Type, Transmission, and Owner**.  
The model is built using the **Lasso Regression (Linear Regression)** algorithm, achieving an **R² score of 0.83**, which reflects strong predictive performance.  

A detailed **Exploratory Data Analysis (EDA)** was conducted to identify trends, patterns, and correlations affecting car resale prices.  
This project demonstrates the use of **regression modeling** in real-world **automobile price prediction and valuation systems**.  

---

## 🔍 About the Project  
This project showcases how **supervised learning regression algorithms** can be applied to forecast used car prices accurately.  
By leveraging historical car data, it helps users, car dealerships, and marketplaces make **data-driven pricing decisions** based on factors that influence vehicle depreciation and market trends.  

---

## 🧠 Model Architecture  
The project uses a **Lasso Regression (Linear Regression)** model with the following specifications:  
* **Algorithm:** Lasso Regression  
* **Problem Type:** Regression (Continuous Value Prediction)  
* **Evaluation Metrics:** R² Score, Mean Absolute Error (MAE)  

---

## 🧾 Dataset Description  
The dataset contains car details such as model, fuel type, and price, used to train and test the regression model.  

| Column Name         | Description |
| :------------------ | :----------------------------------------------------------- |
| `Car_Name`          | Name of the car model |
| `Year`              | Manufacturing year of the car |
| `Selling_Price`     | Price at which the car was sold (target variable) |
| `Present_Price`     | Current ex-showroom price of the car |
| `Kms_Driven`        | Total kilometers driven |
| `Fuel_Type`         | Type of fuel used (Petrol/Diesel/CNG) |
| `Seller_Type`       | Indicates if the seller is an individual or dealer |
| `Transmission`      | Type of transmission (Manual/Automatic) |
| `Owner`             | Number of previous owners |

---

## ⚙️ Tech Stack & Libraries  

**Language:**  
* Python 🐍  

**Libraries:**  
* **NumPy** – Numerical computations  
* **Pandas** – Data manipulation and preprocessing  
* **Scikit-learn** – Model training, evaluation, and feature encoding  
* **Matplotlib / Seaborn** – Visualization and EDA  

---

## 🚀 Features  
* Predicts resale car prices with high accuracy  
* Performs thorough EDA to identify key price factors  
* Utilizes **Lasso Regression** for feature selection and regularization  
* Suitable for **real-world automobile valuation**  
* Achieves an **R² score of 0.83**  

---

## 📊 Results  
The trained **Lasso Regression (Linear Regression)** model achieved an **R² score of 0.83**, accurately predicting car resale prices based on diverse automobile attributes.  

---

## 📁 Repository Structure  

```
📦 ML_Project_Car_Price_Prediction
│
├── car_price_prediction.ipynb # Jupyter Notebook with full implementation
├── car_data.csv # Dataset used for model training and testing
└── README.md # Project documentation

```
---

## 🧪 How to Run  

1. **Clone the repository:**  
   ```bash
   git clone https://github.com/ms00000ms0000/ML-Projects-Car-Price-Prediction.git
   cd ML-Projects-Car-Price-Prediction
   ```

2.**Install dependencies:**

```bash
pip install -r requirements.txt
```

3.**Run the notebook:**

```bash
jupyter notebook car_price_prediction.ipynb
```

4. **Execute all cells to train, test, and evaluate the model.**

---

## 📈 Future Improvements

* Integrate a web-based prediction interface using Flask or Streamlit

* Add XGBoost or Random Forest Regressor for performance comparison

* Expand dataset with real-time used car listings for better generalization

---

## 👨‍💻 Developer

Developed by: Mayank Srivastava
