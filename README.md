In this notebook, we will scrape some data from a website.

We use requests to load page into our python script. Now, if the page we are trying to load is dynamic in nature and we request this page by requests library, it would send the JS code to be executed locally. Requests package does not execute this JS code and just gives it as the page source. For that we use selenium package.

references: https://www.geeksforgeeks.org/difference-between-static-and-dynamic-web-pages/
https://www.geeksforgeeks.org/scrape-content-from-dynamic-websites/

 
#### Required Libraries:
 
 > requests -  this module allows user to send HTTP requests using Python and to get the response text.
 
 > Selenium:  Selenium  (open-source) is a web testing library. It is used to automate browser activities.
 
 > bs4 - Beautiful Soup is a Python package for parsing HTML and XML documents. It creates parse trees that is helpful to extract the data easily.
 
 > pandas - to store the data in a structured format
 
 > Selenium webdriver - need to download selenium webdriver. The webdriver will run in real time and interact with the webpage to get the data.
> ### URL That We want to scrape

In this Jupyter Notebook, we will scrape some laptop details from flipkart website  'https://www.flipkart.com/'. The data includes Product Name, Specs_summary, Price, rating.


