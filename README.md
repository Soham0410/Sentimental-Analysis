# Sentimental-Analysis

Dataset Source : Kaggle
Dataset Name : sentiment 140
Number of data :  1.6 million tweets
API command : “kaggle datasets download -d kazanova/sentiment140”
Dataset URL: https://www.kaggle.com/datasets/kazanova/sentiment140


METHODS USED :
  For vectorization:
    Tf-idf vectorizer

  For Feature Extraction:
    PoterStemmer
    Tokenizer
    Padding
    Embedding

  For Classification:
    SVM(Support Vector Mechanism)
    CNN(Convolutional Neural Network)
    ANN(Artificial Neural Network)
    RNN(Recurrent Neural Network)
    DNN(Deep Neural Network)


Layout in which the whole process works :
  First the raw data set is taken, on which data preprocessing works which includes stemming, reming non alphabetic characters, converting to lower case, splitting  into individual words and reming stop words. Then TF-IDF (Term Frequency-Inverse Document Frequency) vectorization is employed, which entails cleaning and standardizing the text data(converting the text data into vector or numerical format suitable for model training). Then the data is split into training and testing sets.A logistic regression model is trained on the processed data. The accuracy of the model is evaluated on both training and testing datasets. Then the trained model is saved using pickle, which is loaded from saved files and predictions are made.
