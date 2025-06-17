# AWS-Sagemaker
Smartphone Price Predictor
A web application that predicts smartphone price ranges using a machine learning model deployed on AWS SageMaker.

Features
Predicts smartphone price range in 4 categories:
Budget mobile phone,
Lower mid-range phone,
Upper mid-range phone,
Premium phone.
Interactive web interface with real-time predictions.
Responsive design that works on desktop and mobile devices.
Handles 20 different smartphone specifications for prediction.

ML Model Deployment: AWS SageMaker,
Prerequisites:
AWS Account with appropriate credentials
Boto3 library,
scikit-learn,
joblib,
numpy,
pandas,
sagemaker,
argparse,
ipykernel.
Flask Installation:
pip install flask boto3
Configure AWS credentials:
aws configure,
AWS_ACCESS_KEY_ID='your-access-key',
AWS_SECRET_ACCESS_KEY='your-secret-key',
AWS_REGION='ap-south-1'.
Usage:
Start the Flask application:
python app.py
Open a web browser and navigate and

Enter the smartphone specifications in the form:

Basic specifications (RAM, storage, processor, etc.)
Camera details
Screen specifications
Additional features (Bluetooth, WiFi, etc.)
Click "Predict Price Range" to get the prediction
