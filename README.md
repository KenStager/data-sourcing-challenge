# data-sourcing-challenge
Module 6 - Ken Stager

# Movie Data Analysis Project

## Overview
This project involves retrieving and analyzing movie reviews from the New York Times API and additional movie details from The Movie Database (TMDB) API. The goal is to merge these data sources to create a comprehensive dataset for further analysis or building a movie recommendation system.

## Features
- Fetches movie reviews containing "love" in the headline from the NYT API.
- Retrieves corresponding movie details from TMDB API using the titles extracted from the NYT reviews.
- Merges the data from both APIs for a combined dataset.
- Cleans and preprocesses the data for consistency and ease of analysis.

## Dependencies
- Python 3
- Libraries: `requests`, `pandas`, `json`, `time`, `dotenv`

## Setup and Installation
1. Clone the repository to your local machine.
2. Ensure Python 3 and the required libraries are installed.
3. You need to have API keys for both the New York Times and TMDB. Store these keys in a `.env` file as `NYT_API_KEY` and `TMDB_API_KEY`.

## How to Run
1. Load the project in a Python environment.
2. Execute the Jupyter Notebook cells in sequence.
3. The final output will be a CSV file containing the merged data from NYT and TMDB.

## Data Retrieval Process
- **NYT API**: The script fetches movie reviews with specific filters and stores the results.
- **TMDB API**: Using the titles obtained from NYT data, the script fetches detailed movie information from TMDB.
- **Data Cleaning**: The script cleans and formats the data, particularly fields containing lists and extracts meaningful information from JSON structures.

## Merging and Exporting Data
- The data from both APIs is merged based on movie titles.
- The script removes duplicates and unnecessary columns for a clean dataset.
- The final dataset is exported as a CSV file, `my_data.csv`, for further use.

## Contributing
Feel free to fork the project and submit pull requests for any enhancements.

## License
[Your chosen license]
