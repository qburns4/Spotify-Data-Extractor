# Spotify-Data-Extractor

## Overview

This project builds a Spotify → Data Frame → SQL pipeline that allows users to extract their personal Spotify listening history and save it for use in Excel, Tableau, Power BI, or other analytics tools.

## Skills Demonstrated

* Connect to an API and load data into notebook
* Build a repeatable API-to-SQL pipeline
* Store and query data with SQLite
* Transform data into a pandas DataFrame for further analysis and visualization.

## How It Works

1. Authenticate with the Spotify Web API via Spotipy.
2. Collect your listening history and track metadata (artist, song, album, time listened, etc.).
3. Store the results in a SQLite database.
4. Query the database and load results into a pandas DataFrame.
5. Export or connect the data to Excel, Tableau, or Power BI for visualization.
