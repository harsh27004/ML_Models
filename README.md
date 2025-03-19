# ML_Models
# The Naive Bayes model detects spam and phishing emails from the given dataset by using TF-IDF(Term Frequency - Inverse Document Frequency) vectorization.
# Where TF measures how often a word appears in a document.
#    TF= number of times word appears in the document/Total number of words in the document
# And IDF reduces the importance of common words (i.e. the, is, and, etc.)
#    IDF= log(Total number of documents/Number of documents containing words)
#    TF-IDF= TF X IDF (high TF-IDF score means a word is important in a document but rare in others)

# Model training is done by using the Multinominal Naive Bayes algorithm, it is a specific type of algorithm that is well-suited for text classification tasks. It works by calculating the probability of a message belonging to a certain category (spam or ham) based on the frequency of words in the message.
