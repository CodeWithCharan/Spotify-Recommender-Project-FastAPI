# Spotify Recommendation System using FastAPI

In this project, I've built an spotify recommendation system to individual preferences. Just type your favorite song name and year, it will give you a list of music recommendations based on your preferences.

To do this, I performed various tasks, including Feature engineering, Exploratory Data Analysis (EDA), fetching data using Spotify Web APIs, Model development and Model serving using FastAPI

## Video Presentation
https://github.com/CodeWithCharan/Spotify-Recommender-Project-FastAPI/assets/106027109/fdf95696-be0c-4442-b771-ee8b0424a0b1


## DATASET
This dataset is taken from : https://www.kaggle.com/datasets/vatsalmavani/spotify-dataset/data<br/>

## Acknowledgements
`Thanks to Spotify Web API that makes it easy for developers to fetch data and query Spotify’s catalog for songs`

## Installation

1. Clone the repository:

   ```
   git clone https://github.com/CodeWithCharan/Spotify-Recommender-Project-FastAPI.git
   ```

2. Create a `virtual environment` (optional): [Virtual Environment Set Up](https://github.com/CodeWithCharan/virtual-env-setup)

3. Download `Postman`: 
    - Go to https://www.postman.com/downloads/
    - Choose your desired platform among `Mac`, `Windows` or `Linux`.
    - Click `Download`.

4. Install the required dependencies:

    ```
    pip install -r requirements.txt
    ```

5. Start the `server` in the terminal:
    ```
    uvicorn main:app --reload  
    ```
6. Open `postman` and `Add request`

7. Uvicorn will be running on `localhost:8000`, so paste this URL

8. Select `POST`, `Body`, `raw`, `JSON` and then paste the `sample.json` data in the raw block



## Usage
Now, Enter your favorite `song name` and `year` to get personalized `recommendations`.