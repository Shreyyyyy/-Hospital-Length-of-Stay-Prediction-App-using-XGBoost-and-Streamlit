# 🏥 Hospital Length of Stay Prediction App using XGBoost and Streamlit

This repository contains a machine learning-powered web application that predicts the length of stay for hospital patients based on various medical details. Built using **XGBoost** and **Streamlit**, the app provides an intuitive interface for healthcare providers to input patient information and receive real-time predictions.

## 🚀 Project Overview

This project leverages patient data (e.g., age, diagnosis, severity of illness) and machine learning to predict the number of days a patient might stay in the hospital. Accurate predictions of length of stay can help healthcare facilities optimize resource allocation, enhance patient care, and streamline discharge planning.

### Features
- **User-friendly Interface**: Built with **Streamlit**, the app allows healthcare providers to input data through sliders, dropdowns, and text boxes.
- **Real-time Predictions**: After inputting patient details, the app predicts the length of stay using a machine learning model (XGBoost).
- **Customizable and Scalable**: Easily adaptable for different types of patient data or healthcare environments.

## 📂 File Structure
├── ada.csv # Sample dataset (not included in the repo) ├── xgb_model_pipeline.pkl # Trained XGBoost model ├── app.py # Streamlit app code ├── model_training.py # Script for training the model ├── README.md # Project documentation


## 💻 Setup and Installation

### Prerequisites
- **Python 3.x**
- **pip** for package management

### Install Dependencies
To get started, clone the repository and install the required Python packages:
```bash
git clone https://github.com/yourusername/hospital-length-of-stay-prediction.git
cd hospital-length-of-stay-prediction
pip install -r requirements.txt
