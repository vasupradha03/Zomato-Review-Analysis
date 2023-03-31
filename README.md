# Zomato-Review-Analysis
A simple project to demonstrate how textual data can be used to extract valuable insights that can be used to improve the quality of service offered by restaurants.
This project analyzes customer reviews of restaurants on the food delivery platform Zomato using Natural Language Processing (NLP) techniques. 

## Dataset
The dataset taken from Kaggle consists of around 1000 customer reviews of restaurants from Zomato and whether the review is positive or not.

## Tools and Libraries
   - Python 3
   - Pandas
   - NumPy
   - Re
   - Scikit-learn
   - NLTK (Natural Language Toolkit)
   
## Data Cleaning and Preprocessing
	The textual data is preprocessed to clean and prepare for analysis. This involves:
		 - removing characters other than alphabets
		 - removing stop words
		 - converting the text to lowercase
		 - stemming or lemmatizing the words

## Analysis
	The preprocessed and vectorized data is then used to train various machine learning models to predict ratings. A testing size of 0.20 is used over the dataset. The model is trained with a Gaussian Naive Bayes. 
