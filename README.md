# End_to_End_6Week_RAG_dev
A great initiative by professor Harsh Singhal in Ramaiah Institute of Technology to bring students together and learn end to end RAG development which is the foundation of building on accuracy and reliability in LLMS through sophisticated NLP techniques. This repository is a complete journey showcasing my learnings and experiences at this workshop.

*WEEK 1 - Text Vectorization & Sentiment Analysis using TF-IDF and Logistic Regression* 

Codes are provided as ipynb files within lib -> Week1

The wordvectorizebasic.ipynb contains word vectorization for a number of sentences in the corpus declared within the code. Its a basic idea as to how words are converted into vectors via TF-IDF vectorizer. The idf scores are got and printed in the form of arrays. 

The sentiment_analysis.ipynb was trained using the Tweet Sentiment Extraction competition dataset which was held in Kaggle. I have tried Logistic Regression algorithm on the given dataset but it showed an accuracy of 0.6894 on the validation dataset. I also tried using LazyPredict to evaluate which algorithm works best but it had a dependency error with the version of ski-kit learn. 
