##End to End machine learing project 
#  Student Exam Performance Prediction
## End-to-End Machine Learning Project | From Data to Deployment

This project is a **complete End-to-End Machine Learning application** designed using **industry-level architecture and MLOps practices**.  
It predicts a student’s **math exam score** based on academic and demographic features using a production-ready ML pipeline and a web application.

---

##  Project Overview

The goal of this project is to demonstrate how a **real-world ML system** is built — not just model training, but the **entire ML lifecycle**, including:

- Data ingestion and preprocessing
- Model training and evaluation
- Experiment tracking
- Model serialization
- Prediction pipeline
- Web application deployment
- Containerization using Docker

---

##  Problem Statement

Predict a student’s **math score** using the following features:
- Gender
- Race/Ethnicity
- Parental level of education
- Lunch type
- Test preparation course
- Reading score
- Writing score

---

## Architecture & Workflow

1. **Data Ingestion**
   - Load raw dataset
   - Perform train-test split
   - Store artifacts

2. **Data Transformation**
   - Handle missing values
   - Encoding of categorical features
   - Scaling numerical features
   - Save preprocessing pipeline

3. **Model Training**
   - Train multiple ML models
   - Evaluate using performance metrics
   - Select the best-performing model

4. **Model Evaluation**
   - Compare model performance
   - Finalize best model

5. **Prediction Pipeline**
   - Load trained model and preprocessor
   - Transform user input
   - Generate predictions

6. **Web Application**
   - Flask-based UI
   - Real-time predictions

7. **MLOps Integration**
   - MLflow for experiment tracking
   - DagsHub for dataset & experiment versioning
   - Docker for containerization

---

##  Project Structure (Industry-Level)
End-to-End-Machine-Learning-Project/
│
├── app.py # Flask application
├── requirements.txt # Project dependencies
├── setup.py # Package configuration
├── README.md # Project documentation
│
├── notebook/ # EDA & experimentation
│
├── src/ # Production-ready code
│ ├── components/
│ │ ├── data_ingestion.py
│ │ ├── data_transformation.py
│ │ └── model_trainer.py
│ │
│ ├── pipeline/
│ │ ├── train_pipeline.py
│ │ └── predict_pipeline.py
│ │
│ ├── logger.py
│ ├── exception.py
│ └── utils.py
│
├── artifacts/ # Model & preprocessor outputs
├── logs/ # Application logs
└── Dockerfile # Docker configuration


---

## ⚙️ Tech Stack

- **Programming Language:** Python  
- **Machine Learning:** Scikit-Learn, CatBoost, XGBoost  
- **Web Framework:** Flask  
- **Experiment Tracking:** MLflow  
- **Version Control (Data & Experiments):** DagsHub  
- **Database:** MongoDB  
- **Containerization:** Docker  
- **Source Control:** Git & GitHub  


