# Skin Disease Detection System

## Overview
This project focuses on detecting skin diseases using a deep learning model implemented in Python with Keras and TensorFlow. The model leverages the MobileNetV2 architecture for image classification. The project includes a Flask web application for uploading skin lesion images and obtaining predictions about the skin disease.

## Project Structure
The project is divided into two main components:

1. **Flask Web Application:**
   - The `app.py` file contains the Flask application.
   - The application provides a user interface for uploading skin lesion images.
   - The user uploads an image, and the deep learning model predicts the skin disease category.
   - The predicted skin disease category is displayed to the user.

2. **Skin Disease Detection Model:**
   - The skin disease detection model is implemented in the `model.py` file.
   - The model is built using MobileNetV2 as the base model, followed by additional layers for classification.
   - The model is trained on the HAM10000 dataset, which includes images of various skin diseases.
   - Model training details, including accuracy and loss curves, are visualized in the notebook.

## Dependencies
Ensure you have the following dependencies installed:

- Flask
- TensorFlow
- Keras
- NumPy
- PIL (Pillow)
- scikit-learn
- gevent

You can install the necessary dependencies using the following:

```bash
pip install Flask tensorflow keras numpy Pillow scikit-learn gevent
```

## How to Run
1. Run the Flask web application by executing the `app.py` file.
2. Access the application through a web browser at `http://127.0.0.1:5000/`.
3. Upload a skin lesion image to obtain a prediction of the skin disease category.

## Model Training
The skin disease detection model is trained on the HAM10000 dataset, which includes various skin disease images. The model architecture includes MobileNetV2 as the base model, with additional layers for classification.

The training process and results, including accuracy and loss curves, are visualized in the notebook.

## Results
The Flask web application provides an interactive way to upload skin lesion images and receive predictions about the skin disease category based on the trained model.

## Author
Ved Prakash

Email-vedprakash108.hitcse2020@gmail.com

Feel free to reach out with any questions or feedback!

*Note: Ensure that you have the necessary hardware requirements for running the code, especially if using the GPU version of TensorFlow.*
