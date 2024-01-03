# NetworkThreatClassifier
Network Traffic Analysis for Threat Intelligence

Description:
This project contains the development of a simple model that detects for threats in network traffic data. It works by classifying the traffic as either normal or malicious based on various types of characteristics. For the purpose of training and testing, I used the CICIDS2017 dataset as it came up as a credible and reputable one for models like mine in my searches.

Sharafaldin, Iman, Arash Habibi Lashkari, and Ali A. Ghorbani. "Toward generating a new intrusion detection dataset and intrusion traffic characterization." ICISSP 2018 (2018): 108-116.

+-----+

Project Structure:

Data Preprocessing: This section covers the data loading, cleaning, normalization, and encoding processes.

Model Building: Details about the neural network architecture, including layers, neurons, and activation functions.

Model Training: Description of the training process, including loss functions, optimizers, and training/validation splits.

Model Evaluation: Evaluation of the model performance using metrics such as accuracy, confusion matrix, etc.

API Deployment: Steps for deploying the model using Flask and instructions for accessing it via an API endpoint.

+-----+

Installation requirements to run:
Python 3.x
Libraries: TensorFlow, scikit-learn, Flask (plus additional libraries as per the requirements, see main file's first code block for further details)

To run the project, clone the repository, install the required libraries, and execute the Jupyter notebook. For API usage, run the Flask app and access the provided endpoint for model predictions.

Side note: as I originally ran this in colab, the filepaths indicate so. You may need to change them accordingly if you decide to run on local.
