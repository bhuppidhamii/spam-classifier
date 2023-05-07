# Spam Classifier

This repository contains a simple implementation of a spam classifier using the Naive Bayes algorithm. The spam classifier is trained on a dataset of emails labeled as either spam or non-spam, and it can predict whether a given email is spam or not.

## Usage

To use this spam classifier, follow these steps:

1. Clone this repository to your local machine:

```
git clone https://github.com/bhupendradhami/spam-classifier.git
```

2. Install the required packages:

```
pip install -r requirements.txt
```

3. Run the `train.py` script to train the spam classifier:

```
python train.py
```

4. Run the `predict.py` script to predict whether a given email is spam or not:

```
python predict.py <email_file>
```

where `<email_file>` is the path to the file containing the email to be classified.

## Dataset

The dataset used to train the spam classifier is the [SpamAssassin Public Corpus](http://spamassassin.apache.org/old/publiccorpus/). This dataset contains a collection of spam and non-spam emails, which have been pre-processed and labeled.

## Algorithm

The spam classifier is implemented using the Naive Bayes algorithm, which is a probabilistic algorithm that is commonly used for text classification tasks. The Naive Bayes algorithm works by calculating the probability of a document belonging to a particular class, given its features (i.e., words). The algorithm assumes that the features are independent of each other, which is not always true in practice, but it still works reasonably well for many text classification tasks.

## Contact

If you have any questions or feedback, please feel free to contact me at bhupendradhami@gmail.com.
