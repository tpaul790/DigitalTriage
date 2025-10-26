Digital Triage System

Overview
The Digital Triage System is a rule-based application designed to assist individuals in identifying the most appropriate healthcare professional based on their symptoms.
The app allows users to input their symptoms, severity, and medical history to recommend the most likely diagnosis and provide the appropriate provider (e.g., General Practitioner, Cardiologist, etc.).
This app uses a simple rule-based approach to match symptoms to possible conditions and determines the urgency and confidence of the diagnosis based on user inputs.

Features
    * Symptom Selection: Users can select from a list of symptoms (such as fever, headache, cough, etc.).
    * Severity Selector: A slider allows users to select the severity level of their symptoms.
    * Personal Information: Users are asked to input their name, age, and medical history.
    * Analysis Button: After inputting symptoms and severity, the user can press the "Analyze Symptoms" button to receive a recommendation.

Results(what the app shows):
   * Primary diagnosis (condition)
   * Recommended healthcare provider
   * Urgency (e.g., emergency or routine)
   * Confidence in the diagnosis
   * Alternative conditions to consider

Prerequisites
    Python 3.x
    Kivy and KivyMD libraries

Installation Steps
    Clone the repository or download the app's code.
    Create a virtual environment (optional but recommended):

    ** python -m venv .venv **

Install the required dependencies:
    pip install -r requirements.txt

Run the app:
    python main.py
