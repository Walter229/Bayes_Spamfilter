# Bayes Spamfilter
The goal of this project was to build a spam filter for sms messages using a Naive Bayes algorithm. The algorithm uses conditional probability to evaluate whether a new message is more likely to be spam or not. The dataset was taken from the UCI Machine Learning repository and contains 5572 sms messages that are labeled as being spam or legitimate messages (ham).

## Performance:
The spam filter using a Naive Bayes algorithm performs quite good on the test set. It classifies over 95% of messages correctly and has a very high sensitivity of over 99%, thus detecting almost all spam messages. It does so, while still having a high specificity, correctly classifying over 95% of all non-spam messages.

## Limitations:
The spam filter is based on a rather small sample and would obviously benefit from a larger training dataset. The training data should ideally containg a large variety of different SMS sources to get a more representative picture of non-spam as well as spam messages. Naive Bayes spam filters are also susceptible to Bayesian poisoning - a technique where a spammer includes a large amount of legitimate text to improve the messages spam-score.
