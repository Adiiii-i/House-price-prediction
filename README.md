# 🏡 House Price Prediction

This project implements a **Machine Learning model** to predict house prices using regression techniques.  
The notebook (`housepriceprediction.ipynb`) demonstrates the full workflow of data preprocessing, training a Linear Regression model, and evaluating its performance.  

---

## 🔹 Features
- Data loading and preprocessing using **Pandas**  
- Splitting dataset into training and testing sets  
- Training a **Linear Regression** model from scikit-learn  
- Model evaluation using **R² Score** and **Mean Absolute Error (MAE)**  
- Visualization of results using **Matplotlib**  

---

## 🔹 Tech Stack
- Python  
- Pandas  
- Matplotlib  
- Scikit-learn  

---

## 📂 Project Structure

housepriceprediction/
│
├── housepriceprediction.ipynb   # Main notebook
├── requirements.txt              # Dependencies
├── README.md                     # Project overview
├── LICENSE                       # Open-source license
│
├── data/                         # Dataset (if small, else link in README)
│    └── housing.csv
│
└── results/                      # Outputs, graphs, predictions
└── predictions.png

---

## 🔹 How to Run
1. Clone this repository  
   '''bash
   git clone https://github.com/Adiiii-i/housepriceprediction.git
   cd housepriceprediction
	
   pip install -r requirements.txt

   jupyter notebook housepriceprediction.ipynb
   
