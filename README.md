# NLP-Textprocessing
import numpy as np # linear algebra import pandas as pd # data processing, CSV file I/O (e.g. pd.read_csv) import string # special operations on strings import spacy # language models  from matplotlib.pyplot import imread from matplotlib import pyplot as plt from wordcloud import WordCloud %matplotlib inlineb # remove both the leading and the trailing characters  # removes empty strings, because they are considered in Python as false # Joining the list into one string/text #Punctuation  #with arguments (x, y, z) where 'x' and 'y' # must be equal-length strings and characters in 'x' # are replaced by characters in 'y'. 'z' # is a string (string.punctuation here) #stopwords  #tokenization ##Remove stopwords import nltk nltk.download('stopwords') #normalize data #stemming #feature extraction  #generate wordcloud
