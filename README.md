# 🌍 AQI Predictor: Air Quality Index Prediction Using Machine Learning

A machine learning-based web application that predicts the **Air Quality Index (AQI)** using air pollutant measurements. Built with Python and Streamlit, the application provides interactive predictions, model comparisons, visualizations, and health-related recommendations.

## 📌 Project Overview

Air pollution is a major environmental concern that affects human health and quality of life. Understanding air quality helps people make informed decisions about outdoor activities and potential health risks.

The AQI Predictor project uses machine learning regression algorithms to estimate AQI values based on pollutant measurements. It combines data preprocessing, model training, prediction, and visualization in an interactive web application.

## 🎯 Objectives

- Predict AQI using air pollutant measurements.
- Preprocess environmental data for machine learning.
- Train and compare multiple regression algorithms.
- Provide an interactive interface using Streamlit.
- Display AQI predictions and related health recommendations.
- Visualize model results and support CSV export.

## ✨ Features

- **AQI Prediction:** Estimate AQI using pollutant input values.
- **Multiple ML Models:** Linear Regression, Random Forest Regression, and XGBoost Regression.
- **Data Preprocessing:** Handle missing values and identify AQI outliers.
- **Model Comparison:** Compare the performance of different regression models.
- **Interactive Dashboard:** Enter pollutant measurements and view predictions.
- **Data Visualization:** Explore air quality data and model results.
- **Health Recommendations:** Display AQI categories and associated health advice.
- **CSV Export:** Download prediction results for further analysis.
- **Model Persistence:** Save and reuse trained model artifacts.

## 🛠️ Technologies Used

| Technology | Purpose |
|---|---|
| Python | Core programming language |
| Streamlit | Interactive web application |
| Pandas | Data manipulation and preprocessing |
| NumPy | Numerical computations |
| Scikit-learn | Machine learning and preprocessing |
| XGBoost | Gradient-boosting regression |
| Matplotlib / Configured plotting libraries | Data visualization |
| Git and GitHub | Version control and project hosting |

## 🧠 Machine Learning Algorithms

### 1. Linear Regression
A supervised learning algorithm used as a baseline for predicting continuous AQI values.

### 2. Random Forest Regression
An ensemble learning algorithm that combines multiple decision trees to capture nonlinear relationships between pollutant measurements and AQI.

### 3. XGBoost Regression
A gradient-boosting algorithm that builds trees sequentially to improve predictive performance.

The models are evaluated and compared to select a suitable model for prediction.

## 🌫️ Input Parameters

The documented pollutant inputs include:

- PM2.5
- PM10
- Nitrogen Dioxide (NO2)
- Sulphur Dioxide (SO2)
- Carbon Monoxide (CO)
- Ozone (O3)

The trained model uses the available pollutant measurements to estimate AQI.

## 📂 Project Structure

```text
AQI-Predicator/
│
├── data/
│   └── aqi_data.csv
│
├── models/
│   ├── scaler.pkl
│   ├── trained_model.pkl
│   └── model_results.json
│
├── src/
│   ├── data_preprocessing.py
│   ├── model_training.py
│   └── prediction.py
│
├── app.py
├── requirements.txt
└── README.md
```

## ⚙️ Installation and Setup

### Prerequisites

Make sure Python and Git are installed on your system.

### Step 1: Clone the Repository

```bash
git clone https://github.com/AayushKumar6465/AQI-Predicator.git
```

### Step 2: Navigate to the Project Directory

```bash
cd AQI-Predicator
```

### Step 3: Create a Virtual Environment

```bash
python -m venv venv
```

### Step 4: Activate the Virtual Environment

**Windows PowerShell:**

```powershell
.\venv\Scripts\Activate.ps1
```

**Windows Command Prompt:**

```cmd
venv\Scripts\activate.bat
```

### Step 5: Install Dependencies

```bash
python -m pip install -r requirements.txt
```

### Step 6: Run the Application

```bash
streamlit run app.py
```

Once the application starts, open the local URL displayed in your terminal to access the dashboard.

## 🔄 Workflow

1. Load the air quality dataset.
2. Preprocess the data and handle missing values.
3. Identify potential AQI outliers.
4. Train the regression models.
5. Evaluate and compare model performance.
6. Save the selected model and preprocessing artifacts.
7. Enter pollutant measurements through the web interface.
8. Generate and display the predicted AQI.
9. Explore visualizations and download results.

## 📊 Model Evaluation

Regression models can be evaluated using metrics such as:

- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)
- R-squared (R²)

The actual performance depends on the dataset, model configuration, and evaluation procedure. Refer to the project's generated evaluation results for measured values.

## 🌱 Applications

- Environmental data analysis
- Air quality awareness
- Machine learning education
- Exploratory pollution analysis
- Academic and research projects
- Prototype environmental monitoring applications

## 🔮 Future Enhancements

- Integration with live air quality APIs.
- Location-based AQI prediction.
- Air quality forecasting using historical data.
- Integration of weather parameters.
- Advanced data visualizations and geographical maps.
- Model explainability and prediction monitoring.
- Deployment as a publicly accessible web application.

## ⚠️ Limitations

- Predictions depend on the quality and representativeness of the training data.
- The application should not be assumed to provide real-time measurements unless connected to a live data source.
- Predicted AQI values are estimates and should not be treated as official environmental measurements.
- Model performance should be verified using appropriate test data.

## 👩‍💻 Author

**Project:** AQI Predictor — Air Quality Index Prediction Using Machine Learning

**Developed using:** Python, Streamlit, and Machine Learning

## 📄 License

Add a license file if you intend to distribute the project. Make sure the license is compatible with the original repository's license and that you have permission to redistribute the code and associated data.

## 🙌 Acknowledgements

This project is based on the AQI Predictor repository and demonstrates the application of machine learning techniques to environmental data analysis.

**Original Repository:** https://github.com/AayushKumar6465/AQI-Predicator
