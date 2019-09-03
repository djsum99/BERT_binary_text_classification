
# File Descriptions
BERT preparing data and training - Preprocesses the data so that it is suitable to run through the BERT model. Also, splits dataset into training and testing data and uses training data to fine-tune a downloaded BERT model (bert-base-cased).

BERT testing - Uses testing data to assess how accurate the fine-tuned model. Prints out the number of TPs, TNs, FPs, and FNs.

Logistic Regression - Uses a vectorizer to convert text to vectors, and then runs logistic regression on the dataset. Results were compared to those that came from the BERT codes.

Cosine Similarity Testing - Uses data to train a logistic regression model. Then testing data is run through model, and false positives are extracted. Then cosine similarity is used to determine the most similar texts to each of the false positives. This is useful, as measures can more easily be taken to adjust the training data to prevent false positives.

# Binary Text Classification with BERT
Accompanying code for the Medium article found at https://medium.com/@chaturangarajapakshe/a-simple-guide-on-using-bert-for-text-classification-bbf041ac8d04.

The code in this repository is based on the code from ThilinaRajapakse's repository called BERT_binary_text_classification. It was modified a bit in order to suit my own needs.
