# AutoScrape-Harvester (Amazon SA Review Scraper)

AutoScrape-Harvester is an automated web scraping tool built with Python and Selenium. It is designed to navigate product pages on Amazon Saudi Arabia (`amazon.sa`) and automatically harvest user reviews and comments.

## 🚀 Features

* **Automated Review Extraction:** Automatically locates and clicks the "See all reviews" (اطلع على جميع المراجعات) button to gather customer feedback.
* **Pagination Handling:** Navigates through multiple pages of reviews to extract large datasets sequentially.
* **Anti-Bot Bypass:** Utilizes custom Chrome options (e.g., disabling `AutomationControlled` and overriding the User-Agent) to avoid detection and blocking by target websites.
* **Data Parsing:** Extracts raw text data from specific XPATH elements on the page, preparing it for natural language processing or data mining tasks.

## 📋 Prerequisites

Before running this script, ensure you have the following installed:

* **Python 3.x**
* **Google Chrome browser**
* **ChromeDriver:** Must match your current version of Google Chrome.

Install the required Python libraries using pip:

```bash
pip install selenium pandas
```

## Disclaimer
This tool is provided for educational and academic research purposes (e.g., Data Mining and Natural Language Processing). Web scraping should be done ethically and in accordance with the target website's Terms of Service.
