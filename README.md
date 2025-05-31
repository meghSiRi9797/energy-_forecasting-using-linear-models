#  Energy Forecasting Using Linear Models

This project is part of my Udemy coursework on practical machine learning. It focuses on **forecasting electricity load (demand)** using classical machine learning models such as **Linear Regression, Decision Trees, Random Forests, and Gradient Boosting**.

The data comes from [Open Power System Data](https://data.open-power-system-data.org/time_series/), a high-quality source for European energy data.

---

##  Dataset

- **File used**: `time_series_60min_singleindex.csv`  
- **Size**: ~124 MB  
- **Source**: [Open Power System Data – Time Series](https://data.open-power-system-data.org/time_series/)  
- **Description**: The dataset contains hourly electricity consumption, generation, and weather data across several European countries.

> **Note**: Download the dataset and place it in your project folder (e.g., inside `notebooks/`).

---

##  Objective

The aim of the project is to:
- Understand and preprocess energy time series data.
- Train and evaluate various regression models to forecast future energy load.
- Compare model performances visually and numerically.
- Select the best-performing model for load prediction.

---

## Tools & Libraries Used

- Python 3.x
- pandas
- numpy
- matplotlib & seaborn (for visualizations)
- scikit-learn (for machine learning models)
- Jupyter Notebook

---

## Models Implemented

- **Linear Regression**
- **Multiple Linear Regression**
- **Polynomial Linear Regression**
- **Decision Tree Regressor**
- **Random Forest Regressor**
- **Gradient Boosting Regressor**

Each model is trained on historical energy load data and evaluated using performance metrics such as **Mean Absolute Error (MAE)** and **Mean Squared Error (MSE)**.

---

## Evaluation Strategy

Selected timestamps from the test set are used to:
- Compare model predictions against actual load values
- Calculate absolute errors and determine which model performs best at each time instance

## How to Run

1. **Clone the repository**:
   ```bash
   git clone https://github.com/meghSiRi9797/energy-_forecasting-using-linear-models.git
   cd energy-_forecasting-using-linear-models
2. ** Set Up a Virtual Environment**
   ```bash
   🔹 On Windows
    python -m venv env
    env\Scripts\activate
   🔹 On macOS/Linux
    python3 -m venv env
    source env/bin/activate
3. Install Required Libraries
   ```bash
   Make sure your virtual environment is activated, then install all required packages using:
   pip install -r requirements.txt



