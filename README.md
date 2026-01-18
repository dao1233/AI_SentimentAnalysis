# AI_SentimentAnalysis
AI Semester Project: Implementation of sentiment analysis on film trailer comments

SVM MODEL
1. Create conda environment using environment.yml
2. Run the first cell in the notebook trainNotebook.ipynb to install and import all nesscessary packages
3. Run cells step by step, cell by cell to process data and train model
4. the last two cells are used to store the trained model (model\svm_sentiment_model.pkl) and load the trained model for analyzing sentiments of new inputs respectively
5. In the last cell, you can change the inputs to predict the sentiments of each input by using the trained model.
Ex:
reviews.append("this seem to be ok, not so intersting")

LEXICON ANALYSIS
1. Create conda environment using environment.yml
2. Run the first cell in the notebook lexiconAnalysis.ipynb to install and import all nesscessary packages
3. Run cells step by step, cell by cell to process data and analyze sentiment based on lexicon
4. In the last cell, you can change the inputs to predict the sentiments of each input by using the function sentiment_vader_lexicon().
Ex:
reviews.append("this seem to be ok, not so intersting")

