The main aim of this project was to create a crypto scraper bot script 
This bot scrapes one crypto site and get the prices of coins depending on their headers and display them using csv format
In this project libraries imported include
Requests, os, beautifulsoup, csv, 
The request sends a request to the crypto website 
The beautifulsoup parses the raw html, and the os creates and joins the file name to the folder_path
Also the bs4 finds the exact html content including the rows and columns we want to extract 
We used the csv to write the extracted data into the csv file. 
