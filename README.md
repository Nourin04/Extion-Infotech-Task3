

# Sentiment Analysis Tool: IMDB Movie Reviews

## Objective
The goal of this project is to create a sentiment analysis tool that can classify text data, specifically movie reviews, as **positive** or **negative**. The project follows these steps:
1. Use Python and Natural Language Processing (NLP) libraries.
2. Collect and preprocess text data (IMDB dataset).
3. Develop a sentiment analysis model.
4. Apply the model to analyze the sentiment of text samples.

## Highlights of the Project
- **Dataset**:
  - Installed Kaggle's API and imported the **IMDB Dataset of 50K Movie Reviews**.
  - Loaded and extracted the dataset for further processing.

- **Preprocessing**:
  - Tokenized the text data and converted the words to sequences.
  - Used padding to ensure uniform input length for the model.
  - Split the dataset into training and test sets using `train_test_split`.

- **Model Development**:
  - Built a **Long Short-Term Memory (LSTM)** model using TensorFlow and Keras to classify reviews as positive or negative.
  - The LSTM network was chosen due to its capability to handle sequential data effectively.

- **Model Training and Evaluation**:
  - Trained the LSTM model on the preprocessed text data.
  - Evaluated the model’s performance on the test set, achieving good accuracy in predicting the sentiment.

- **Prediction System**:
  - Developed a predictive system that analyzes user input (movie review text) and classifies it as either positive or negative sentiment.

## Key Libraries and Tools Used
- **Kaggle API**: For importing the IMDB dataset.
- **TensorFlow & Keras**: For building and training the LSTM model.
- **Scikit-learn**: For data splitting and evaluation metrics.
- **Pandas**: For data manipulation and exploration.
- **NLTK/SpaCy**: For potential NLP preprocessing tasks (if applicable).
- **Tokenization and Padding**: For preparing the text data for model input.
