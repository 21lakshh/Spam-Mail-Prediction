# Spam Mail Prediction

This project categorizes emails into **Spam** and **Non-Spam** (Ham) using natural language processing (NLP) techniques and machine learning. The model uses **Logistic Regression** for classification. Email spam is a pervasive issue that affects individuals and businesses alike. This project aims to classify emails as spam or legitimate using machine learning. By transforming email content into meaningful numerical representations, the model identifies patterns that distinguish spam from regular mail.

## Project Features

- **Text Data Preprocessing**: 
  - Text is split into tokens, and the frequency of each token is calculated  
  - Common English words are removed using the `stop_words` parameter.
  - All text data is converted to lowercase before processing.
  
- **Feature Extraction**: 
  - The project utilizes **TF-IDF** (Term Frequency-Inverse Document Frequency) to convert text data into numerical feature vectors. This method helps emphasize important and unique terms in the emails.
  - **min_df** parameter ensures terms that appear more than once are included, removing very rare terms.

- **Logistic Regression**: 
  - The model uses logistic regression for binary classification, predicting whether an email is spam or non-spam.

- **Performance**:
  - **Train Accuracy**: 96.87%
  - **Test Accuracy**: 96.59%
  - **Validation Accuracy**: 95.81%

## Visualization

- **Spam vs Non-Spam Distribution**: The project visualizes the distribution of spam and non-spam emails in a **pie chart** to give a quick overview of the dataset.

## Libraries and Technologies Used

- **NLP Techniques**: Tokenization, Stopword Removal, TF-IDF Vectorizer
- **Machine Learning**: Logistic Regression
- **Visualization**: Matplotlib (for pie chart)
- **Other Libraries**: Pandas, Scikit-learn, Numpy

