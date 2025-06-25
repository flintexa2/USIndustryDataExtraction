USIndustryDataExtraction
A web scraping project using Python, BeautifulSoup, and pandas to extract data on the largest companies in the United States by revenue from Wikipedia.
Project Summary:
    I recently completed a Python project focused on web scraping using the BeautifulSoup library in Google Colab.
The goal was to extract a list of the largest industry in the United States by revenue from a Wikipedia page.
Using BeautifulSoup, I successfully parsed the HTML content of the page, located the relevant table, and extracted the company data including rank, name, industry, revenue, employees, and headquarters.
Finally, I organized this extracted data into a pandas DataFrame and saved it as a CSV file, making the information easily accessible for further analysis.

Coding Process:
     The first step was to fetch the web page content using the `requests` library. Once I had the HTML, I used BeautifulSoup to parse it and identify the relevant table containing the company data. This involved inspecting the page's HTML structure to find the correct table tag and its attributes.

A key part of the process was extracting the table headers to use as column names for my data. I then iterated through each row of the table, extracting the data from each cell. A minor challenge I encountered was handling the header row separately from the data rows to ensure the data was correctly aligned with the headers.

Finally, I used the pandas library to structure the extracted data into a clean and organized DataFrame. This made it easy to view and work with the data. As a last step, I saved the DataFrame to a CSV file for future use and sharing.

Final Result:
   Avalible in a cathe.analytics/py1.0.csv

How to Run the Code:
    Open the .ipynb file in Google Colab.
Files:
   web_scrp1.ipynb`: The Colab notebook containing the web scraping code.
cathe.analytics/py1.0.csv`: The extracted data in CSV format.

