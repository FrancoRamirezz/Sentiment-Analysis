# Sentiment-Analysis
On March 10 the famous Silicon Bank crashed causing much reaction. Some were polarizing, and some were not so much. Understanding how individuals react to the news is very important in developing better insights into the individual mind
The dataset incorporates info from X(formerly Twitter) on the reaction to it.

<img width="753" alt="Screenshot 2023-11-13 at 5 43 16 PM" src="https://github.com/FrancoRamirezz/Sentiment-Analysis/assets/96508706/8fbdb3ea-62a8-4dda-a84e-702a4c6fbfb3">





<img width="394" alt="Screenshot 2023-11-13 at 6 04 13 PM" src="https://github.com/FrancoRamirezz/Sentiment-Analysis/assets/96508706/a81797f8-00ae-46d8-bda7-a939113f1e45">


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
