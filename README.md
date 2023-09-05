# CS_Crates
Counter-Strike Crate Valuation Analysis

## Objective:
Help a friend calculate the total value of Counter-Strike crates given to another person.

## Summary:
In this project, I assisted a friend in calculating the total value of gifted Counter-Strike crates. Using Python and BeautifulSoup, I web scraped the CSGO Database to fetch crate details like names, prices, and release dates. Additionally, I employed text parsing techniques to extract and quantify crate data from raw personal message logs. The extracted data was then merged, processed, and analyzed to determine the total value of the gifted crates. Tools used include Python, BeautifulSoup, Jupyter Notebook, and Excel.

## Data Sources:
CSGO Database: Web scraped to obtain crate names, release dates, and current prices.
Personal messages: Used to extract the list and count of gifted crates.

## Workflow:
1. Data Collection:
- Downloaded the CSGO Database website.
- Read the personal message history to retrieve the list of gifted crates.
2. Data Extraction and Processing:
- **Web Scraping:** Used the beautifulsoup4 library to parse the HTML content of the CSGO Database and extracted the required data (crate name, price, release date).
- **Text Processing:** Processed the personal messages to count the occurrence of each crate.
- **Extraction from Message Logs:** Employed text parsing techniques to sift through messages and identify patterns indicating crate names and quantities. Utilized Python's string manipulation and data structures like dictionaries for efficient counting.
3. Data Analysis:
- Merged the data from the two sources.
- Calculated the total value of the gifted crates by matching crate names and quantities with their respective prices.

## Tools and Technologies:
- Python: Primary programming language used for data extraction, processing, and analysis.
- BeautifulSoup: Used for web scraping.
- Jupyter Notebook: Used for iterative development and data analysis.
- Excel: Used for data storage and final calculations.

## Key Files:
- CSGO_Cases.html: Source HTML file from the CSGO Database.
- GiftedText.txt: Text file containing the list of gifted crates.
- CS_Crates.ipynb: Jupyter notebook detailing the entire data extraction, processing, and analysis workflow.
- Crates_Final.xlsx: Final Excel file containing crate data and total gifted crate value.
