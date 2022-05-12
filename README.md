# US-Healthcare-Stocks-MiniProject
Analyzing the top US Healthcare stocks, alongside XLV and a simple average healthcare index.

Dataset: web.DataReader - Yahoo Finance Historical Data

The objective of this project was to analyze the US Healthcare stock industry over 2020-2021 and 2012-2021. Python was used to read, clean, and store web data.

Interesting Notes:

- WBA really struggled to perform compared to its peers. It failed to make new highs in 2020 and 2021, and also has been lagging the industry over 2012-2021.
- WBA also had a close in October 2020 that was lower than its March 2020 low. Ever since the RiteAid merger announcement in October 2015, WBA has been in a steady downtrend.
- On the topic of a close lower than the March 2020 low, CAH had a -14.26% drop after posting earnings in August of 2021 (worst day in 2020-2021).
- Recently, MCK, UNH, and ABC all outperform both XLV and a simple average index. Zooming out, however, only UNH has outperformed XLV (both UNH and ANTM outperform the simle average index).
- MCK has had a wonderful recent performance, improving its Avg Annual Return by 26.32% with only a 8.4% increase in Standard Deviation: 82% improvement in Coefficient Variation.
- CVS also has had a notable recent performance, improving its Avg Annual Return by 11.41% with only an 8.4% increase in Standard Deviation: 54.8% improvement in Coefficient Variation. 
- UNH really stepped up in 2018, overtaking the top spot of returns since 2012 and hasn't given it back since.
- CAH and WBA shareholders should reasonably be upset with the stock performance over the last 10 years. 

# Install
pip install numpy | conda install numpy

pip install pandas | conda install pandas

pip install matplotlib | conda install matplotlib

pip install seaborn | conda install seaborn

pip install plotly

pip install chart-studio

pip install cufflinks

# Import
import pandas_datareader.data as web

import pandas as pd

import numpy as np

import datetime as dt

import seaborn as sns

import matplotlib.pyplot as plt

import plotly

import cufflinks as cf

from plotly.offline import download_plotlyjs, init_notebook_mode,plot,iplot

init_notebook_mode(connected = True)

import chart_studio.plotly as py

cf.go_offline()

%matplotlib inline
