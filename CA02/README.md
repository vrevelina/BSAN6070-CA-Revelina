# CA02.ipynb

CA02.ipynb is a jupyter notebook program for spam email detection using Naive Bayes Classification Algorithm.
The program has two (2) functions described under **Usage** section. It identifies the 3000 most common words from the emails in the train set. These most common words are the attributes of the emails which allow our model to classify which email are spam and non-spam.

## Installations

User should have Python3 and Jupyter Notebook installed into their system.

User should also have the following packages installed:
* os
* numpy
* collections
* sklearn.naive_bayes
* sklearn.metrics

## Dataset

The dataset was retrieved from the following link: https://github.com/ArinB/MSBA-CA01-Spam-Mail-Naibe-Bayes 

Dataset is located inside the zip folder [Data.zip], which contains two (2) folders: [train-mails] and [test-mails].\
The dataset used in this program are a set of text files (.txt). Spam email file names start with "spmsg".

[train-mails] consists of 702 emails equally divided into spam and non-spam category.\
[test-mails] consists of 260 emails.

Each text file represents an email in the following format:

* First line: subject line
* Second line: left blank
* Third line: email body

## Instructions

User can open CA02.ipynb through jupyter notebook.
Please be sure that the train and test directory/path are correctly specified in *TRAIN_DIR* and *TEST_DIR* respectively.
Then open the file and run each cell separately.

## Usage

CA02.ipynb has been provided with detailed comments to help the user understand the codes.

FUNCTIONS

* MakeCounterList(root_dir): Extracts 3000 most repeated words
  * Summary:\
    Creates a list of every word in every email, takes only alphabetical words with more than 1 character and returns 3000 words which occured the most.
  * Parameter:\
    root_dir (str): path to a folder which contains the emails
  * Returns:\
    word_count_list (list): a list of tuples containing the 3000 most common words with its corresponding number of occurences
* extract_features(mail_dir): Marks most common word occurence and spam emails
  * Summary:\
    Checks the number of occurences of most common words in each email and marks it in the features_matrix
    Checks if the name of the text file containing the email indicates that it is a spam email
  * Parameter:\
    mail_dir (str): path to a folder containing all emails
  * Returns:\
    features_matrix (np.array): a matrix containing the number of occurences of each most common word in each email
    email_labels (np.array): a matrix indicating which emails are spam (1) and not spam (0)

## Contributors
Version 1: Code created for CA02.ipynb in a (.py) file, by Professor Brahma\
Version 2: Changed python code format into a jupyter notebook, few variable changes and comments added, by Vania Revelina
