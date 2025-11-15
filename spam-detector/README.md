# Predicting Spam Emails Using Machine Learning

This project aims to accurately predict whether an email is spam or not using a machine learning model. Leveraging a pre-classified dataset, our model achieves an impressive 99% accuracy in distinguishing spam emails from legitimate ones.

## Table of Contents

- [Introduction](#introduction)
- [Dataset](#dataset)
- [Methodology](#methodology)
  - [Data Preprocessing](#data-preprocessing)
  - [Model Training](#model-training)
  - [Model Evaluation](#model-evaluation)
  - [Prediction Function](#prediction-function)
- [Results](#results)
- [Conclusion](#conclusion)
- [Future Work](#future-work)
- [Dependencies](#dependencies)
- [Usage](#usage)
- [Acknowledgements](#acknowledgements)

## Introduction

The goal of this project is to build a machine learning model that can accurately predict whether a given email is spam or not. Using a dataset of emails, we train a Multinomial Naive Bayes model, achieving a high level of accuracy.

## Dataset

The dataset used in this project consists of emails, each labeled as spam or not spam. The data is loaded from a CSV file (`emails.csv`), with each row representing an email and columns including the email text and its classification (spam or not spam).

## Methodology

### Data Preprocessing

- **Vectorization**: The `CountVectorizer` from `sklearn.feature_extraction.text` is used to convert the email text into a matrix of token counts.
- **Splitting Data**: The data is split into training and testing sets using `train_test_split` from `sklearn.model_selection`, with 80% of the data used for training and 20% for testing.

### Model Training

- **Model**: We use the Multinomial Naive Bayes (`MultinomialNB`) classifier from `sklearn.naive_bayes` to train our model.
- **Training**: The model is trained on the training data (`X_train`, `y_train`).

### Model Evaluation

- **Accuracy**: The model is evaluated on the test set (`X_test`, `y_test`) using the `accuracy_score` from `sklearn.metrics`.
- The model achieved an accuracy of 99%.

### Prediction Function

A function `predictMessage` is created to allow users to input their own email text and receive a prediction on whether it is spam or not.

## Results

The trained model demonstrated an impressive accuracy of 99%, effectively predicting whether an email is spam based on the email text. The accuracy was confirmed using the testing dataset.

## Conclusion

The Multinomial Naive Bayes model proved to be highly effective in predicting spam emails with an accuracy of 99%. This project demonstrates the feasibility and efficiency of using machine learning techniques for spam detection in emails.

## Future Work

To further improve and expand this project, consider the following:
1. Experimenting with different machine learning models.
2. Incorporating additional features from the email metadata.
3. Using larger and more diverse datasets.
4. Evaluating the model's performance on different email providers.

## Dependencies

- Python 3.x
- pandas
- scikit-learn

Install the dependencies using pip:

```bash
pip install pandas scikit-learn
```

## Usage

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/rdcar/spam-detector.git
   cd spam-predictor
   ```

2. **Run the Script**:
   ```bash
   python email_spam_detection.py
   ```

3. **Predict an Email**:
   Enter your email text when prompted to receive a prediction on whether it is spam or not.

## Acknowledgements

We would like to thank the developers of the Python libraries used in this project for their invaluable tools and resources.


