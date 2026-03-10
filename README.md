# Social Media Sentiment Analysis

This project analyzes tweet sentiment with a Logistic Regression model and provides a Streamlit app for interactive predictions and visualizations.

## Project structure
- `sentiment/train.py`: trains and saves the sentiment model.
- `sentiment/app.py`: Streamlit UI for inference and charts.
- `sentiment/preprocess.py`: text cleaning and sentiment helper utilities.
- `sentiment/visualizations.py`: chart utilities.
- `sentiment/twitter_training.csv`: training data.
- `sentiment/twitter_validation.csv`: validation data.

## Setup
```bash
python -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
```

## Run
Train the model:
```bash
python sentiment/train.py
```

Launch the app:
```bash
streamlit run sentiment/app.py
```

## Notes
- The training and validation CSV files are included in this repository.
- If NLTK resources are not present, the first run may download them.
