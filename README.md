# Student Dropout Risk Prediction & Monitoring Dashboard

## 🚀 Overview
...

## 🧠 Model
...

## 🛠️ Technologies Used
...

## 📂 Project Structure
...

## ✅ How to Run Locally
1. Clone repo
2. Set up virtual environment
3. Install requirements
4. Run MLFlow UI
5. Start FastAPI server
6. Test API endpoints
7. Run monitoring scripts

## 📊 Sample Prediction
Input JSON → Output risk level

## 🖥️ Monitoring Dashboard Screenshot
...

## ✅ Future Improvements
- Add real-time data streaming
- Deploy to AWS / GCP
- Add alerting via Slack


## Project structure (so far...)

student_dropout_prediction/
├── data/
│   ├── raw/                # Original dataset (UCI or synthetic)
│   └── processed/          # Cleaned/feature-engineered data
├── notebooks/
│   └── exploratory_analysis.ipynb
├── src/
│   ├── data_preprocessing.py
│   ├── model_training.py
│   ├── inference_service.py        # FastAPI app here
│   └── monitoring_drift.py         # Evidently AI drift detector
├── docker/
│   ├── Dockerfile_api
│   └── Dockerfile_monitoring
├── mlflow_tracking/
│   └── mlflow_setup.sh
├── dashboard/ (Optional)
│   └── streamlit_app.py
├── requirements.txt
├── README.md
└── .gitignore

