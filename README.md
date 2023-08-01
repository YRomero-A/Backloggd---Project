# Videogames Based on Popular Opinion
## Data Analysis Project
### Overview

This data analysis project aims to explore and visualize gaming data from the website Backloggd. The project includes the following steps:

* Data Scraping: Data is scraped from the [Backloggd](https://www.backloggd.com/) website to obtain information about various games, including their ratings, total plays, current players, wishlist from their users, among other data. The library which was scraped comes from the following link [Backloggd - Games](https://www.backloggd.com/games/lib/popular/) library.

* Data Cleaning: The scraped data is processed and cleaned using Python to ensure it is in a suitable format for analysis.

* Database Management: Certain datasets are downloaded using Python and stored in SQL databases to facilitate efficient querying and data manipulation.

* Dashboard Creation: Two interactive dashboards are developed to provide insights into the gaming data. The first dashboard displays top games by rating, total plays, current players, and games in the users wishlists. The second dashboard presents information about the top producing teams, the most common gaming consoles, the minimum, maximum, and average ratings of games per console, and the top 10 genres by average rating.

## Objective
The primary objectives of this data analysis project are as follows:

+ Identify and visualize the top games based on various metrics such as ratings, total plays, current players, and popularity in users' wishlists.

+ Analyze the top producing teams associated with the games and investigate their average ratings.

+ Determine the most common gaming consoles used to play these games.

+ Calculate the minimum, maximum, and average ratings of games for each gaming console.

+ Rank the top 10 genres based on their average ratings.

## Data Source - [Backloggd](https://www.backloggd.com/)
Backloggd is a popular website where gamers can track, rate, and manage their gaming experiences. It contains extensive data on various games, including user ratings, playtime, platform information, and genres. The first 300 pages in their library of games, with the filter popularity, were used at the time of the data scraping (July, 2023).

## Tools and Technologies Used
The following tools and technologies are employed in this end-to-end data analysis project:

* **Python:** Python programming language is used for web scraping, data cleaning, and data processing tasks.

* **Beautiful Soup and Requests:** These Python libraries are utilized for web scraping and extracting data from the Backloggd website.

* **Pandas:** The Pandas library is employed for data manipulation and cleaning.

* **SQL Server Management Studio:** SQL Server Management Studio is used as the database management system to store and query certain datasets.

* **SQL: Structured Query Language (SQL)** is used to perform database queries.

* **Tableau:** Tableau is a leading data visualization tool used for data analysis and business intelligence. 

## Repository Structure

The repository contains the following files and folders:

* WebScraping Project - Backloggd.com.ipynb: This Python script contains the code to scrape data from the Backloggd website.

* Backloggd - Data Cleaning and EDA Scrypt.ipynb: This Python script includes the code to clean and process the scraped data, as well as the code to download the datasets.

* README.md: This document provides an overview of the project, its objectives, data sources and tools used.

## Dashboard

* **Link:** [Games Analysis - July 2023 - Backloggd.com](https://public.tableau.com/views/GamesAnalysis-July2023-Backloggd_com/Games-Dashboard?:language=en-US&publish=yes&:display_count=n&:origin=viz_share_link)

## Instructions to Run the Project
Clone this repository to your local machine.

* Install the required libraries and dependencies listed in requirements.txt using the command: pip install -r requirements.txt.

* Run the data scraping script WebScraping Project - Backloggd.com.ipynb to extract data from the Backloggd website.

* Execute the data cleaning script Backloggd - Data Cleaning and EDA Scrypt.ipynb to clean, process and download the scraped data datasets.

* Import the csv.files into SQL Server Management Studio, the name of the teams, consoles, and genres were changed after the sql upload to make them more understandable and easy to query.

* Run the SQL-Queries-Backloggd.sql script file to see the different queries done in the project.

* Follow the dashboard link to see the dashboard created, keep in mind the data is static, and your results due to a different timeframe will vary with the resulst found here.
* Interact with the dashboards to explore the gaming data and gain insights based on the provided objectives.

## Conclusion
This data analysis project provides valuable insights into gaming data from Backloggd. The interactive dashboards present visualizations that enable users to explore top games, team ratings, popular gaming consoles, and top genres based on average ratings. These visualizations facilitate a deeper understanding of gaming trends and preferences, which can be utilized for decision-making and strategy in the gaming industry.
