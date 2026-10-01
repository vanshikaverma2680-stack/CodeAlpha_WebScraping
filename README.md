# CodeAlpha Internship — Task 1: Web Scraping

## Project Overview

This project demonstrates how to collect structured information from a website using Python. The project scrapes book information from Books to Scrape, a practice website designed for web scraping.

## Objectives

* Retrieve webpage content using HTTP requests.
* Extract book information using BeautifulSoup.
* Organize collected data using Pandas.
* Clean price values and calculate basic statistics.
* Visualize book prices and rating distributions.
* Export the processed data to CSV and Excel formats.

## Technologies Used

* Python
* Requests
* BeautifulSoup
* Pandas
* Matplotlib
* Seaborn
* Google Colab

## Data Collected

The dataset contains the following fields:

* **Title:** Name of the book.
* **Price:** Book price in pounds sterling.
* **Rating:** Book rating category.
* **Availability:** Availability information displayed on the website.

## Methodology

1. Send HTTP requests to the practice bookstore website.
2. Parse HTML content using BeautifulSoup.
3. Extract titles, prices, ratings and availability.
4. Convert the extracted records into a Pandas DataFrame.
5. Clean price values and calculate descriptive statistics.
6. Create charts to explore price and rating distributions.
7. Export the cleaned dataset to CSV and Excel files.

## Project Files

* `CodeAlpha_Task1_WebScraping.ipynb` — Project notebook containing code, outputs and explanations.
* `books_dataset_cleaned.csv` — Cleaned dataset in CSV format.
* `books_dataset_cleaned.xlsx` — Cleaned dataset in Excel format.

## How to Run

1. Open the notebook in Google Colab.
2. Run the cells in order.
3. Ensure the required Python libraries are available.
4. Review the extracted data, statistics and visualizations.
5. Run the export cells to save the cleaned datasets.

## Results

The project produces a structured dataset of book information, summary statistics and visualizations of price and rating distributions.

The number of records and specific findings should be reported according to the actual notebook output.

## Limitations

* The collected data represents only the pages selected for scraping.
* Website structure and availability may change.
* The extracted rating categories are the labels displayed on the website.
* The results should not be treated as a complete representation of every bookstore.

## Conclusion

This project provided practical experience in web scraping, HTML parsing, data cleaning, exploratory analysis and data export using Python.

## Data Source

Books to Scrape — https://books.toscrape.com/

The website is used for practicing web scraping and learning data extraction techniques.
