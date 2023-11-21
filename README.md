# crop-disease-prediction-level-fml
# Crop Disease Prediction System

## Overview
The Crop Disease Prediction System is a machine learning project designed to predict and identify diseases in crops. This system utilizes a trained model to analyze images of crops and provide predictions on whether the crops are affected by diseases.

## Features
- Image Upload: Users can upload images of crops they suspect to be diseased.
- Disease Prediction: The system predicts whether the uploaded crop images contain signs of diseases.
- Confidence Score: The prediction is accompanied by a confidence score, indicating the model's level of certainty.

## Prerequisites
Before using the Crop Disease Prediction System, ensure you have the following dependencies installed:
- Python 3.x
- Required Python libraries (list them, e.g., TensorFlow, OpenCV, Flask)

## Installation
1. Clone the repository: `git clone https://github.com/your-username/crop-disease-prediction.git`
2. Install dependencies: `pip install -r requirements.txt`

## Usage
1. Run the application: `python app.py`
2. Open your web browser and navigate to `http://localhost:5000`
3. Upload a crop image and submit for prediction.
4. View the prediction results, including the predicted disease and confidence score.

## Folder Structure
- `/data`: Contains the dataset used for training the model.
- `/models`: Stores the trained machine learning model.
- `/static`: Contains static files such as CSS and images for the web interface.
- `/templates`: HTML templates for the web interface.
- `app.py`: The main application file.

## Training (Optional)
If you want to train the model with your own dataset, follow these steps:
1. Place your dataset in the `/data` directory.
2. Run the training script: `python train_model.py`
3. The trained model will be saved in the `/models` directory.

## Contributors
- [Kalki Kartik](github.com/KalkiKartik)

## License
This project is licensed under the [MIT License](LICENSE).

## Acknowledgments
- Mention any additional resources or references you used in your project.
