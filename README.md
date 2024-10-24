# Spam Mail Detection Using Logistic Regression
This project aims to classify emails as spam or ham (non-spam) using machine learning with the help of a Logistic Regression model. It employs text preprocessing techniques and the TF-IDF vectorizer to extract features from email text and classify them based on patterns learned during training.

## Features
• Preprocess email text data.
• Convert the text data to numerical vectors using the TF-IDF Vectorizer.
• Train a Logistic Regression model to classify emails as spam or ham.
• Predict whether a given email is spam or not.
## Project Workflow
### Data Loading and Preprocessing:
• Load the email dataset (mail_data.csv).
• Handle missing values and map categorical labels to numerical values (spam=0, ham=1).

### Splitting the Data:
• Split the data into training (80%) and test (20%) sets.

#### Vectorizing the Text Data:
Use TfidfVectorizer to convert email text into numerical feature vectors.

#### Model Training:
Train a Logistic Regression model using the training data.

#### Evaluation:
Calculate accuracy on both the training and testing data.

#### Make Predictions:
Test the model with new email samples and classify them as spam or ham.

## Model Performance
Training Accuracy: 96.7%
Testing Accuracy: 96.6%
