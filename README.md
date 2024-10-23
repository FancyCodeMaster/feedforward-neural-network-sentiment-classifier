## Feedforward Neural Network for Sentiment Classification

# TO-DO
1. Preprocess the twitter sentiment dataset\
    a. Remove unnecessary columns\
    b. Text Cleaning\
        \ti. converting to lowercase\
        \tii. removing urls\
        \tiii. removing non-word and whitespace characters\
        \tiv. removing digits\
    c. Tokenization\
    d. Stopword Removal\
    e. Stemming/Lemmatization\
    f. Data Splitting : train test split\
2. Neural Network Modeling\
    a. Vectorization with tfidf or embedding model\
    b. Tensor conversion of the splitted dataset\
    c. Build Model in PyTorch\
3. Evaluation and Visulisation\
    a. Plot loss vs epochs\
    b. Accuracy - Precison, Recall and F1 score\
    c. Roc curve and more\