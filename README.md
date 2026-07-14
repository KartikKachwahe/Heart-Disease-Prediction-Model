# ❤️ Heart Disease Prediction Model

---

<p align="center">

![Python](https://img.shields.io/badge/Python-Programming-blue?style=for-the-badge&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Processing-150458?style=for-the-badge&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-Numerical%20Computing-013243?style=for-the-badge&logo=numpy&logoColor=white)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-Machine%20Learning-F7931E?style=for-the-badge&logo=scikitlearn&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-Visualization-orange?style=for-the-badge)
![Seaborn](https://img.shields.io/badge/Seaborn-EDA-0099CC?style=for-the-badge)
![Streamlit](https://img.shields.io/badge/Streamlit-Web%20Application-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white)
![Jupyter Notebook](https://img.shields.io/badge/Jupyter-Notebook-F37626?style=for-the-badge&logo=jupyter&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-Portfolio-black?style=for-the-badge&logo=github)

</p>

<p align="center">
<b>An end-to-end Machine Learning project that predicts the likelihood of heart disease using patient medical attributes and supports healthcare decision-making through predictive analytics.</b>
</p>

---

# Table of Contents

- [Project Overview](#-project-overview)
- [Business Problem](#-business-problem)
- [Project Objectives](#-project-objectives)
- [Dataset Information](#-dataset-information)
- [Tech Stack](#-tech-stack)
- [Project Workflow](#-project-workflow)
- [Data Preprocessing](#-data-preprocessing)
- [Exploratory Data Analysis](#-exploratory-data-analysis)
- [Feature Description](#-feature-description)
- [Model Development](#-model-development)
- [Model Evaluation](#-model-evaluation)
- [Prediction System](#-prediction-system)
- [How To Run](#-how-to-run)
- [Repository Structure](#-repository-structure)
- [Skills Demonstrated](#-skills-demonstrated)
- [Future Enhancements](#-future-enhancements)
- [Business Impact](#-business-impact)
- [Conclusion](#-conclusion)
- [Author](#-author)

---

#  Project Overview

Heart disease is one of the leading causes of death globally. Early prediction and identification can help reduce healthcare risks and improve patient outcomes.

This project uses Machine Learning techniques to analyze medical attributes and predict the likelihood of heart disease.

The project combines:

- Data preprocessing
- Exploratory Data Analysis
- Feature engineering
- Machine Learning model training
- Model evaluation
- Model deployment

The system helps:

- Identify high-risk patients
- Support healthcare decisions
- Reduce diagnosis delays
- Improve preventive care

---

#  Business Problem

Healthcare systems often face challenges in identifying heart disease risk at an early stage.

Traditional diagnosis approaches can:

- Be expensive
- Require multiple medical tests
- Consume significant time
- Delay preventive treatment

Key questions addressed:

- Can Machine Learning predict heart disease risk?
- Which medical attributes influence predictions?
- Can predictive analytics assist healthcare decisions?
- How can early risk detection improve patient outcomes?

---

#  Project Objectives

### Healthcare Objectives

- Predict heart disease likelihood
- Analyze patients health indicators
- Identify important predictive features
- Train and evaluate ML models
- Build a prediction system
- Support healthcare analytics

---

#  Dataset Information

**Dataset Source:** UCI Heart Disease Dataset

### Dataset Summary

| Metric | Value |
|----------|--------|
| Total Records | 303 |
| Total Features | 14 |
| Target Variable | Heart Disease |
| Data Type | Structured Medical Data |

---

### Features Included

| Feature | Description |
|-----------|-------------|
| age | Age of patient |
| sex | Gender |
| cp | Chest pain type |
| trestbps | Resting blood pressure |
| chol | Cholesterol |
| fbs | Fasting blood sugar |
| restecg | Resting ECG |
| thalach | Maximum heart rate |
| exang | Exercise induced angina |
| oldpeak | ST depression |
| slope | Slope of ST segment |
| ca | Major vessels count |
| thal | Thalassemia |
| target | Heart disease prediction |

---

#  Tech Stack

| Technology | Purpose |
|------------|----------|
| Python | Programming |
| Pandas | Data Manipulation |
| NumPy | Numerical Operations |
| Matplotlib | Data Visualization |
| Seaborn | Exploratory Data Analysis |
| Scikit-Learn | Machine Learning |
| Streamlit | Web Application |
| Pickle | Model Serialization |
| Git/GitHub | Version Control |

---

#  Project Workflow

```text
Raw Dataset (.CSV)
          │
          ▼
Data Preprocessing
          │
          ▼
Exploratory Data Analysis
          │
          ▼
Feature Engineering
          │
          ▼
Train-Test Split
          │
          ▼
Model Training
          │
          ▼
Model Evaluation
          │
          ▼
Model Serialization
(.pkl)
          │
          ▼
Prediction Web Application
```

---

#  Data Preprocessing

Data preprocessing was performed before model development.

### Tasks Performed

- Imported dataset
- Checked missing values
- Removed duplicates
- Data validation
- Feature scaling
- Train-test splitting
- Data transformation

---

#  Exploratory Data Analysis

Exploratory analysis was conducted to understand relationships between medical attributes.

### Analysis Performed

- Distribution Analysis
- Correlation Analysis
- Feature Relationships
- Disease Distributions
- Health Indicator Analysis

### Key Observations

- Chest pain significantly affects prediction
- Maximum heart rate influences outcomes
- Exercise-induced angina contributes strongly
- Clinical indicators show correlation with target values

---

#  Model Development

Machine learning workflow:

- Data splitting
- Feature scaling
- Model training
- Hyperparameter tuning
- Performance evaluation

### Model Pipeline

```python
Dataset
   ↓
Train-Test Split
   ↓
Feature Scaling
   ↓
Model Training
   ↓
Prediction
   ↓
Performance Evaluation
```

---

#  Model Evaluation

Model performance was evaluated using classification metrics.

### Evaluation Metrics

- Accuracy Score
- Precision
- Recall
- F1 Score
- Confusion Matrix

### Goals

- Improve prediction reliability
- Reduce false negatives
- Increase model generalization

---

#  Prediction System

Users provide health-related parameters and receive prediction results.

### Prediction Flow

```text
User Inputs Health Parameters
              │
              ▼
Preprocessing
              │
              ▼
Trained ML Model
              │
              ▼
Prediction
              │
              ▼
Heart Disease Risk Result
```

---

#  How To Run

### Clone Repository

```bash
git clone https://github.com/KartikKachwahe/Heart-Disease-Prediction-Model.git
```

### Move into Project Directory

```bash
cd Heart-Disease-Prediction-Model
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

### Run Streamlit App

```bash
streamlit run app.py
```

---

#  Repository Structure

```text
Heart-Disease-Prediction-Model
│
├── Pickel files
│   ├── model.pkl
│   └── scaler.pkl
│
├── Heart-Disease-Prediction.ipynb
├── app.py
├── heart.csv
├── README.md
```

---

#  Skills Demonstrated

### Python

- Data Cleaning
- Data Manipulation
- Feature Engineering

### Machine Learning

- Classification Models
- Model Training
- Model Evaluation
- Predictive Analytics

### Data Science

- Exploratory Data Analysis
- Healthcare Analytics
- Data Visualization

### Software Development

- Model Deployment
- Pickle Serialization
- Git Version Control

---

#  Future Enhancements

- Deploy application to cloud
- Add more healthcare datasets
- Implement Deep Learning models
- Build healthcare dashboards
- Add Explainable AI (XAI)
- Improve prediction interpretability

---

#  Business Impact

Potential healthcare benefits:

✅ Early disease identification

✅ Better healthcare planning

✅ Reduced healthcare risk

✅ Faster clinical support

✅ Improved patient outcomes

✅ Data-driven medical decisions

---

#  Conclusion

This project demonstrates how Machine Learning can support healthcare systems in identifying heart disease risk using patient medical attributes.

The project covers a complete end-to-end Data Science workflow:

- Data preprocessing
- Exploratory Data Analysis
- Feature engineering
- Machine Learning model development
- Performance evaluation
- Deployment-ready prediction system

Predictive healthcare solutions can help improve diagnosis speed and support better decision-making.

---

# 👨‍💻 Author

## Kartik Kachwahe

**Aspiring Data Scientist | Data Analyst | Machine Learning | SQL | Power BI | Python**

📧 Email: kartikkachwahe25@gmail.com

💼 LinkedIn: https://www.linkedin.com/in/kartikkachwahe021

💻 GitHub: https://github.com/KartikKachwahe

---

## ⭐ Support

If you found this project useful, consider giving the repository a star.

Your support motivates future projects and helps others discover this work.

---

**Thank you for visiting this repository ❤️**
