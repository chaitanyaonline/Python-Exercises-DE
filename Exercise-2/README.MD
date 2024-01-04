# Exercise #2 - WebScraping and File Downloading with Python.
## Problem Statement
You need to download a file of weather data from a government website. files that are sitting at the following specified location.

`https://www.ncei.noaa.gov/data/local-climatological-data/access/2021/`

You are looking for the file that was Last Modified on `2023-12-31 22:00`, you can't cheat and lookup the file number yourself. You must use `Python` to scrape this webpage, finding the corresponding file-name for this timestamp, `2023-12-31 22:00`

Once you have obtained the correct file, and downloaded it, you must load the file into `Pandas` and find the record(s) with the highest `HourlyDryBulbTemperature`. Print these record(s) to the command line.

Generally, your script should do the following ...
1. Attempt to web scrap/pull down the contents of `https://www.ncei.noaa.gov/data/local-climatological-data/access/2021/`
1. Analyze it's structure, determine how to find the corresponding file to `2023-12-31 22:00` using `Python`.
1. Build the URL required to download this file, and write the file locally.
1. Open the file with `Pandas` and find the records with the highest `HourlyDryBulbTemperature`
1. Print this to stdout/command line/terminal.
