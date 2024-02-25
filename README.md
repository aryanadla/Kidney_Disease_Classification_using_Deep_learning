# Kidney_Disease_Classification_using_Deep_learning
This project tries to diagnose kidney illness using deep learning techniques, notably MLflow for experiment tracking and DVC for versioning. The dataset includes several kidney-related characteristics, including age, blood pressure, and serum creatinine.

# Setup
Install dependencies: pip install -r requirements.txt
Initialize DVC: dvc init
Configure MLflow: mlflow server --default-artifact-root dvc://path/to/your/data --host 0.0.0.0 --port 5000
