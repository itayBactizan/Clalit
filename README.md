# Disease Detection Project

This project analyzes health-related data to classify disease types using Python and PySpark for data preparation, and scikit-learn/XGBoost and DecisionTree for modeling and SHAP interpretability.

## 🚀 Getting Started

### 1. Build the Docker Image

docker build -t disease-detection .

### 2. Run the Docker Container
docker run --rm -p 8888:8888 -v "%cd%\app:/app" -w /app disease-detection

### 3. Open Jupyter Notebook
In your browser, go to: http://127.0.0.1:8888/tree

### 4. Start Working
Open the notebook: DiseaseDetection.ipynb

The dataset is available as: Prediction home assignment data.csv

