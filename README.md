# Breast-Cancer-Prediction-Model

## Overview
This project aims to develop a machine learning model to predict breast cancer using patient data. The model is designed to assist in early detection and improve treatment outcomes by providing accurate predictions based on input features.

## Features
* Data Collection and Preprocessing: Utilizes the Wisconsin Breast Cancer Dataset.
* Feature Engineering: Extracts significant features to enhance predictive performance.
* Model Development: Implements various machine learning algorithms.
* Model Evaluation: Uses cross-validation and performance metrics to ensure high accuracy and reliability.
* Deployment: Provides a web-based application for real-time predictions.

## Libraries Used
* Python: Core programming language used for development.
* pandas: For data manipulation and analysis.
* numpy: For numerical computations.
* scikit-learn: For machine learning algorithms and model evaluation.
* Flask: For deploying the model as a web application.
* matplotlib: For data visualization.
* seaborn: For statistical data visualization.

## Installation
### Clone the repository:
bash
Copy code
git clone https://github.com/Ugofebe/Breast-Cancer-Prediction-Model.git
Navigate to the project directory:
bash
Copy code
cd Breast-Cancer-Prediction-Model

## Install the required libraries:
bash
Copy code
pip install -r requirements.txt

## Usage
* Data Preprocessing: Run the script to preprocess the data.
bash
Copy code
python data_preprocessing.py

* Model Training: Train the model using the preprocessed data.
bash
Copy code
python train_model.py

* Model Evaluation: Evaluate the model's performance.
bash
Copy code
python evaluate_model.py

* Web Application: Run the Flask web application for real-time predictions.
bash
Copy code
python app.py

## Project Structure
data_preprocessing.py: Script for data cleaning and preprocessing.
train_model.py: Script for training the machine learning model.
evaluate_model.py: Script for evaluating the model's performance.
app.py: Flask application for deploying the model.
templates/: Contains HTML templates for the web application.
static/: Contains static files like CSS and JavaScript for the web application.

## Results
The breast cancer prediction model achieved:

Accuracy: 98%
Recall: 97%
These results indicate the model's effectiveness in accurately predicting breast cancer, potentially aiding in early detection and timely medical intervention.

## Contact
For any questions or suggestions, please contact me at ugofebe@gmail.com.

## License
This project is licensed under the MIT License. See the LICENSE file for more details.
