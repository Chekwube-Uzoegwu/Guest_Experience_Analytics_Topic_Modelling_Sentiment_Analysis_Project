# Guest_Experience_Analytics_Topic_Modelling_Sentiment_Analysis_Project
End to end NLP project that analyses hotel guest reviews using BERTopic for topic modelling and DistilBERT for sentiment classification, turning unstructured feedback into actionable insights for hospitality analytics and service optimisation.

## Business Problem

Star ratings show how satisfied a guest was overall but not why. The reasons sit in review text, which is slow and inconsistent to read by hand at scale. This project builds an automated approach to identify what guests discuss and how they feel about each aspect of their stay.

## Objectives

1. Prepare guest review data for NLP and machine learning.
2. Discover and interpret recurring topics with BERTopic.
3. Analyse sentiment at topic level.
4. Compare traditional machine learning baselines with a BERT based model.
5. Track experiments with MLflow on DagsHub.
6. Translate the findings into business insights.

## Repository Structure

1. notebooks: the main Colab notebook.
2. data: derived datasets. No credentials are stored here.
3. models: references to saved model artefacts, which are kept in Google Drive and registered in MLflow.
4. reports: figures and written reports.
5. docs: project documentation.

## Setup

1. Install the packages with pip install -r requirements.txt.
2. Run python -m spacy download en_core_web_sm.
3. Download the NLTK packages punkt, punkt_tab and stopwords.
4. Store the database URL in Colab Secrets under the name DATABASE_URL. Never commit it.

## Project Status

Completed so far: data preparation, text preprocessing, BERTopic topic modelling, a Random Forest baseline, a DistilBERT sentiment model, and MLflow tracking. Still in progress: topic level sentiment analysis, additional baseline models, error analysis and the business insights report.
