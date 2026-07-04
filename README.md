# Indian-Manufacturer-Lead-Scraper-Project
This project is a Python-based web scraping tool that collects information about 100 Indian manufacturers who can support Indian founders, startups, and business clients. The main purpose of this project is to make supplier research easier. 
How It Works
The code first tries to search the web for manufacturer websites.
Then it checks whether the website looks like a real manufacturer by looking for manufacturing-related words.
After that, it extracts useful information from the website text, such as certifications, production capacity, packaging support, logistics support, and lead time.
If live search does not return enough results, the project uses a curated list of Indian manufacturers and enriches it by visiting their official websites.
Finally, the collected data is saved into:
CSV file
Excel file

Technologies Used: 
Python
Pandas
Requests
BeautifulSoup
OpenPyXL
Jupyter Notebook

Output:
The final output is a spreadsheet containing 100 Indian manufacturers with useful business information.
This file can be used by founders, students, researchers, or business teams to explore potential manufacturing partners in India.
