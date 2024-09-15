# Naver-Blog-Scraper-with-Selenium

# Description
Naver Blog Scraper is a Python tool that allows users to search for blog posts on Naver, retrieve blog links, and scrape the content from each post. The project uses Naver's OpenAPI to fetch blog data based on user input and Selenium to extract the content of each blog post. The scraped data, including blog titles, links, and content, is saved in a CSV file for further analysis.

# Features
* Search Naver Blogs: Search for Naver blog posts using Naver's OpenAPI.
* Scrape Blog Content: Extract the content of each blog post using Selenium.
* Save Data: Save the blog titles, links, and content in a CSV file.
* Supports Dynamic Pages: Handles modern web pages that load content dynamically using JavaScript.

# Requirements
* Python 3.x
* Required libraries (install with pip):
  * selenium
  * webdriver_manager
  * chromedriver-autoinstaller
  * pandas
  * re
  * urllib

# Setup
Naver API Credentials
You need to obtain your Client ID and Client Secret from the Naver Developers platform:

Create an application in Naver Developer Center.
Obtain your Client ID and Client Secret.

# Output
The output will include:

1. Titles: The titles of the blog posts.
2. Links: The blog post URLs.
3. Content: The main content of each blog post.

The scraped data is saved in a CSV file with columns:
* Title: Blog post title.
* Link: Blog post link.
* Content: Blog post content.
