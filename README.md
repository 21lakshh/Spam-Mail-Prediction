# **Spam Mail Prediction**  
Email spam is a pervasive issue that affects individuals and businesses alike. This project aims to classify emails as spam or legitimate using machine learning. By transforming email content into meaningful numerical representations, the model identifies patterns that distinguish spam from regular mail.

## **Features**  
### **Text Preprocessing**  

**Vectorization**: TF-IDF (Term Frequency-Inverse Document Frequency), Gives high importance to unique words that maybe useful, learns the vocabulary and inverse document frequencies for each word in the data. words that appear frequently are given less importance and converts all textual data into feature vectors (numeric data)   

 splits text into tokens and calculates frequency of each token but excludes stop_words list  

 min_df : terms that appear at least 1(more than 1) once are included.
 stop_words : Excludes Common english words
 lowercase : Converts all textual data to lowercase before converting it

used for converting a collection of text documents into a matrix of TF-IDF features. TF-IDF (Term Frequency-Inverse Document Frequency) is a technique used to convert textual data
into numerical form while emphasizing words that are more unique or important in each document.  

Data Splitted into **Train**, **Test** and **Validation**  

**Model Selection**: Logistic Regression to predict whether mail is spam or real.  
- Accuracy on Training Data: 96.87%  
- Accuracy on Testing Data: 96.59%
- Accuracy on Validation Data: 95.81%  

This model can be used in real-world applications to combat spam mails.  
