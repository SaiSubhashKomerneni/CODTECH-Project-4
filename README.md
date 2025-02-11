# CODTECH-Project-4
Name: SAI SUBHASH KOMERNENI
Company: CODTECH IT SOLUTIONS
ID: CT12EBG
Domain: Data Analytics
Duration: 17 December 2024 to 17 February 2025
Mentor: N.SANTOSH KUMAR

Overview of the Project

Project: Twitter Sentimental Analysis

Objective: The purpose of this project is to perform a sentiment analysis on textual data using Natural Language Processing(NLP) Techniques.

This script analyzes Twitter sentiment by classifying tweets into positive (1) or negative (0) using multiple machine learning models. The best-performing model can then be used for real-time sentiment analysis on social media data. 

Key steps:
1. Data Loading and Exploration                                                                                                            
Reads training and testing datasets (train_tweet.csv, test_tweets.csv) using pandas.                                                
Checks for missing values and explores sample tweets.                                                           
Visualizes tweet length distribution and sentiment labels.                                                                  
                                                                                       
2. Text Preprocessing                                                                     
Tokenizes and cleans the tweets (removes special characters, converts to lowercase).                                 
Removes stopwords and applies stemming using NLTK.                                           
Extracts hashtags and analyzes their frequency.                                       
Generates word clouds to visualize common words.                                                     
                                                                        
4. Feature Engineering                                                                   
Converts tweets into numerical format using:                                  
Bag of Words (BoW) Model via CountVectorizer                                           
Word2Vec embeddings using gensim                                        
Standardizes features using StandardScaler.                                       
                                                      
6. Model Training and Evaluation                                               
Splits the dataset into training and validation sets.                                            
Trains multiple machine learning models:                                      
Random Forest                                     
Logistic Regression                              
Decision Tree                                    
Support Vector Machine (SVM)                                   
XGBoost                                                
Evaluates models using:                                           
Accuracy                                                 
F1-score                                                
Confusion Matrix                                       
                                                             
8. Predictions                                                         
Each model predicts sentiments (positive/negative) on the validation set.                                  
Compares different model performances.                                          
