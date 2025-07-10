# Spam-Classifier

A concise Naive Bayes classifier to detect unsolicited or spam messages.

## Overview
- **Purpose**: Quickly classify messages as spam or ham using probabilistic methods.  
- **Data**: Utilizes the SMS Spam Collection (5,574 labeled text messages).  
- **Algorithm**: Naive Bayes with bag-of-words (CountVectorizer) for feature extraction.  

## How It Works
1. **Data Preparation**  
   - Load dataset, split into training and test sets.  
   - Clean and tokenize text.
2. **Feature Extraction**  
   - Convert words and common word pairs (unigrams/bigrams) into numeric features.  
3. **Model Training**  
   - Train Naive Bayes using training set.  
   - Evaluate performance on test data (accuracy, precision, recall, etc.).  

## Usage
1. Clone the repo:  
   ```bash
   git clone https://github.com/Exido-Rio/Spam-Classifier.git
   cd Spam-Classifier

## Files 
- Tester.ipynb - Used to load and test the model
- Trainer.ipynb - Used to load dataset , clean and extract feature then train the model 
