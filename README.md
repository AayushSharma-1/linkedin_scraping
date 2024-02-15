# LinkedIn Job Scraping and Exploratory Data Analysis

## Overview

This project aims to scrape job listings from LinkedIn and perform Exploratory Data Analysis (EDA) on the collected data. The scraping process extracted 714 job listings along with their details, such as job title, company name, location, job description, and more. The subsequent EDA delves into analyzing various aspects of the job data to gain insights and extract meaningful information.

## Project Structure

- **Jupyter Filst**: Contains the Python script used to scrape job listings from LinkedIn.
- **Raw Data**: Folder containing the scraped data in CSV format.
- **Result**: Folder containing csv results.
- **README.md**: This file, providing an overview of the project.

## Scraping Process

The scraping script utilized web scraping techniques, primarily employing the `BeautifulSoup` library in Python, to extract job listings from LinkedIn. It navigates through job search pages, retrieves job details, and stores them in a structured format. The script handles pagination to ensure comprehensive data collection.

## Exploratory Data Analysis

The EDA phase involves analyzing the scraped data to derive insights and understand patterns. Some of the key analyses performed include:

- **Job Distribution by Location**: Visualizing the distribution of job listings across different locations.
- **Top Companies with Job Openings**: Identifying the companies with the highest number of job listings.
- **Most Common Job Titles**: Determining the most frequently occurring job titles in the dataset.
- **Word Cloud of Job Descriptions**: Creating a word cloud to visualize common terms and phrases used in job descriptions.
- **Salary Insights**: Analyzing salary ranges and trends, if available in the scraped data.
- **Experience and Qualifications**: Exploring the requirements and qualifications mentioned in job descriptions.

## Conclusion

Through this project, we gained valuable insights into the job market trends within the LinkedIn platform. The combination of web scraping and exploratory data analysis provided a comprehensive understanding of job listings, companies, and requirements across various industries and locations. This project serves as a foundation for further analysis and can be extended for more in-depth research or targeted job search efforts.

Feel free to explore the provided data and notebooks for a deeper understanding of the findings and methodologies employed in this project. If you have any questions or suggestions, please don't hesitate to reach out.

Happy exploring! 🚀
