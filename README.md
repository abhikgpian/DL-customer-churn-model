## Customer Churn Prediction Web App

The web application is built with Streamlit for interactive user input and real-time churn probability prediction. The model is trained using customer data and uses features such as age, geography, credit score, and more to predict if a customer is likely to churn from a financial service.

## Features

### 1.User-friendly web interface for inputting customer attributes.

### 2.Data preprocessing with label encoding, one-hot encoding, and feature scaling.

### 3.ANN model for binary classification of customer churn.

### 4.Probability output with actionable insights.

### 5.Modular code structure for easy updates and maintenance.


## Installation
### 1.Clone the repository:-[git clone https://github.com/yourusername/customer-churn-prediction.git cd customer-churn-prediction](https://github.com/abhikgpian/DL-customer-churn-model.git)

### 2.Set up a virtual environment (optional but recommended):-python -m venv venv source venv/bin/activate  # On Windows: venv\Scripts\activate

### 3.Install dependencies:-pip install -r requirements.txt


## Usage
### Run the Streamlit application:-streamlit run app.py

### 1.Select customer attributes like Geography, Gender, Age, Balance, etc.

### 2.The app processes and scales inputs before predicting churn probability.

### 3.View the churn risk with an intuitive message.


## Model Details
### Model Architecture: Fully connected ANN with configurable hidden layers and neurons.

### Training Dataset: Customer data with 10 features such as Credit Score, Tenure, Balance, and more.

## Preprocessing:

### Label encoding for categorical features like Gender.

### One-hot encoding for Geography.

### Standard scaling of all features.

### Evaluation: Model tuning through GridSearchCV optimizing layers, neurons, and epochs.

### Saving Artifacts: Model, encoders, and scaler saved for inference.
