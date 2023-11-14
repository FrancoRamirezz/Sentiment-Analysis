# Sentiment-Analysis Machine Learning
On March 10 the famous Silicon Bank crashed causing much reaction. Some were polarizing, and some were not so much. Understanding sentiment analysis allows machine learning to predict what emotion was displayed in the text. The emotions consisted ofpositive, negative, and neutral    
The dataset incorporates info from X(formerly Twitter)


<img width="761" alt="Screenshot 2023-11-13 at 6 38 40 PM" src="https://github.com/FrancoRamirezz/Sentiment-Analysis/assets/96508706/5972684d-086c-4ceb-be2c-610a6ee3ffc1">








```bash
import pandas as pd
import numpy as np
import matplotlib.pyplot as plt

import seaborn as sns
import nltk 
from nltk.corpus import stopwords 
nltk.download("all")
import seaborn as sns
from nltk.tokenize import RegexpTokenizer, word_tokenize
from nltk.corpus import stopwords 
import string
from nltk import WordPunctTokenizer
nltk.download('punkt')
nltk.download('stopwords')
stopwords.words("english")
