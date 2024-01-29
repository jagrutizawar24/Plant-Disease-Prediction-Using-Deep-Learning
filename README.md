Plant-Disease-Prediction-Using-Deep-Learning
Overview
Welcome to the Plant Disease Classification System, a smart solution for early detection of diseases in plants using deep learning. This system leverages Convolutional Neural Networks (CNNs) to analyze plant images and accurately classify whether a plant is healthy or affected by a disease. The goal of this project is to provide farmers with a user-friendly tool that enables them to make informed decisions for better crop yields and sustainable farming practices.

Table of Contents
Project Components
1. Dataset
2. Model Development
3. Deployment
4. API Testing
5. User Interface
How to Use
Project Components
1. Dataset
The model was trained on a diverse dataset gathered from Kaggle, comprising images of both healthy plants and plants with various diseases. The dataset covers different plant species and a wide range of disease types, ensuring the model's effectiveness across various crops.

2. Model Development
The deep learning model was developed and trained using Jupyter Notebook, TensorFlow, and Keras. The Convolutional Neural Network architecture was chosen for its suitability in image-related tasks. Fine-tuning of model parameters was performed to enhance accuracy and adaptability to different plant types.

3. Deployment
The trained model is deployed as a web service using FastAPI, a fast and efficient web framework. Docker was employed to containerize the application, ensuring consistency across environments and facilitating a smooth deployment process.

4. API Testing
Postman, a widely-used tool for API testing, was utilized to ensure the functionality of the API. Sample plant images were sent to the API, and the responses were validated to ensure accurate disease classifications.

5. User Interface
The frontend application, developed with React JS, allows farmers to easily upload plant images. Upon image upload, the application sends a request to the FastAPI backend. TensorFlow Serving is then employed to classify the image using the trained model, and the predicted disease or healthy status is displayed to the user.
