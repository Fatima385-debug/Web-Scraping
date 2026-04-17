# Web-Scraping Project Name: MarketWatch Mandi Price Scraper

### 1. Project Overview
- **Target Website:** http://www.amis.pk/daily%20market%20changes.aspx
- **Data Fields Extracted:** City Name, Crop Name, Today's Price, Yesterday's Price, Change in Price
- **Tools Used:** Python, requests, BeautifulSoup, pandas

### 2. Setup Instructions
1. Clone this repo 
2. Install dependencies using `pip install -r requirements.txt`
3. Run script using `python scraper.py`

### 3. Challenges & Solutions
One technical challenge was extracting tabular data correctly from HTML rows and columns. This was solved by using `find_all('tr')` and looping through table cells.
