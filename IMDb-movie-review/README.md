# Sentiment Analysis Project - IMDb Movie Reviews

This project aims to build a sentiment analysis model to classify movie reviews as positive or negative using the IMDb movie review dataset. The model uses machine learning techniques and provides visualizations to understand its performance.

## Project Overview

- **Objective**: Sentiment Analysis for Movie Reviews (Binary Classification)
- **Dataset**: IMDb movie review dataset from the `nltk` library
- **Programming Language**: Python
- **Dependencies**: `nltk`, `scikit-learn`, `matplotlib`, `seaborn`

## Project Structure

- `sentiment_analysis.ipynb`: Jupyter Notebook containing the complete project code.
- `README.md`: This file, providing an overview of the project and instructions.
- `imdb_reviews.py`: Python script version of the project code (without explanations).

## Instructions

1. **Installation**: Ensure you have Python installed. Install the required dependencies using the following command:


pip install nltk scikit-learn matplotlib seaborn

2. **Dataset**: The IMDb movie review dataset will be downloaded automatically when you run the code for the first time. It contains positive and negative movie reviews.

3. **Run the Code**: Open and run the sentiment_analysis.ipynb Jupyter Notebook to execute the project step-by-step.

4. **Visualization**: After running the code, visualizations such as the ROC curve will be displayed in the Notebook.

5. **User Input and Prediction**: The project includes a function predict_sentiment(review) that takes a new movie review as input and predicts its sentiment (positive or negative).

6. **Model Evaluation**: The SVM model's accuracy, classification report, and ROC AUC score will be displayed in the Notebook.

7. **Summary**: The Notebook concludes with a summary of the project, including key findings and potential improvements.