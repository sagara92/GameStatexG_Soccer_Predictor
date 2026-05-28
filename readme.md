# Predict Soccer Matches using Machine Learning Models

This project is an end-to-end proof of concept for English Premier League (EPL) exploratory data analysis (EDA) and ML Models predictions:

- Scrapes season match data from `understatapi`
- Runs EDA on raw data
- Creates model-ready features with a private function (hidden by gitignore)
- Trains multiple match home/away goals models in Python
- Serves predictions through a FastAPI endpoint



## Web Application
- See `eda_model_train.ipynb` for model and training detail
- App is hosted in HuggingFace Space
- Takes three inputs from user `home team`, `away team`, and `model name`, uses home and away models to predict scores with the probability of each scoreline
- Web application: [https://www.adhikari-sagar.com.np/projects](https://www.adhikari-sagar.com.np/projects)

## Data & Privacy

- Dataset is freely available through understatapi.