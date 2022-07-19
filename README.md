# Challenge-7
# ETF Analyzer

## Overview
This program [etf_analyzer.ipynb] contains code with examples of accessing financial data using SQL with the purpose of creating a web application displaying different evaluations for the ETF data. Through the use of optimized SQL Queries and Conditionals, different sets of data are evaluated and analyzed to show daily returns of an individual stock as well as ETF stocks as a whole (for the given data in etf.db included in folder). Visuals are produced from corresponding dataframes and are then opened on web browser using Voila.

## Technologies Used
The libraries and dependencies used in this program are listed in the first cell of the program which are: Numpy, Pandas, hvplot.pandas, SQLAlchemy. To display notebook on webpage, Voila will need to be downloaded to local machine. 

## Program Layout
This program is divided into 4 parts which are as follows:

**Part 1** - Analyzing a Specific Asset from given ETF database
            Using SQL queries, data from PYPL stock data is accessed and converted into a pandas dataframe. With this data, visuals are created by implementing .hvplot() to 
            display daily returns and cumulative returns for this single stock.
            
**Part 2** - Optimize data access with SQL queries
            Continue analysis of PYPL data, this time with more specific parameters accessed by implementing SQL Queries that specify time and specific amounts for closing
            prices and create a Pandas DataFrame showing this data. Building on this data, daily returns are then rearranged and displayed at the top 10 return values in a 
            Pandas DataFrame.
            
**Part 3** - Analyzing complete ETF Portfolio
            Using SQL query, all 4 tables for the assets within etf.db are accessed and compiled into one Pandas DataFrame which is then used to evaluate the portfolio focusing 
            on daily returns and annualezed returns for the etf assets as a whole.

**Part 4** - Displaying Notebook as Web Application
            Through use of Voila webapp generator, completed notebook is displayed in browser. To run voila and the notebook, follow instructions under 'Run Web APP'.

## To Run Web APP
-Download program packages, and files under 'starter_code' folder
-Access file through terminal, with Voila installed in machine, run command: voila etf_analyzer.ipynb (*voila + name_of_file* will open notebook on web application)

-When successfully run, browser should show the following:



## Author
Juan Bohorquez![Screenshot (1)](https://user-images.githubusercontent.com/101238359/179846435-bf854258-a465-4194-9184-d1a6c303b6e2.png)
![Screenshot (2)](https://user-images.githubusercontent.com/101238359/179846453-98925da2-c20e-421d-85eb-3db14ddc9bc5.png)
![Screenshot (3)](https://user-images.githubusercontent.com/101238359/179846467-e2dd3762-3e3a-4907-9395-8600ed343bbe.png)
