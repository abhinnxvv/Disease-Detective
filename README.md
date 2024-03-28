# Disease Diagnosis Chatbot - Disease Detective

This is a medical diagnosis chatbot that helps users identify possible diseases based on their symptoms. The chatbot is trained using machine learning models such as K-Nearest Neighbors (KNN) and Decision Trees (DT).

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
1. Install dependencies using `pip install -r requirements.txt`.
2. Run the application using `python app.py`.

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

## Note
This README assumes that the application is run locally. Make sure to update the file paths and configurations as necessary if deploying it in a different environment.
