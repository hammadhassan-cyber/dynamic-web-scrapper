# Professional Dynamic Web Scraper

A Python-based GUI application for scraping Jobs, Products, and News from real websites with auto-refresh, search/filter, and export capabilities.

## Features
- **Scrape** Jobs (Hacker News), Products (Books to Scrape), and News (Hacker News)
- **Auto-Refresh** with user-defined intervals
- **Search & Filter** scraped data in real-time
- **Export** to JSON, CSV, and Excel
- **Demo Mode** works offline without internet or ChromeDriver
- **Selenium Support** for dynamic JavaScript-heavy sites
- **Double-click links** to open in browser

## Requirements
```bash
pip install requests beautifulsoup4 openpyxl lxml
```
## Run
```
python main.py
```

Usage
- Select a category (Jobs / Products / News)
- Click Scrape Now to fetch live data, or Load Demo Data to test offline
- Check Auto-Refresh and set an interval for automatic updates
- Use Search to filter results
- Save data via JSON, CSV, or Excel buttons
