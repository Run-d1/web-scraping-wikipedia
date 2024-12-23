# Web Scraping Wikipedia Project: Largest US Companies by Revenue

This project is my first web-scraping program, completed as part of the 'Data Analyst Bootcamp' by Alex The Analyst on YouTube. The goal of this project is to scrape structured data from a Wikipedia page and make it accessible for analysis.

---

## About the Project

The program uses Python and the Beautiful Soup library to scrape data from the Wikipedia page:  
[Wikipedia: List of largest companies in the United States by revenue](https://en.wikipedia.org/wiki/List_of_largest_companies_in_the_United_States_by_revenue)

### Features
- Extracts company names, revenue, and other relevant details.
- Saves the scraped data into a structured format (CSV).

### Purpose
- Practice web-scraping techniques.
- Gain familiarity with handling HTML and parsing data.
- Demonstrate a basic understanding of Python programming and libraries.

---

## Getting Started

### Prerequisites
Ensure you have Python installed along with the required libraries:
- `beautifulsoup4`
- `requests`
- `pandas` (for data handling and export)

You can install them using pip:
```bash
pip install beautifulsoup4 requests pandas
```
---

## Outputs
- **Data file**: The scraped data is saved in `data/largest_companies_in_us_by_revenue.csv`.
- **Contents**: The file contains company names, revenue figures, and other relevant details in a structured format.

---

## Acknowledgments
- **Alex The Analyst**: For the 'Data Analyst Bootcamp' series on YouTube.
- Wikipedia contributors for maintaining the page being scraped.
