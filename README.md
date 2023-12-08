# Group11_Project_Intro_to_Python

DAB111-004: Group Project


Students:

* Onyeukwu Chukwuemeka Ifeoluwa (0827889)    
* Stanley Esuagum (0826364)
* Uchenna Uwagbale (0850859)

## Project Description

In this project, we explored by collecting non-fiction book data from 
'http://books.toscrape.com/' website via webscraping with three columns 
were documented in this project with the "title" ,"price" and 
"availabilty". This Python project script performs web scraping to 
extract information about non-fiction books from the website. The data is 
then loaded into a Pandas DataFrame with some data cleaning and analysis 
performed. The script includes functionality to save the data to a CSV 
file and provides options for data visualization. This project is 
involves web scraping, data processing, and website interaction project 
that collects data and stores it to the database using SQLite3, and 
serves the data through a Flask-based website. The processing and 
cleaning of the collected data is done before being stored. Users can 
access and interact with the data on the website.


## Requirements

To complete this project, the following are the requirements:

1. Data Collection: Data collection should be legally from 
'http://books.toscrape.com/' through web scraping. Collect data 
through web scraping of the non-fiction category of the bookstoscrape website. The data 
collection process included about 100 observation of information and have the 
following columns:

   - Title
   - Price
   - Availabilty


2. Data Processing: Process the collected data by cleaning 
it for clarity. This process involves the extraction of numerical values, 
formatted the columns and normalized the text after the data has been 
collected. Also add an additional column of Price(CAD), to represent prices in canadian dollars 
These data processing steps aim to  manipulates and transform 
the raw web data into a structured format suitable for analysis and 
visualization. Adjustments can be made to the script based on specific 
data requirements or analysis objectives.


3. Database: The usage of the sqlite3 package was considered to complete 
the creation and insertion of the data. The collected and processed data  
was stored in SQLite database named 'books.db'. 


4. Website Interaction: The Flask and SQLAlchemy software was used 
for the creation of this website. The basic format of the website should 
include the following pages:

    - About page with a basic information about what users can do.
    -View all list of nonfictional books available
    - Search for a list of books and view the result in the website
    
   

5. Repository Structure: The project is organized with the following structure:

   - Data collection group.ipynb :Jupyter Notebook containing web scraping code
   - Data_processing_group.ipynb:Jupyter Notebook for data cleaning and processing.
   - database.ipynb: Jupyter Notebook for SQLite database creation and data insertion.
   - website.ipynb: Python script for the Flask web application.
   - templates/about.html`: Directory containing HTML templates for the website.
   - templates/index.html`: Directory containing HTML templates for the website.
   - Readme.md: Documentation for the project.
   - requirements.txt: File listing project dependencies.
   

6. Installation

a. Store this GitHub repository to your system.
b. Install Python on your system.
c. Run the Jupyter Notebooks in the following order:

    - Data collection group.ipynb
    - Data_processing_group.ipynb
    - database.ipynb
    - website.ipynb

7.. Access the Flask website at http://localhost:5000/ in your web browser.



































