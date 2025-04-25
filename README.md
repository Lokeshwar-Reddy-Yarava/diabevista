# DiabeVista - Intelligent Diabetes Insights

## 🩺 About the Project

DiabeVista is a smart healthcare dashboard that uses **machine learning** and **data visualization** to predict diabetes readmissions, identify critical health factors, and support data-driven healthcare decisions.

We blend the power of predictive analytics and interactive visualization to enable **better understanding**, **early intervention**, and **personalized treatment strategies** for diabetes management.

---

## 🚀 Features

- **Exploratory Data Analysis** of Diabetes Patient Data
- **Feature Selection** & **Variance Analysis**
- **Multiple Machine Learning Models**: Logistic Regression, SVM, KNN, Random Forest, Naive Bayes, Decision Trees
- **Patient Readmission Prediction** for Diabetes Dataset
- **Confusion Matrix**, **ROC Curve**, **Model Comparison**
- **Streamlit Dashboard UI** with custom styles
- **Interactive visualizations** using **Plotly** and **Seaborn**

---

## 🛠️ Built With

- **Python 3.9+**
- **Streamlit** for interactive dashboard
- **scikit-learn** for Machine Learning models
- **Matplotlib** and **Plotly** for visualizations
- **Seaborn** for EDA

---

## 📁 Project Structure

```
├── main.py                 # Home page + Navigation
├── data.py                 # Data loading & missing data analysis
├── feature.py              # Feature extraction, selection and variance
├── model_train.py          # ML model training & performance evaluation
├── patient_readmission.py  # Readmission prediction on diabetic dataset
├── style.py                # Page styling & background setup
├── Final_Project_Proposal.pdf  # Project proposal document
├── requirements.txt        # Python dependencies
└── images/
    └── image.png           # (Background image for the app)
    └── Dashboard.png 
```

---

## ⚡ How to Run Locally

1. Clone the repo
```bash
git clone https://github.com/yourusername/diabevista.git
cd diabevista
```

2. Install required packages
```bash
pip install -r requirements.txt
```

3. Run the Streamlit app
```bash
streamlit run main.py
```

---

## 📈 Results and Insights

- Achieved **up to 96% accuracy** using models like **Random Forest**, **KNN**, and **Decision Tree**.
- Identified top contributing factors: Polydipsia, Sudden Weight Loss, Age, Visual Blurring, etc.
- ROC Curves and Confusion Matrices provided detailed model evaluation.

---

## 📚 References

- [Machine Learning Methods to Predict Diabetes Complications (Dagliati et al., 2018)](https://doi.org/10.1177/1932296817706375)
- [Machine learning for diabetes clinical decision support: a review (Tuppad & Patil, 2022)](https://doi.org/10.1007/s43674-022-00034-y)
- [Prediction of Type 2 Diabetes Using ML (Mansoori et al., 2023)](https://doi.org/10.1038/s41598-022-27340-2)

---

## 🤝 Contributions

Project completed as part of **Smart & Connected Health** course at the **University of South Florida**.

