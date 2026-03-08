# 🩺 Blood Pressure Prediction using Machine Learning

> An end-to-end machine learning pipeline for early detection of hypertension — from raw data to actionable predictions.

![Python](https://img.shields.io/badge/Python-3.8%2B-blue?logo=python&logoColor=white)
![Scikit-learn](https://img.shields.io/badge/Scikit--learn-ML-orange?logo=scikit-learn&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-F37626?logo=jupyter&logoColor=white)
![License](https://img.shields.io/badge/License-MIT-green)

---

## 📌 Overview

Hypertension (high blood pressure) silently affects over **1.28 billion adults worldwide** and is one of the leading risk factors for heart disease and stroke. Early identification is critical — yet most people remain undiagnosed until serious complications arise.

This project builds a **Machine Learning classification system** that predicts whether an individual is at risk of high blood pressure based on physiological and medical parameters. It demonstrates a complete, reproducible ML workflow — from raw data to evaluation-ready models — using Python and industry-standard data science libraries.

---

## 🎯 Project Objectives

- ✅ Preprocess and clean raw medical data
- ✅ Perform Exploratory Data Analysis (EDA) to uncover patterns
- ✅ Engineer and select the most predictive features
- ✅ Train and compare multiple ML classification models
- ✅ Evaluate model performance with comprehensive metrics
- ✅ Generate predictions from new patient input data

---

## 🧠 ML Workflow

```
Data Collection → Preprocessing → EDA → Feature Selection → Model Training → Evaluation → Prediction
```

| Step | Description |
|------|-------------|
| **1. Data Collection** | Medical and physiological parameter dataset |
| **2. Preprocessing** | Handling missing values, encoding, scaling |
| **3. EDA** | Distribution plots, correlation heatmaps, outlier detection |
| **4. Feature Selection** | Identifying the most impactful predictors |
| **5. Model Training** | Fitting classification algorithms |
| **6. Evaluation** | Accuracy, Confusion Matrix, F1-Score, Precision, Recall |
| **7. Prediction** | Inference on new input data |

---

## 📁 Project Structure

```
Blood_Pressure_using_ml/
│
├── Blood_pressure.ipynb     # Main Jupyter Notebook (full pipeline)
├── requirements.txt         # Python dependencies
└── README.md                # Project documentation
```

---

## 🛠️ Tech Stack

| Library | Purpose |
|---------|---------|
| `Python 3.8+` | Core programming language |
| `NumPy` | Numerical computations |
| `Pandas` | Data manipulation and analysis |
| `Matplotlib` | Static data visualization |
| `Seaborn` | Statistical visualizations |
| `Scikit-learn` | ML model building and evaluation |
| `Jupyter Notebook` | Interactive development environment |

---

## 📊 Model Evaluation Metrics

The models are assessed using the following metrics to ensure clinical reliability:

- **Accuracy Score** — Overall correct predictions
- **Confusion Matrix** — Visual breakdown of TP, TN, FP, FN
- **Precision** — How many predicted positives are actually positive
- **Recall (Sensitivity)** — How many actual positives were caught
- **F1-Score** — Harmonic mean of Precision and Recall

---

## ▶️ Getting Started

### Prerequisites
- Python 3.8 or higher
- pip package manager

### Installation

```bash
# 1. Clone the repository
git clone https://github.com/your-username/Blood_Pressure_using_ml.git

# 2. Navigate into the project directory
cd Blood_Pressure_using_ml

# 3. Install required dependencies
pip install -r requirements.txt

# 4. Launch Jupyter Notebook
jupyter notebook
```

Then open `Blood_pressure.ipynb` and run all cells from top to bottom.

---

## 📈 Results & Expected Output

The trained model outputs a binary classification — predicting whether a patient is **likely** or **unlikely** to have high blood pressure — along with a confidence score and evaluation report.

---

## 🔮 Future Improvements

- [ ] Hyperparameter tuning with GridSearchCV / RandomizedSearchCV
- [ ] K-Fold cross-validation for more robust evaluation
- [ ] Benchmark multiple algorithms (XGBoost, LightGBM, Random Forest)
- [ ] Deploy as a web app using **Flask** or **Streamlit**
- [ ] Build a real-time healthcare dashboard
- [ ] Integrate with wearable device APIs for live monitoring

---

## 🤝 Contributing

Contributions are welcome! To get started:

1. Fork this repository
2. Create a feature branch (`git checkout -b feature/your-feature`)
3. Commit your changes (`git commit -m 'Add your feature'`)
4. Push to the branch (`git push origin feature/your-feature`)
5. Open a Pull Request

---

## 📌 Conclusion

This project demonstrates how machine learning can support early detection of hypertension — a condition that often goes undiagnosed until it's too late. By transforming raw medical data into actionable predictions, it highlights the potential of data-driven approaches to improve preventive healthcare.

---

## 👩‍💻 Author

**Khushi Kalwani**  
*Machine Learning Enthusiast | AI Developer*

[![GitHub](https://img.shields.io/badge/GitHub-Follow-black?logo=github)](https://github.com/your-username)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-blue?logo=linkedin)](https://linkedin.com/in/your-profile)

---

*If you found this project useful, please ⭐ star the repository!*
