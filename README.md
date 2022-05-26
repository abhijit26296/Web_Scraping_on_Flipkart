# Web_Scraping_on_Flipkart

What is Web Scraping?

It is the automated procedure of extracting the large amount of data from websites. The data available on the websites which is unstructured can be converted to structured data using Web Scrapping.  There are different ways to scrape websites such as Online Services, APIs or writing your own code.

Why is Web Scraping Used?

Why does someone have to collect large data from websites?
To know about this, let’s look at the applications of web scraping:

Price Comparison:
To collect data from online shopping websites and use it to compare the prices of products.

Email address gathering:

To use email as a medium for marketing, use web scraping to collect email ID and then send bulk emails.

Social Media Scraping:

To collect data from Social Media websites such as Twitter to find out what’s trending.

Research and Development:

To collect a large set of data (Statistics, General Information, Temperature, etc.) from websites, which are analyzed and used to carry out Surveys or for R&D.

Job listings:

Details regarding job openings, interviews are collected from different websites and then listed in one place so that it is easily accessible to the user.

How Do You Scrape Data From A Website?
When you run the code for web scraping, a request is sent to the URL that you have mentioned. As a response to the request, the server sends the data and allows you to read the HTML or XML page. The code then, parses the HTML or XML page, finds the data and extracts it.

To extract data using web scraping with python, you need to follow these basic steps:

1) Find the URL that you want to scrape.

2) Inspecting the Page.

3) Find the data you want to extract.

4) Write the code.

5) Run the code and extract the data.

6) Store the data in the required format.

Now let us see how to extract data from the Flipkart website using Python.

Libraries used for Web Scraping:
As we know, Python is has various applications and there are different libraries for different purposes. In our further demonstration, we will be using the following libraries:

1) Selenium:
Selenium is a web testing library. It is used to automate browser activities.

2) BeautifulSoup:
Beautiful Soup is a Python package for parsing HTML and XML documents. It creates parse trees that is helpful to extract the data easily.

3) Pandas:
Pandas is a library used for data manipulation and analysis. It is used to extract the data and store it in the desired format.
