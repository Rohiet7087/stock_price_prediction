# Project Name: 
Analyzing Historical Stock Prices and Forecasting

# Project Description:
  This project aims to analyze the historical stock prices of a given stock symbol and perform a linear regression analysis to forecast future prices.
The project featch  the Alpha Vantage API to retrieve the necessary stock data  various data analysis & visualization techniques using Python libraries such as requests, 
pandas, matplotlib, random,& scipy

# How to use and Run the Project
   We have to install and import some dependencies I will tell further, Firstly I will share that how to use this application.
    This application work for analyzing the historical stock prices.
    
 # Steps for handling applicaton
 1.Open a stock_symbol pdf I mentioned over there about the comapny name and there symbol.
 2. Go to the STOCK_PRICE_PREDICT.ipynb file in that file put your symbol in Ticket_symbol variable.
 3. For looking data of tranding days go to the trading_days variable and change the days accordingly your need.
 4. In this forecasted_days variable we can change the days for how many days you want to do forecasted.


# Dependencies
pip install requests
import pandas
import matplotlib
import scipy
import random
pip install reportlab
from reportlab.lib.pagesizes import letter
from reportlab.pdfgen import canvas
from reportlab.platypus import SimpleDocTemplate, Paragraph, Spacer
from reportlab.lib.styles import getSampleStyleSheet


# Configuration 
API Key: You can replace api_key

# Thank You...
