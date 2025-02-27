# Pneumonia-Detection-CNN
A deep learning-based pneumonia detection system that classifies chest X-ray images as 'Normal' or 'Pneumonia' using a Convolutional Neural Network (CNN). The model is deployed using Streamlit for an interactive user interface.

🩺 Pneumonia Detection Using CNN

📌 Project Overview

This project is a deep learning-based pneumonia detection system that classifies chest X-ray images as 'Normal' or 'Pneumonia' using a Convolutional Neural Network (CNN). The application is built with Streamlit for an interactive user interface.

✅ Features

Image Upload: Upload chest X-ray images in JPG, JPEG, or PNG format.

Automated Image Processing:

Resizes images to 224x224 pixels.

Converts them into arrays and normalizes pixel values.

Deep Learning Model:

Uses a trained CNN model (my_pneumonia_detection_model.h5).

Outputs classification with confidence percentage.

User-Friendly UI:

Built using Streamlit for easy interaction.

Provides color-coded alerts for quick decision-making.

🛠 Tools & Technologies Used

Deep Learning: TensorFlow, Keras

Framework: Streamlit

Image Processing: OpenCV, Pillow

Programming Language: Python

📡 System Workflow

User Uploads an Image

The user selects a chest X-ray image.

Preprocessing the Image

Resizes to 224x224 pixels.

Converts to an array and normalizes it.

Model Prediction

Loads the trained model and makes a prediction.

Outputs either ‘Normal’ or ‘Pneumonia’ with a confidence score.

Displaying Results

Shows prediction results on Streamlit UI.

Provides alerts for Pneumonia detection.

🚀 Deployment Options

Local Deployment: Run Streamlit locally using streamlit run app.py.

Cloud Deployment: Deploy on Streamlit Cloud, Heroku, or AWS.

📌 Future Improvements

Enhanced Model Performance: Train with a larger dataset for higher accuracy.

Mobile Compatibility: Develop a mobile-friendly UI.

Integration with Healthcare Systems: Connect to hospital databases for real-time diagnosis.

👨‍💻 Author

Jashan Kamboj

GitHub: https://github.com/jashankaamboj

Email: jashankaamboj@gmail.com

