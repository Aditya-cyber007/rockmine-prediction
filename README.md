# 🪨 Rock vs Mine Prediction using Logistic Regression

This machine learning project uses **Logistic Regression** to classify whether an object detected by sonar is a **Rock** or a **Mine**. It is a binary classification problem built with Python, pandas, NumPy, and Scikit-learn.

---

## 📊 Dataset Information

- 📁 Source: [UCI Sonar Dataset](https://archive.ics.uci.edu/ml/datasets/connectionist+bench+sonar+mines+vs.+rocks)
- 🔢 208 instances, 60 numeric features representing sonar signals
- 🎯 Target Variable:  
  - `R` = Rock  
  - `M` = Mine  

---

## ⚙️ Libraries Used

- Python
- pandas
- numpy
- scikit-learn

---

## 🧠 Code Workflow

1. Load and analyze the dataset
2. Split features (X) and target (Y)
3. Split into train and test sets
4. Train a Logistic Regression model
5. Evaluate model accuracy on training and test data
6. Create a prediction system for new inputs

---

## ✅ Accuracy Results

- 🎓 **Training Accuracy**: 83%
- 🧪 **Test Accuracy**: 76%

---

## 📎 Run This Project on Google Colab

Click below to open the project in Google Colab:  
👉 [Run on Google Colab](https://colab.research.google.com/drive/1Aeq_eoI1Uq9OYHTEXVAhEE3XIPH8Chzn#scrollTo=Pt3OC5YtPUjZ)

---

## 📁 Project Files

- `sonar_data.csv` – The dataset used for training and testing (downloaded from UCI repository)
- `rock_vs_mine_logistic_regression.ipynb` – Main Jupyter Notebook with the complete code and visualizations
- `README.md` – Project overview and instructions
- `requirements.txt` – List of required Python libraries

---

## 📌 Key Features

- **Data Preprocessing**: Cleaned and prepared data for model input
- **Exploratory Data Analysis (EDA)**: Checked class distribution and basic statistics
- **Model Training**: Used Logistic Regression for binary classification
- **Evaluation**: Measured performance using accuracy scores
- **Prediction System**: Built an input system to predict Rock or Mine based on custom data

---

## 🚀 How to Use

1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/rock-vs-mine-logistic-regression.git
   cd rock-vs-mine-logistic-regression
