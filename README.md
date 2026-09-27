# Employee Attrition NLP Analysis

## Project Overview

This project combines machine learning, natural language processing, sentiment analysis, topic identification, policy retrieval, and evidence-based explanations to analyze employee attrition risk.

## 5-Day Workflow

### Day 1 — Employee Attrition Prediction
- IBM HR Analytics dataset
- Data preprocessing
- One-hot encoding
- Random Forest classification
- Attrition risk probability
- Feature importance analysis

### Day 2 — Exit Interview Analysis
- Synthetic exit interview dataset
- Sentiment analysis using TextBlob
- Keyword-based topic identification

### Day 3 — Integrated Analysis
- Combined attrition risk with sentiment and topics
- Risk-level and topic analysis

### Day 4 — HR Policy Retrieval
- Created a sample HR policy knowledge base
- Implemented keyword-based policy retrieval
- Tested retrieval using employee-related questions

### Day 5 — Evidence-Based Explanations
- Combined attrition risk, interview sentiment, topics, and relevant policies
- Generated explanations for employees with available interview information

## Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- TextBlob
- Matplotlib
- Google Colab
- GitHub

## Model

A Random Forest classifier was used as the baseline attrition prediction model.

The model achieved approximately 85% overall accuracy on the test set. However, recall for the attrition class was low, so the result should be considered a baseline rather than a highly reliable attrition detector.

## Important Data Note

The IBM HR Analytics dataset is used as the underlying employee dataset.

The exit interview transcripts and HR policies used in this project are synthetic/project-created data designed to demonstrate the NLP, retrieval, and explanation workflow. They are not real employee responses or official company policies.

## Project Structure

employee-attrition-nlp/
- Employee_Attrition_NLP_Analysis.ipynb
- data/
- results/
- README.md
- requirements.txt
