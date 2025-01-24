# Sentiment Analysis Using LSTM

This project is a Sentiment Analysis system for movie reviews, built using a Long Short-Term Memory (LSTM) neural network. It predicts whether a review expresses a **positive** or **negative** sentiment based on the text input.

---

## Features
- Downloads and preprocesses the **IMDB Movie Reviews Dataset** from Kaggle.
- Uses an LSTM model for text sequence analysis.
- Provides a prediction function for custom movie reviews.

---

## Dataset
The dataset used is the **IMDB Dataset of 50K Movie Reviews**, available on [Kaggle](https://www.kaggle.com/datasets/lakshmi25npathi/imdb-dataset-of-50k-movie-reviews).  
To access the dataset:
1. Set up your Kaggle API credentials in a `kaggle.json` file.
2. Ensure the file contains the following:
    ```json
    {
      "username": "your_kaggle_username",
      "key": "your_kaggle_api_key"
    }
    ```
3. Place the `kaggle.json` file in the same directory as the script.

---

## Requirements
Install the required dependencies using:
```bash
pip install -r requirements.txt
