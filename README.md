# Kubernetes Microservice API 

Operationalized a fault tolerant machine learning microservice API using AWS and Kubernetes.

Deployed a containerized Python/Flask application to serve out predictions (inference) about 
housing prices through API calls. My Flask microservice uses a a pre-trained, sklearn model 
that has been trained to predict housing prices in Boston according to several features.

Deployed my Kubernetes cluster, configured my Kubernetes autoscale and load tested my Kubernetes 
application.

### Technologies:
AWS Lambda, Docker, Flask, Kubernetes (Container Orchestration), NumPy, Pandas, PyLint, Python, Scikit-Learn.

## Getting Started 

### Setup the Environment
Create a virtualenv and activate it
python3 -m venv <your_venv>
source <your_venv>/bin/activate

Run make install to install the necessary dependencies

### Running app.py
1) Standalone: python app.py
2) Run in Docker: ./run_docker.sh
3) Run in Kubernetes: ./run_kubernetes.sh

### Kubernetes Steps
1) Setup and Configure Docker locally
2) Setup and Configure Kubernetes locally
3) Create Flask app in Container
4) Run via kubectl