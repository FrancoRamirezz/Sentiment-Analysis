# Sentiment-Analysis
On March 10 the famous Silicon Bank crashed causing much reaction. Some were polarizing, and some were not so much. Understanding how individuals react to the news is very important in developing better insights into the individual mind
The dataset incorporates info from X(formerly Twitter) on the reaction to it. It is either positive, negative, or neutral







<img width="755" alt="Screenshot 2023-11-13 at 6 33 35 PM" src="https://github.com/FrancoRamirezz/Sentiment-Analysis/assets/96508706/8dd4d966-d706-464b-90a1-f9f0cce5823f">


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
