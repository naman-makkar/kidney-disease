# Chronic Kidney Disease Prediction 🩺

A machine learning-powered web application for predicting the risk of chronic kidney disease based on various health parameters.

## Overview 🔍

This project implements a predictive model for chronic kidney disease (CKD) using machine learning algorithms. The model analyzes 18 different health parameters, including age, blood pressure, and albumin levels, to assess the risk of developing CKD. A Flask-based web interface allows users to input their health data and receive real-time prediction results.

## Features ✨

- **Predictive Analysis**: Uses Decision Tree and Logistic Regression algorithms to analyze risk factors and predict CKD onset
- **Interactive Web Interface**: Flask-based application with user-friendly input forms
- **Real-time Results**: Instant prediction results based on user inputs
- **Comprehensive Parameter Analysis**: Evaluates 18 different health parameters
- **Data Visualization**: Visual representation of important features and their impact on predictions

## Technology Stack 💻

- **Frontend**: HTML, CSS, JavaScript
- **Backend**: Flask
- **Data Processing**: Pandas, NumPy
- **Machine Learning**: Scikit-learn (Decision Tree, Logistic Regression)

## Data Preprocessing Pipeline 🧹

The project implements robust data preprocessing pipelines to ensure high-quality input for the machine learning models:

1. **Data Cleaning**: Handling missing values and outliers in the dataset
2. **Feature Scaling**: Normalizing numeric features to improve model performance
3. **Feature Selection**: Identifying the most predictive parameters for CKD
4. **Data Transformation**: Converting categorical variables to numerical representations
5. **Train-Test Split**: Proper dataset division for model training and validation

## Model Training and Optimization 🚀

The machine learning pipeline includes:

1. **Algorithm Selection**: Comparing multiple algorithms to find the best performer
2. **Hyperparameter Tuning**: Grid search to optimize model parameters
3. **Cross-Validation**: K-fold cross-validation to ensure model reliability
4. **Model Evaluation**: Comprehensive metrics including accuracy, precision, recall, and F1-score
5. **Ensemble Methods**: Combining predictions for improved accuracy

## Large Dataset Processing 📊

The project efficiently handles large medical datasets through:

1. **Chunked Processing**: Loading and processing data in manageable chunks
2. **Parallel Computing**: Utilizing multi-core processing for faster data manipulation
3. **Memory Optimization**: Reducing memory footprint through efficient data types
4. **Incremental Learning**: Training models on data batches for scalability
5. **Caching Strategies**: Implementing intermediate results caching for faster reprocessing

## Installation 🛠️

```bash
# Clone the repository
git clone https://github.com/naman-makkar/kidney-disease.git
cd kidney-disease

# Create and activate virtual environment
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate

# Install dependencies
pip install -r requirements.txt

# Run the application
python app.py
```

## Usage 📝

1. Start the Flask application
2. Navigate to `http://localhost:5000` in your web browser
3. Fill in the required health parameters
4. Click "Predict" to see your CKD risk assessment
