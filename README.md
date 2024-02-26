# Spotify Recommendation System using FastAPI

In this project, I've built an spotify recommendation system to individual preferences. Just type your favorite song name and year, it will give you a list of music recommendations based on your preferences.

To do this, I performed various tasks, including Data cleaning, Feature engineering, Exploratory Data Analysis (EDA), Data preprocessing, fetching data using Spotify Web APIs, Model development and Model serving using FastAPI

## DATASET
This dataset is taken from : https://www.kaggle.com/datasets/vatsalmavani/spotify-dataset/data<br/>

## Acknowledgements
`Thanks to Spotify Web API that makes it easy for developers to fetch data and query Spotify’s catalog for songs`

## Installation

1. Clone the repository:

   ```
   git clone https://github.com/CodeWithCharan/Spotify-Recommender-Project-FastAPI.git
   ```

2. Create a virtual environment (optional): [Virtual Environment Set Up](https://github.com/CodeWithCharan/virtual-env-setup)

3. Install the required dependencies:

    ```
    pip install -r requirements.txt
    ```


4. Run the uvicorn app:
    ```
    uvicorn main:app --reload  
    ```

## Usage
After running the app, open your browser and go to `http://127.0.0.1:8000/docs` to use the app. Now, Enter your favorite song name and year to get personalized recommendations.