# Ecommerce Web Scraper

**Overview:**
This project is a web scraping tool built using Scrapy, a powerful web crawling framework in Python. The scraper is designed to extract product information from the Hugo Boss online store for men's clothing. It fetches data such as product names, available colors, product images, and care instructions.

**How it works:**

**1. Spider Implementation:** The scraper utilizes a Scrapy Spider named 'boss' to crawl the Hugo Boss website. It starts from the main men's clothing page and navigates through various categories to extract product details.

**2. Data Extraction:** Using CSS selectors, the scraper extracts relevant information such as product names, colors, image URLs, and care instructions from the product pages.

**3. Pagination Handling:** The scraper is capable of handling pagination to scrape multiple pages of product listings, ensuring comprehensive data collection.

**4. Output:** The extracted data is saved into a CSV file named 'HugobossProducts_Pagination.csv' for further analysis or processing.

**Dependencies:**: Python 3, Scrapy, Requests
