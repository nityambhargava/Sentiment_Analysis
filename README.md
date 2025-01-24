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
```

Key Libraries
1. TensorFlow: For building and training the LSTM model.
2. Pandas: For data manipulation and preprocessing.
3. Scikit-learn: For splitting the dataset.
4. Kaggle API: For downloading the dataset.

How It Works
1. Data Collection: Downloads the IMDB dataset from Kaggle.
2. Data Preprocessing:
Tokenizes and converts text reviews into padded sequences.
Converts sentiments to binary labels (positive = 1, negative = 0).
3. Model Building:
Embedding Layer: Converts words to dense vectors.
LSTM Layer: Captures temporal patterns in the text data.
Dense Layer: Outputs the probability of positive sentiment.
4. Training:
Trains the LSTM model with a validation split of 20%.
5. Evaluation:
Evaluates the model's performance on test data.
6. Prediction:
Accepts custom text reviews for sentiment prediction.

Example Predictions
1. Positive Review:
Input: "This movie was fantastic, with amazing acting!"
Output: "Positive"

2. Negative Review:
Input: "The storyline was boring and predictable."
Output: "Negative"

Contributing
Contributions are welcome! Feel free to submit issues or pull requests to improve the project.

Acknowledgments
Kaggle: For the IMDB dataset.
TensorFlow & Scikit-learn for the tools and libraries.

Let me know if you'd like any additional sections or modifications!

