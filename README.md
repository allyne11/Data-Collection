Mars Temperature Data Analysis
Project Overview
This project involves scraping, analyzing, and visualizing temperature and atmospheric pressure data from Mars, based on data collected by the Curiosity Rover.

Steps Performed
Web Scraping:

Used Splinter and BeautifulSoup to extract temperature data from a Mars facts webpage.
Parsed an HTML table and stored the data in a Pandas DataFrame.
Data Cleaning & Processing:

Checked and converted data types (e.g., terrestrial_date to datetime, numerical columns to float).
Handled missing values and ensured data was formatted correctly.
Data Analysis:

Identified the coldest and hottest months on Mars based on minimum temperature trends.
Determined the lowest and highest atmospheric pressure months by analyzing pressure fluctuations.
Estimated the length of a Martian year using temperature cycles.
Visualization:

Plotted average minimum temperature by month (to identify seasonal temperature variations).
Plotted average atmospheric pressure by month (to understand atmospheric changes).
Visualized daily minimum temperature over time to estimate the length of a Martian year.
Exporting Data:

Saved the processed dataset as a CSV file in a folder called temp_data.
Files Included
mars_temperature_data.csv: The final dataset containing processed Mars weather data.
scraper.py (if applicable): The Python script used for web scraping.
README.md: This file, summarizing the project.
Requirements
To run this analysis, ensure you have the following Python libraries installed:

bash
Copy
Edit
pip install pandas numpy matplotlib splinter beautifulsoup4
How to Use
Run the web scraping script to fetch updated data.
Use the analysis script to generate insights and plots.
The CSV file can be used for further study or machine learning models.
