# Swiggy Restaurant Recommendation System 🍽️

## Overview
A Streamlit app that recommends restaurants based on city, cuisine, rating, and cost. Built using Python, pandas, scikit-learn, and Streamlit.

## How It Works
- `cleaning.py` → Cleans raw restaurant data
- `encoding.py` → Encodes categorical features
- `recommendation.py` → Uses cosine similarity to find top matches
- `app.py` → Streamlit UI for user interaction

## How to Run
```bash
python cleaning.py
python encoding.py
python recommendation.py
streamlit run app.py
