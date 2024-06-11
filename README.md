# Global Temperature Prediction Using Machine Learning Models

## 🌐 Overview

This project aims to predict global temperatures using various machine learning models. The data is sourced from NASA's [GISS Surface Temperature Analysis (GISTEMP v4)](https://data.giss.nasa.gov/). The dataset includes global mean monthly, seasonal, and annual temperature records from 1880 to the present. Multiple models are utilized to predict and analyze temperature trends, including Linear Regression, Random Forest, RNN, SVR, and Gradient Boosting.

## 📂 Table of Contents

- [Project Description](#-project-description)
- [Installation](#-installation)
- [Usage](#-usage)
- [Data Preprocessing](#-data-preprocessing)
- [Model Training and Evaluation](#-model-training-and-evaluation)
- [Results](#-results)
- [Visualization](#-visualization)
- [References](#-references)

## 📝 Project Description

The project includes:

- Loading and preprocessing global temperature data.
- Splitting the data into training and testing sets.
- Standardizing features.
- Training various machine learning models to predict temperatures.
- Evaluating model performance.
- Visualizing model predictions and temperature trends over time.

## 🛠️ Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/Dipti2021/globalwarming_dr.git
   ```
2. Navigate to the project directory:

```bash
cd globalwarming_dr
```

3. Install the required packages:

```bash
 pip install -r requirements.txt
```

## ▶️ Usage

1. Ensure the `GlobalTemperatures.csv` file is in the project directory.
   - The dataset can be downloaded from [GISS Surface Temperature Analysis (GISTEMP v4)](https://data.giss.nasa.gov/), specifically from the [Global-mean monthly, seasonal, and annual means, 1880-present](https://data.giss.nasa.gov/gistemp/).
2. Run the jupyter notebook

## 🔄 Data Preprocessing

1. Load Data: Load data from GlobalTemperatures.csv.
2. Data Cleaning: Replace '\*\*\*' with NaN and convert data to numeric.
3. Feature Engineering: Split data into features (X) and target (y).
4. Standardization: Standardize features using StandardScaler.

## 🧠 Model Training and Evaluation

The following models are trained and evaluated:

- Linear Regression
- Random Forest Regression
- Recurrent Neural Network (RNN)
- Support Vector Regression (SVR)
- Gradient Boosting Regression

## 📊 Results

Model Performance (Mean Squared Error - MSE)

| Model                        | Mean Squared Error (MSE) |
| ---------------------------- | ------------------------ |
| Linear Regression            | 1.2534478212723646e-05   |
| Random Forest Regression     | 0.0013798172413793087    |
| RNN                          | 0.0004137594654409371    |
| SVR                          | 0.002840265153870605     |
| Gradient Boosting Regression | 0.0018607360500542598    |

## 📈 Visualization

1. Loss History
2. Model Predictions:

- Linear Regression
- Random Forest
- RNN
- SVR
- Gradient Boosting

3. Temperature Trends

## 📚 References

- [Global Temperature Anomalies](https://data.giss.nasa.gov/gistemp/)
- [Scikit-Learn Documentation](https://scikit-learn.org/stable/documentation.html)
- [Keras Documentation](https://keras.io/)

Feel free to contribute to this project by opening issues and pull requests. Let's work together to understand and predict global temperature trends! 🌍📈
