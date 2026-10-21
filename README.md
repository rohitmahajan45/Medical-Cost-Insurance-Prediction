# 🏥 Medical Insurance Cost Prediction

### 💡 Machine Learning | Python | Scikit-learn | Streamlit

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.10%2B-blue?logo=python" alt="Python">
  <img src="https://img.shields.io/badge/Machine-Learning-purple" alt="Machine Learning">
  <img src="https://img.shields.io/badge/Scikit--learn-ML-orange?logo=scikitlearn" alt="Scikit-learn">
  <img src="https://img.shields.io/badge/Streamlit-Web_App-red?logo=streamlit" alt="Streamlit">
  <img src="https://img.shields.io/badge/Status-Completed-success" alt="Project Status">
</p>

---

## 🌟 About the Project

**Medical Insurance Cost Prediction** is a machine learning project that estimates medical insurance charges based on personal and lifestyle information.

The project uses regression algorithms to analyze insurance data, compare model performance, and generate estimated insurance costs through an interactive web application.

## ✨ Key Features

* 📊 **Data Analysis:** Explore the insurance dataset and visualize patterns.
* 🤖 **Multiple ML Models:** Train and compare regression algorithms.
* 📈 **Model Evaluation:** Compare MAE, RMSE, and R² scores.
* 💰 **Cost Prediction:** Estimate insurance charges using user inputs.
* 🎨 **Interactive UI:** Simple and user-friendly Streamlit interface.
* ⚡ **Real-Time Interaction:** Generate predictions from the information entered by the user.

## 🛠️ Tech Stack

| Technology   | Purpose                     |
| ------------ | --------------------------- |
| Python       | Programming                 |
| Pandas       | Data manipulation           |
| NumPy        | Numerical operations        |
| Matplotlib   | Data visualization          |
| Seaborn      | Statistical visualization   |
| Scikit-learn | Machine learning            |
| Streamlit    | Interactive web application |

## 📂 Project Structure

```text
Medical-Insurance-Cost-Prediction/
│
├── insurance.csv       # Insurance dataset
├── main.py             # Data analysis and model comparison
├── prediction.py       # Insurance cost prediction app
├── requirements.txt    # Required Python libraries
└── README.md           # Project documentation
```

## 📊 Dataset Information

The dataset contains the following features:

| Feature    | Description                                 |
| ---------- | ------------------------------------------- |
| `age`      | Age of the individual                       |
| `sex`      | Gender                                      |
| `bmi`      | Body Mass Index                             |
| `children` | Number of children                          |
| `smoker`   | Smoking status                              |
| `region`   | Residential region                          |
| `charges`  | Medical insurance charges (target variable) |

## 🤖 Machine Learning Algorithms

The project compares these regression models:

* Linear Regression
* Ridge Regression
* Random Forest Regressor
* Extra Trees Regressor

The best-performing model is selected according to the evaluation results.

## 📈 Evaluation Metrics

* **MAE:** Mean Absolute Error
* **RMSE:** Root Mean Squared Error
* **R² Score:** Coefficient of Determination

## ⚙️ Installation and Usage

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/rohitmahajan45/Medical-Insurance-Cost-Prediction.git
```

### 2️⃣ Navigate to the Project Folder

```bash
cd Medical-Insurance-Cost-Prediction
```

### 3️⃣ Install Dependencies

```bash
pip install -r requirements.txt
```

### 4️⃣ Launch the Analysis Dashboard

```bash
streamlit run main.py
```

### 5️⃣ Launch the Prediction Application

```bash
streamlit run prediction.py
```

**Note:** Keep `insurance.csv` in the same folder as the Python files.

## 🎯 Project Objective

The objective is to apply machine learning regression techniques to estimate medical insurance costs and demonstrate the practical use of data preprocessing, model evaluation, and interactive prediction.

## 👨‍💻 Author

### Rohit Mahajan

* 🐙 **GitHub:** [@rohitmahajan45](https://github.com/rohitmahajan45)

---

<p align="center">
  ⭐ If you find this project useful, consider starring the repository!
</p>
