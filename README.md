# NLP-Relationship-Satisfaction

# NLP Relationship Satisfaction Analysis (Malaysia)

## Project Overview
This project uses Natural Language Processing (NLP) to analyze users’ satisfaction with their romantic partners in Malaysia using code-mixed Malay-English text.

## Dataset
- 1200 labeled samples
- Classes: Positive, Negative, Neutral
- Language: Bahasa Melayu + English (Bahasa Rojak)

## Model Used
- TF-IDF Vectorization
- Logistic Regression Classifier

## Pipeline
Data → Preprocessing → TF-IDF → Logistic Regression → Evaluation

## Evaluation Metrics
- Accuracy
- Precision
- Recall
- F1-score
- Confusion Matrix

## How to Run
1. Upload dataset3a.csv to Colab
2. Run notebook sentiment_analysis_colab.ipynb
3. View results

## Requirements
Install dependencies:

pip install -r requirements.txt


## Limitations
- Dataset is partially synthetic
- Code-mixed language complexity
- Limited real-world generalization

## Author
STINK3114 NLP Assignment
