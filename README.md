# Medical Diagnostic System using Machine Learning and NLP

## Overview

This project is a **Medical Diagnostic System** built using **Python**, **Flask**, **Machine Learning**, and **Natural Language Processing (NLP)**. It allows users to input symptoms, processes the data to find matches with known medical conditions, and provides potential diagnoses and recommendations based on symptom severity. The system leverages pre-trained models, semantic and syntactic similarity analysis, and a structured medical dataset to offer accurate results.

## Features

- **Symptom Matching**: Uses NLP techniques to match user-input symptoms with known medical symptoms in the dataset.
- **Disease Prediction**: Utilizes a pre-trained **KNN (k-nearest neighbors)** classifier for predicting diseases based on input symptoms.
- **Severity Analysis**: Assesses the severity of symptoms and suggests medical consultation if needed.
- **Symptom Description and Precautions**: Provides detailed descriptions of symptoms and precautions based on the analysis.
- **User Interaction**: Offers a step-by-step conversational flow using Flask to make it easy for users to provide symptom information.

## Technologies Used

- **Python**: Main programming language.
- **Flask**: Web framework for building the interface and handling user interaction.
- **Pandas & NumPy**: For data handling and numerical operations.
- **NLTK & Spacy**: For NLP tasks such as lemmatization, tokenization, and similarity analysis.
- **Joblib**: For loading pre-trained ML models.
- **Machine Learning**: Pre-trained **KNN classifier**.
- **HTML/CSS**: For basic web page design.

## Dataset

The application uses several datasets to drive the diagnosis:

- `Training.csv`: Dataset for training the machine learning model. Contains combinations of symptoms and diagnosed diseases.
- `Testing.csv`: Dataset for validation purposes.
- `symptom_Description.csv`: Contains descriptions for symptoms.
- `symptom_severity.csv`: Lists the severity of each symptom.
- `symptom_precaution.csv`: Provides precautionary measures for each disease.

## Installation

### Prerequisites

Ensure you have the following installed:

- **Python 3.7+**
- **Pip** (Python package manager)

### Step-by-Step Installation

1. **Clone the Repository**:
   
   ```bash
   https://github.com/SEC-NLP-2026-C/disease-prediction-chatbot.git
