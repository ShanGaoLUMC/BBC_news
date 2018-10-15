# BBC News documents Classification
This script is trying to build a predictive model to automatically label the category for each news article. The raw text files are download from http://mlg.ucd.ie/datasets/bbc.html. 

### The main procedure has the following steps:
* Create a dataframe storing all news data.
* Clean and preprocess the raw texts (e.g. remove non-words, word stemming). Create training and test datasets.
* Convert each news article to a feature vector using bag-of-word approach.
* Build a classification pipeline which includes vectorizer, featureSelection, and classifier.
* Train the pipeline with training sets, turn the model parameters.
* Evaluate the trained model. Apply the optimized model to the test datasets for category prediction. Calculate classifcaition accuracy, consufion matrix.
* Take some interesting news from BBC website, preprocess them, and input them to optimized model to see how does the model works.
