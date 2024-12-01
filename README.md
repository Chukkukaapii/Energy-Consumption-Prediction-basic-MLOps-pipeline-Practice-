# MLOps Pipeline for Consumption Prediction

## Objective
The objective of this project is to build and automate an end-to-end MLOps pipeline for predicting consumption using machine learning models. This includes stages such as data preprocessing, model training, evaluation, deployment, and monitoring. The aim is to automate the machine learning lifecycle to ensure continuous integration, continuous deployment, and efficient model management. This project leverages tools like Scikit-learn, TensorFlow, Docker, GitHub Actions, and Prometheus for model deployment and monitoring.

## Requirements

- Python 3.x
- Pandas
- Scikit-learn
- TensorFlow
- Docker
- GitHub Actions (for CI/CD)
- Prometheus (for monitoring)

## Steps to Run

1. **Clone the Repository**

    ```bash
    git clone https://github.com/your-username/mlops-pipeline-consumption-prediction.git
    cd mlops-pipeline-consumption-prediction
    ```

2. **Install Dependencies**

    ```bash
    pip install -r requirements.txt
    ```

3. **Run the Data Preprocessing and Model Training**

    To preprocess the data and train the model, use the following command:

    ```bash
    python train_model.py
    ```

4. **Deploy the Model**

    The model can be deployed using Docker. Build the Docker container and run the following:

    ```bash
    docker build -t consumption-prediction .
    docker run -p 5000:5000 consumption-prediction
    ```

