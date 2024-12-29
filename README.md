
# Twitter Hashtag Prediction

This repository contains three models developed to predict hashtags from tweets. The models are based on different neural network architectures:
1. **SimpleRNN**
2. **LSTM**
3. **Bi-LSTM**

## Project Structure
- **twitter_hashtag_prediction_RNN.ipynb**: Implements a model based on SimpleRNN.
- **LSTM_model.ipynb**: Implements a model based on LSTM.
- **twitter_hashtag_prediction_BiLSTM.ipynb**: Implements a model based on Bidirectional LSTM.

## Features
- Preprocessing of text data using `nltk`.
- Tokenization and padding for tweets.
- Train-test split to validate models.
- Model architectures designed with TensorFlow/Keras.

## Setup Instructions
1. Clone this repository.
2. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Open the desired Jupyter Notebook (`*.ipynb`) to train and evaluate the models.

## Dependencies
All dependencies are listed in the `requirements.txt` file. Notable libraries include:
- `tensorflow` for model creation.
- `nltk` for text preprocessing.
- `scikit-learn` for dataset splitting.

## Notes
- The datasets used for training are not included in this repository. Ensure you have the appropriate dataset in place.
- Download required `nltk` datasets using the following commands (included in the notebooks):
  ```python
  import nltk
  nltk.download('wordnet')
  nltk.download('punkt')
  ```

## Authors
This project was developed to demonstrate different neural network architectures for text prediction tasks.
