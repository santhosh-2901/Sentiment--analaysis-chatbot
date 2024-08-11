
This project implements a Sentiment Analysis Chatbot that classifies text input as positive or negative sentiment using machine learning. The chatbot features a graphical user interface (GUI) built with Python's `tkinter` library, making it easy for users to interact with the model in real-time.

## Project Overview

### Objective
The primary objective of this project is to develop a sentiment analysis model that can accurately classify text data (e.g., user reviews, comments) as having a positive or negative sentiment. This model is then integrated into a chatbot interface to provide real-time sentiment analysis feedback to the user.

### Key Features
- **Machine Learning Model**: Utilizes a Logistic Regression model trained on a dataset of product reviews to classify sentiment.
- **Graphical User Interface**: The chatbot is built with `tkinter`, providing a user-friendly interface.
- **Real-Time Analysis**: Users can input text and instantly receive sentiment feedback.
- **Modular Design**: The project is organized to easily swap in different models or datasets.

## Dataset
The sentiment analysis model was trained on a dataset of Amazon product reviews. The dataset includes text reviews labeled as either positive or negative based on their star rating.

- **Data Preprocessing**: The text data was cleaned by removing HTML tags, special characters, and stopwords, and then vectorized using `TfidfVectorizer`.
- **Model Training**: A Logistic Regression model was trained on the preprocessed data, and an alternative SVM model was also tested.

## Installation and Setup

### Prerequisites

- Python 3.x
- Required libraries: `scikit-learn`, `tkinter`, `pickle`
