# project---google-image-scrapping
This project is a Python-based web application using Flask that allows users to fetch and download images from Google Images. It utilizes BeautifulSoup for parsing HTML and requests for fetching web pages. Users can enter a search query, and the application retrieves images related to that query from Google, saving them locally.

Features:
Search Functionality: Allows users to enter a query and fetch related images from Google Images.
Image Scraping: Scrapes image URLs from the Google search results page and downloads them to a specified directory.
Error Handling: Logs errors to a file (scrapper.log) using Python's logging module.
User Interface: Simple web interface built with Flask and HTML to interact with the scraping functionality.

Technologies Used:
Flask: Python web framework for building the application.
BeautifulSoup: Python library for parsing HTML and XML documents.
requests: HTTP library for making requests and handling responses.
logging: Python module for logging errors and messages.
HTML/CSS: Front-end for the web interface.

Project Structure:
app.py: Flask application setup and routes.
templates/index.html: HTML template for the user interface.
scrapper.log: Log file for recording errors during scraping.
requirements.txt: List of Python dependencies.


Usage:
Enter a search query in the provided form.
Click on the "Search" button to initiate the image scraping process.
Images related to the query will be fetched from Google and stored in the images/ directory.
Errors encountered during scraping will be logged in scrapper.log.
