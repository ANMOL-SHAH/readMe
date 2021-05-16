# Complete political twitter analysis

It is a political analysis consisting of various modules:
  - Thematic text analysis
  - Versatility in political party
  - Sentiment analysis of tweets along with charts/interactive plots.


## Installation

Use the package manager [pip](https://pip.pypa.io/en/stable/) to install required libraries.

```bash
pip install numpy # To perform linear algebra functions 
pip install pandas # data processing, CSV file I/O e.g. pd.read_csv 
pip install matplotlib.pyplot # create plot  graphs
pip install seaborn # data visualization purposes
pip install spacy # advanced Natural Language Processing in Python
pip install networkx # network analysis library
pip install datetime # for using date and time
pip install os # 
pip install nltk # stopwords, tokenizer, stemmer
pip install textblob #spell correction, lemmatization
pip install plotly.express
pip install scikit
```

## Usage

```python
import numpy as np 
import pandas as pd 
import matplotlib.pyplot as plt
import seaborn as sns
import spacy
import networkx as nx      
import datetime
import os
import nltk
import plotly.express as px
import scikit as sklearn

df = pd.read_csv("../Datasets/uspoliticians.csv") #pd is used to read csv file from dataset and create data frame
nx.draw(strong_G, node_size=20, edge_color='gray',node_color='red') # networkx for drawing network
plt.plot([1, 2, 3, 4], [1, 4, 9, 16]) # usage of plt for ploting graph
```

## Datasets

> Download all datasets present in dataset folder and change directory path for the read csv file functions
 


## Authors
  + Nishant Patel
  + Apurva Mhatre
  + Anmol Nailesh Shah
  + Sampada Talwar
  + Smitha ithal Sadashiv


