# Disease Detective

Disease Detective is a medical diagnosis chatbot that helps users identify possible diseases based on their symptoms. The chatbot is trained using machine learning models such as K-Nearest Neighbors (KNN) and Decision Trees (DT).

https://github.com/abhinnxvv/Disease-Detective/assets/92618378/27b97442-63a8-4c82-aacb-17c254a85aa8

## Table of Contents
- [Usage](#usage)
- [Dependencies](#dependencies)
- [Installation](#installation)
- [Files](#files)
- [Models Used](#models-used)
- [Functionality](#functionality)
- [Output](#output)

## Usage
1. Run the application.
2. Access the application through a web browser.
3. Enter your name, age, and gender when prompted.
4. Follow the instructions provided by the chatbot to describe your symptoms.
5. The chatbot will provide possible diseases based on the symptoms described.
6. Further interactions will guide you through severity assessment and precautionary measures.

## Dependencies
- pandas
- numpy
- nltk
- spacy
- joblib
- flask

## Installation
1. Clone the repository:
   ```sh
   git clone https://github.com/abhinnxvv/Disease-Detective.git
   ```
2. Navigate to the project directory:
   ```sh
   cd Disease-Detective
   ```
3. Install dependencies:
   ```sh
   pip install -r requirements.txt
   ```
4. Run the application:
   ```sh
   python app.py
   ```

## Files
- `Medical_dataset/Training.csv`: CSV file containing training data.
- `Medical_dataset/Testing.csv`: CSV file containing testing data.
- `model/knn.pkl`: Pre-trained KNN model.
- `Medical_dataset/symptom_Description.csv`: CSV file containing symptom descriptions.
- `Medical_dataset/symptom_severity.csv`: CSV file containing symptom severity data.
- `Medical_dataset/symptom_precaution.csv`: CSV file containing precautionary measures for symptoms.

## Models Used
- K-Nearest Neighbors (KNN)
- Decision Trees (DT)

## Functionality
The chatbot performs the following tasks:
- Collects user information (name, age, gender).
- Analyzes symptoms described by the user.
- Predicts possible diseases using machine learning models.
- Provides descriptions, severity assessment, and precautionary measures for identified diseases.
- Allows for multiple interactions to refine the diagnosis.

## Output
The following images illustrate the chatbot's functionality:

![Description](https://github.com/abhinnxvv/Disease-Detective/assets/92618378/72fc4401-0da7-4c67-b2aa-8a1a70591a0a)
*Fig 1: Chatbot describing the disease based on symptoms provided.*

![Symptoms 1](https://github.com/abhinnxvv/Disease-Detective/assets/92618378/17036b79-b67c-42fe-932b-cbf73321ccf4)
*Fig 2: Chatbot interaction with user to gather symptoms.*

![Symptoms](https://github.com/abhinnxvv/Disease-Detective/assets/92618378/271b9f76-66d5-4c23-a59f-062b492fb198)
*Fig 3: Symptoms analysis interface.*

![Analysis](https://github.com/abhinnxvv/Disease-Detective/assets/92618378/e9506bb7-bdfc-4357-a709-9a6241bc11bb)
*Fig 4: Detailed analysis of symptoms and suggested diagnoses.*
