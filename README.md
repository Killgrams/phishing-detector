# AI-Powered Phishing Email Detector & Reporter

## Project Overview
This project is a Python-based email filtering tool that uses natural language processing (NLP) and machine learning to:

- Detect phishing attempts in real-time
- Report suspicious emails to a dashboard
- Automatically flag or quarantine emails in an inbox simulation

## Key Features
- Email Parser: Load and parse .eml or plain-text email formats, extracting metadata such as sender, subject, body, links, and headers.
- Phishing Detection Engine: Uses an ML model (scikit-learn + TF-IDF or transformers like BERT) trained on phishing vs. legitimate emails.
- Threat Score System: Scores emails based on red flags like link obfuscation, urgent language, and mismatched headers.
- Web Dashboard: Flask or Streamlit UI to list flagged emails, show risk levels, and explanations.
- Auto-Quarantine Simulation: Moves flagged emails to a quarantine folder.
- Retraining: Option to retrain the model based on user feedback.

## Installation
Install dependencies with:

```
pip install -r requirements.txt
``` 

## Usage
Run the dashboard with:

```
streamlit run dashboard.py
```

## License
MIT License
