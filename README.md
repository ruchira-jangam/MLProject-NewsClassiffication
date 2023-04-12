# News Category Identification 

This project aims to identify the type of news based on headlines and short descriptions using machine learning techniques. The project uses the News Category Dataset, which contains over 200,000 news articles from 2012 to 2018, categorized into 41 different categories.

## Dependencies
To run this project, you need to have Python 3.x installed on your system. You also need to install the following dependencies:

pandas
numpy
scikit-learn
nltk

To install the dependencies, you can use the following command:

``` pip install pandas numpy scikit-learn nltk ```

``` nltk.download('stopwords') ```

``` nltk.download('wordnet') ```

``` nltk.download('omw-1.4') ```

## Data Preprocessing
The dataset contains a lot of noise and irrelevant information, which can affect the performance of the machine learning model. Therefore, we use NLP techniques such as lemmatization and stemming to clean the text data. We also use the TfidfVectorizer from scikit-learn to convert the text data into numerical vectors that can be fed into the machine learning model.

## Machine Learning Model
We use two classification algorithms, logistic regression and naive Bayes, to train the machine learning model. We use the epoch hyperparameter to tune the performance of the model. We split the dataset into training and testing sets and evaluate the performance of the model using accuracy and F1 score.

## Conclusion
This project demonstrates how machine learning can be used to identify the type of news based on headlines and short descriptions. We use NLP techniques for data cleaning and TfidfVectorizer to convert the text data into numerical vectors. We also use logistic regression and naive Bayes classification algorithms to train the machine learning model. The project can be used as a starting point for building more sophisticated news classification systems.



