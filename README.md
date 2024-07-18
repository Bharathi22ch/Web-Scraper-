PROJECT WEB SCRAPER
Importing Libraries : First, we import the necessary libraries for web scraping, data manipulation, and visualization.
Web Scrapping       : We define the URL of the website we want to scrape and make an HTTP request to get the content of the 
                      page.
Extracting Book Data : We locate the HTML elements that contain the book data (title, price, and availability) and extract 
                       the information.
Converting Data to DataFrame : We convert the extracted data into a pandas DataFrame for easier manipulation and analysis.
Data Cleaning        : We clean the data by removing non-numeric characters from the price and converting it to float.We 
                       also standardize the availability status.
Data Analysis        : We calculate the average price of the books and count the number of books in stock and out of stock.
Data Visualization   : We create visualizations to represent the availability and price distribution of the books.

The libraries that we have used are pandas,Matplotlib,Beautifulsoap,
BeautifulSoup (from bs4) : BeautifulSoup is a library that makes it easy to scrape information from web pages. It sits atop 
                           an HTML or XML parser, providing Pythonic idioms for iterating, searching, and modifying the 
                           parse tree.
Pandas                   : pandas is a powerful, flexible, and easy-to-use open-source data analysis and data manipulation 
                           library for Python. It provides data structures like DataFrames that make data analysis and 
                           manipulation easy.
Matplotlib               : matplotlib is a comprehensive library for creating static, animated, and interactive 
                           visualizations in Python.
These libraries together enable efficient web scraping, data manipulation, analysis, and visualization in Python.
