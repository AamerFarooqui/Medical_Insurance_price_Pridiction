# 🏥 Medical Insurance Analysis and Price Prediction System

## 📌 Project Overview

This project focuses on analyzing medical insurance data and building a machine learning model to predict insurance prices based on various factors such as age, BMI, smoking habits, and health conditions.

The goal is to:

* Perform **Exploratory Data Analysis (EDA)**
* Identify key factors affecting insurance costs
* Build a **predictive model**
* Provide insights for better decision-making

---

## 🚀 Features

* 📊 Data Cleaning & Preprocessing
* 📈 Exploratory Data Analysis (EDA)
* 🔍 Outlier Detection (IQR Method)
* 📉 Data Visualization (Seaborn & Matplotlib)
* 🤖 Machine Learning Model (Linear Regression)
* 🖥️ GUI Application using Tkinter

---

## 📂 Project Structure

```
Medical-Insurance-Analysis_and Price_Prediction/
│── health_data_1000.csv
|
│── main.ipynb
|
│── README.md
```

---

## 📊 Exploratory Data Analysis (EDA)

Key visualizations performed:

* Distribution of insurance charges
* BMI vs Insurance Price
* Age vs Charges
* Smoker vs Non-Smoker comparison
* Correlation Heatmap

### 🔍 Key Insights:

* Smoking significantly increases insurance costs
* BMI and age show moderate positive correlation
* Charges are right-skewed (log transformation applied)
* Outliers represent real-world high medical expenses

---

## 🧠 Machine Learning Model

* Algorithm Used: **Linear Regression**
* Target Variable: `Insurance_Price`
* Features:

  * Age
  * BMI
  * Smoking Status
  * Health Issues
  * Number of Dependents

### 📈 Model Performance

* Evaluated using:

  * R² Score
  * Mean Absolute Error (MAE)

---

## 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Tkinter


---

## 💡 Usage

* Input user details such as age, BMI, smoking status, etc.
* The system predicts the **insurance price instantly**

---

## 📸 Sample Output

### Distribution of insurance price
<img width="902" height="704" alt="image" src="https://github.com/user-attachments/assets/eb079f1d-0add-4abb-8eaa-0d4473134fc8" />

### Age vs Insurance price
<img width="931" height="715" alt="image" src="https://github.com/user-attachments/assets/7a4b0260-7e49-411d-bfb8-042a700d18d8" />

### Smaker vs Non-Smoker by charges
<img width="913" height="701" alt="image" src="https://github.com/user-attachments/assets/8967c8e3-3cca-4b69-a8bf-b81dbc9e7790" />

### BMI vs Insurance price
<img width="917" height="708" alt="image" src="https://github.com/user-attachments/assets/1f4b66a7-eeee-45a5-b185-e534d67ff2ba" />

### Health issue by Insurance price
<img width="904" height="807" alt="image" src="https://github.com/user-attachments/assets/cea48486-f54d-4085-97e6-aff651fe5248" />

### Heatmap
<img width="942" height="651" alt="image" src="https://github.com/user-attachments/assets/9dcfed44-1bae-4007-9c9d-2ddea605135d" />

---


## 🤝 Contributing

Contributions are welcome! Feel free to fork this repository and submit a pull request.

---

## 📜 License

This project is open-source and available under the MIT License.

---

## 👨‍💻 Author

**Aamer Farooqui**

* GitHub: https://github.com/AamerFarooqui
* LinkedIn: https://www.linkedin.com/in/aamer-farooqui-34b1402ba
