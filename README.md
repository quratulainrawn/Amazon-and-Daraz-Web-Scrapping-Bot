# Amazon-and-Daraz-Web-Scrapping-Bot
🛒 Amazon and Daraz Web Scraping Bot
Overview
This project is a web scraping bot designed to extract product data from Amazon and Daraz efficiently for personal product research and price comparison.

The bot retrieves:
✅ Product Titles 
✅ Prices 
✅ Ratings
✅ Product Links

and saves them into a structured CSV/Excel file for easy analysis.

✨ Features Scrape multiple pages automatically.

Extract clean, structured data for Amazon and Daraz.

User-friendly and easily modifiable for other marketplaces.

Useful for:

Product research

Price tracking

Trend analysis

Amazon VA tasks

⚙️ Technologies Used Python 3.x

BeautifulSoup (HTML parsing)

Requests (HTTP requests)

Pandas (Data cleaning and export)

(Optional) Selenium for dynamic page handling if required

🚀 How It Works Specify your search keyword or category URL for Amazon/Daraz.

The bot sends requests to the site and retrieves HTML content.

Parses the HTML to extract:

Product name

Price

Rating

Product URL

Cleans and saves the data in CSV/Excel.

Supports scraping multiple pages with minimal modifications.

📂 Project Structure Copy Edit amazon_daraz_scraper/ ├── amazon_scraper.py ├── daraz_scraper.py ├── requirements.txt └── README.md 🖥️ Setup Instructions 1️⃣ Clone this repository:

bash Copy Edit git clone https://github.com/yourusername/amazon-daraz-web-scraper.git cd amazon-daraz-web-scraper 2️⃣ Install dependencies:

bash Copy Edit pip install -r requirements.txt 3️⃣ Run the scraper:

bash Copy Edit python amazon_scraper.py

or
python daraz_scraper.py 4️⃣ Check your output.csv file for scraped data.
