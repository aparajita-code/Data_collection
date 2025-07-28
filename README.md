# Data_collection

***🚀 Mars Data Scraping and Weather Analysis***
***🧭 Project Overview***
This repository contains two web scraping and data analysis projects focused on Mars-related data. The goal is to practice extracting HTML content, structuring it using Python, and visually interpreting the results using Pandas and Matplotlib. The projects use Splinter and Beautiful Soup for automation and scraping.

***📝 Deliverables***
***📄 Deliverable 1: Mars News Scraper***
Automated browsing using Splinter to visit Mars News

Extracts latest article titles and preview texts using Beautiful Soup

Stores output as a list of dictionaries with title and preview keys

Output printed in notebook and optionally exported to JSON format

***📊 Deliverable 2: Mars Weather Data Analysis***
Scrapes HTML weather table from Mars Facts Site

Parses and structures data using Beautiful Soup and Pandas

Analyzes and visualizes:

Average temperature by Martian month

Atmospheric pressure trends across months

Number of Martian sols and terrestrial days in a Martian year

Exports cleaned DataFrame to CSV

***🛠 Technologies Used***
Python

Jupyter Notebook

Splinter

Beautiful Soup

Pandas

Matplotlib

***🗂 Repository Structure***
mars-data-challenge/
├── part_1_mars_news.ipynb
├── part_2_mars_weather.ipynb
├── resources/
│   ├── mars_weather.csv
│   └── mars_news.json (optional)
├── README.md
***📌 Getting Started***
Clone the repository:

bash
git clone https://github.com/your-username/mars-data-challenge.git
Open the Jupyter notebooks to explore each deliverable step-by-step.

View the generated CSV/JSON outputs in the resources folder.

***📈 Insights Gained***
Reinforced HTML structure analysis and XPath targeting

Gained experience with dynamic content scraping

Practiced transforming messy data into visual insights