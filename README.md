# Fraud Detection Prediction App

A Machine Learning-powered fraud detection application built using Python, Scikit-Learn, and Streamlit to predict whether a financial transaction is fraudulent.

## Project Overview

This project predicts whether a financial transaction is fraudulent based on transaction details such as:

- Transaction Type
- Transaction Amount
- Sender Balance
- Receiver Balance

The model is trained using machine learning classification techniques and deployed with an interactive Streamlit web application.

## Features

- Interactive Streamlit UI
- Real-time fraud prediction
- Machine Learning prediction pipeline
- Clean and user-friendly interface
- Model deployment ready

## Tech Stack

- Python
- Pandas
- NumPy
- Scikit-Learn
- Streamlit
- Joblib
- Jupyter Notebook

## Dataset

The complete training dataset (~250MB) is not included in this repository due to GitHub size limitations.
Dataset link: https://www.kaggle.com/datasets/abhinav4651/fraud-detection-dataset


## Project Structure

````txt
fraud-detection-app/
│
├── main.py
├── fraud_detection_pipeline.pkl
├── analysis_model.ipynb
├── fraud_detection_dataset.csv
├── requirements.txt
├── README.md
├── .gitignore
## Dataset

The dataset contains transaction-related information used to classify fraudulent and non-fraudulent transactions.

Features used include:

* Transaction Type
* Amount
* Old Balance (Sender)
* New Balance (Sender)
* Old Balance (Receiver)
* New Balance (Receiver)

## Installation

Clone the repository:

```bash
git clone https://github.com/Abhinav001-glitch/fraud-detection-app.git
````

Move into the project directory:

```bash
cd fraud-detection-app
```

Install dependencies:

```bash
pip install -r requirements.txt
```

Run the Streamlit application:

```bash
streamlit run main.py
```

## Model

This project uses a Machine Learning classification pipeline to predict fraudulent transactions based on financial transaction patterns.

## Future Improvements

- Improve model accuracy using advanced feature engineering
- Hyperparameter tuning
- Add probability/confidence score
- Deploy online using Streamlit Cloud
- Add transaction visualization dashboard

## Author

Abhinav Kumar

GitHub: https://github.com/Abhinav001-glitch
