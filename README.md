# NLP-I-Corps-Survey-Insights
Portfolio project applying NLP and LLM methods to analyze NSF I-Corps open-ended survey responses.
This project demonstrates end-to-end text analysis, from cleaning and topic modeling to LLM-based summarization and visualization, with the goal of uncovering themes that inform program evaluation and improvement.

## Project Overview

STEM faculty and graduate students participating in the NSF I-Corps program complete surveys with open-ended responses about their learning goals and experiences. Manually coding these responses is time-consuming and inconsistent.
This project shows how modern NLP + LLM techniques can extract meaningful insights efficiently and reproducibly.

## Methods & Tools

- **Data Preparation**: text cleaning, de-identification, exploratory analysis  
- **Topic Modeling**: LDA baseline; BERTopic with transformer embeddings  
- **Goal Classification**: logistic regression (TF-IDF) + transformer-based models, tested on labeled subset  
- **LLM Summarization**: GPT-based prompts to generate human-readable summaries of themes  
- **Visualization**: matplotlib, seaborn, and interactive dashboards (Streamlit)

Libraries: `pandas`, `scikit-learn`, `spacy`, `bertopic`, `transformers`, `streamlit`


## Key Results 

- Identified recurring themes across responses  
- Developed a classifier to categorize participants’ goals, tested on a labeled subset for accuracy  
- Generated concise summaries of each theme with LLM prompts, including representative quotes  
- Presented findings via a Streamlit dashboard and a written report  
