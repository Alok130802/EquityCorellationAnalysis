# EquityCorellationAnalysis
  This project is about how we can do network analysis concepts can be used in correlation network  of Equity market .


# Dataset Discription
  The dataset used in this project is from kaggle . The link is https://www.kaggle.com/abhishekyana/nse-listed-1384-companies-data
# Tools used 
  1.pandas
  
  2.NetworkX

# Data Preprocessing 

  In data set we are given stock prices of 1384 companies from year 2003 to 2017.
  
  
  1.We seprated all the stock which as highly traded from the stock which are less traded to be precise 100000
  
  
  2.After selecting the highly traded stock we calculated the every day return of each stock.
  
  
  3.After calculating the return , for each month we created a corellation matrix.
  
  
  4.Now we select the stock which have corellation greater than thrashold specified (0.7). 
  
  
  5.Now we create a graph with equity as nodes and edged as corellation value.


# Analysis


  1.We used python NetworkX package do find the degee centrality and beetweeness centrality measure of stock.
  
  
  2.For a given node show all the stock which are corellated with that stock in that month.
  

# Refrence
  http://snap.stanford.edu/class/cs224w-2015/projects_2015/Network_Analysis_of_the_Stock_Market.pdf
