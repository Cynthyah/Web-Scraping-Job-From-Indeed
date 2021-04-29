# Web-Scraping-Job-From-Indeed
Web scraping job from Indeed using Beautifulsoup and checking top words and specific skills according to the description of the job.

Source: https://ie.indeed.com

# Libraries
import requests\
import pandas as pd\
import re\
import string\
import matplotlib.pyplot as plt

from bs4 import BeautifulSoup\
from textblob import TextBlob\
from nltk.corpus import stopwords\
from operator import itemgetter\
from datetime import datetime

