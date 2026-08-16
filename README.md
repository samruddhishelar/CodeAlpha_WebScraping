📚 Web Scraping Project — 
Book Dataset Collector 

What this project does 

This project uses Python to automatically collect book data (title, price, and rating) from books.toscrape.com, a website built specifically for practicing web scraping. 
The script visits multiple pages, extracts the data, and saves it into a clean CSV dataset.

 Tools used 
 
 1.Python 3

 2. Requests — downloads webpage HTML 
  
 3. BeautifulSoup — parses and searches HTML
 
 4. Pandas — organizes and exports data as CSV
 
  How it works 
  
  1. The script sends a request to each page of the website. 
  2. It reads the HTML and finds every book listed on the page.
  3. It extracts the title, price, and star rating for each book.
  4. It repeats this for multiple pages (with a short delay between requests to avoid overloading the server). 5. All the collected data is saved into books_dataset.csv .

  How to run it 
  1. Install the required libraries: 
  pip install requests beautifulsoup4 pandas 
  2. Run the script: 
  python scraper.py 
  3. Open books_dataset.csv to see the collected data.

  Notes 
  
  1.This scraper only targets a website designed for scraping practice. 
  2.Always check a website's robots.txt file and terms of service before scraping real-world sites. 
  3.A short delay ( time.sleep ) is added between requests to be respectful of the website's server. 
  
  Author
  Shelar Samtuddhi