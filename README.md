# web-scaping-challenge
# Mars Data Analysis Project

This repository contains Jupyter notebooks that scrape and analyze Mars-related data, along with a folder containing the resulting data in CSV and JSON formats. 

## Files Description

- `part_1_mars_news.ipynb`: This Jupyter notebook scrapes the latest news about Mars from various sources and processes the information into a structured format.

- `part_2_mars_weather.ipynb`: This notebook focuses on scraping and analyzing the weather data of Mars, providing insights into the patterns and changes in Martian weather.

- `/scraped_data`: This folder contains the output of the scraping scripts:
  - `mars_weather_data.csv`: A CSV file with the weather data of Mars, generated by `part_2_mars_weather.ipynb`.
  - `mars_news_data.json`: A JSON file with the latest Mars news data, generated by `part_1_mars_news.ipynb`.

## How to Use

To utilize these notebooks, follow the instructions below:

1. Ensure you have an environment capable of running Jupyter notebooks (e.g., Anaconda, Jupyter Lab, or VSCode).
2. Clone this repository to your local machine.
3. Navigate to the repository directory and start Jupyter notebooks to open the `.ipynb` files.
4. Execute the cells in `part_1_mars_news.ipynb` to scrape the latest Mars news.
5. Execute the cells in `part_2_mars_weather.ipynb` to scrape and analyze Mars weather data.

## Prerequisites

- An environment for running Jupyter notebooks (Anaconda recommended)
- Python 3.x
- Required Python packages:
  - pandas
  - numpy
  - requests
  - BeautifulSoup
  - matplotlib
