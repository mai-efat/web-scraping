# web-scraping
This project demonstrates how to scrape the Facebook logo from the official Facebook website using Python. It utilizes the requests and BeautifulSoup libraries to fetch and parse the HTML content.
Prerequisites

Python 3.x: 
Ensure Python is installed on your system. You can check your version by running:

python3 --version

pip: 
The package manager for Python should be installed. Check by running:

pip --version
```
Libraries:
This project requires the following Python libraries:
requests
beautifulsoup4
Usage
Create a Python Script: Create a new Python file named web.py.
Usage
Create a Python Script: Create a new Python file named scrape_facebook_logo.py.
Run the Script: Execute the script using Python:
python3 web.py
```
Code Explanation
1-Import Libraries: The script imports requests for making HTTP requests and BeautifulSoup from bs4 for parsing HTML.
2-Fetch the Webpage: The script sends a GET request to the Facebook homepage.
3-Parse the HTML: It uses BeautifulSoup to parse the returned HTML.
4-Locate the Logo: The script looks for the <img> tag with the class that matches the Facebook logo.
5-Download and Save: If found, it downloads the image and saves it locally.
```
