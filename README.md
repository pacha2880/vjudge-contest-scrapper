# Vjudge Contest Scrapper

## Overview

This Python script allows you to scrape and collect contest ranking data from the [Vjudge](https://vjudge.net) platform. It retrieves information such as user rankings, solved problem counts, and penalty minutes for specified contests.

## Prerequisites

Before running the script, ensure you have the following prerequisites installed:

- Python 3.x
- Selenium library (`pip install selenium`)
- ChromeDriver executable (download it from the [official website](https://sites.google.com/chromium.org/driver/) and place it in the project directory)


## Usage

1. Create a file named `contests.txt` in the project directory. List the contest IDs you want to scrape, one per line.

2. Edit the `ignore` set in the `main.py` script to specify any usernames you want to ignore during scraping.

3. Run the script:

   ```bash
   python main.py
   ```

   The script will start scraping contest data and generate a `rank.txt` file with the results.