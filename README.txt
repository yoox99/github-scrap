# GitHub Repository Scraper

## Description
The GitHub Repository Scraper is a Python script that retrieves repository information from the GitHub API based on specified criteria. It fetches the top repositories created on each day within a given date range and stores the data in a CSV file.

## Features
- Fetches top repositories based on stars and creation date
- Retrieves repository details including name, URL, description, stars, creation date, language, forks, watchers, open issues, and owner
- Handles pagination and rate limiting of the GitHub API
- Outputs the extracted data to a CSV file for further analysis

## Installation
1. Clone the repository to your local machine.
2. Install the required dependencies by running the command: `pip install -r requirements.txt`.

## Usage
1. Open the terminal or command prompt and navigate to the project directory.
2. Run the script using the command: `python main.py`.
3. Enter the start date, end date, and number of repositories per day when prompted.
4. The script will retrieve the repository data from the GitHub API and save it to a CSV file named `repositoriesfinal.csv` in the project directory.

## Configuration
No additional configuration is required. The script uses the GitHub API base URL and requires a GitHub access token for higher rate limits. The token can be provided in the `access_token` variable in the code.

## Examples
- To scrape the top 100 repositories created between 2022-01-01 and 2022-01-10, enter the following inputs:
  - Start date: 2022-01-01
  - End date: 2022-01-10
  - Number of repositories per day: 100

## Issues and Bug Reports
If you encounter any issues or have suggestions for improvements, please submit them in the [Issues](https://github.com/yoox99/github-scraper/issues) section of this repository. We appreciate your feedback!
