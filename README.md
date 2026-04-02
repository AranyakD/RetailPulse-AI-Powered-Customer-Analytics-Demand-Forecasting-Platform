# RetailPulse – AI-Powered Customer Analytics & Demand Forecasting

## Overview

RetailPulse is an end-to-end data science project designed to analyze retail transaction data and generate actionable business insights. The system focuses on demand forecasting, customer segmentation, churn prediction, and inventory optimization.

This project simulates a real-world production pipeline, combining data engineering, machine learning, and deployment practices.

---

## Objectives

* Predict product demand using time-series forecasting
* Segment customers based on behavior (RFM analysis)
* Identify customers at risk of churn
* Optimize inventory decisions using predictive insights
* Build an interactive dashboard for business users

---

## Project Structure

```
RetailPulse/
│
├── data/
│   ├── raw/
│   ├── processed/
│
├── notebooks/
│
├── src/
│   ├── data/
│   ├── features/
│   ├── models/
│   ├── utils/
│
├── dashboard/
├── models/
├── reports/
│
├── requirements.txt
├── README.md
├── .gitignore
```

---

## Tech Stack

* Python 3.10
* Pandas, NumPy (data processing)
* Scikit-learn (machine learning)
* XGBoost (churn prediction)
* Prophet and LSTM (forecasting)
* Streamlit (dashboard)
* MLflow (experiment tracking)
* Docker (deployment)

---

## Dataset

This project uses the Online Retail II dataset from Kaggle.

Note: The dataset is not included in this repository. Place the dataset file inside:

```
data/raw/
```

---

## Setup Instructions

### 1. Clone the repository

```
git clone <repo-link>
cd RetailPulse
```

### 2. Create virtual environment

```
python3.10 -m venv venv
source venv/Scripts/activate   # Windows (Git Bash)
```

### 3. Install dependencies

```
pip install -r requirements.txt
```

---

## Current Progress

* Project structure initialized
* Dataset integration in progress
* Exploratory Data Analysis started

---

## Future Work

* Data cleaning and feature engineering
* Customer segmentation (RFM + clustering)
* Demand forecasting models
* Churn prediction model
* Dashboard development
* Deployment and MLOps integration

---

## Evaluation Focus

This project is built with the following priorities:

* Model accuracy and performance
* Clean and modular code
* Reproducibility
* Production readiness
* Clear documentation

---

## Contributors



---

## License

This project is for educational and internship purposes.
