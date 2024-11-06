# Top Tracks Analysis: Billboard Hot 100 Trends (2019-2023)

![Spotify Badge](https://img.shields.io/badge/made_with-spotify-%231DB954?logo=spotify&logoColor=white) ![Python Badge](https://img.shields.io/badge/made_with-python-%233776AB?logo=python&logoColor=white) ![Jupyter Badge](https://img.shields.io/badge/made_with-jupyter-%23F37626?logo=jupyter&logoColor=white)

This project analyzes the **Top Tracks of the Billboard Hot 100** from 2019 to 2023, using **Spotify** playlists and data extracted via **Choosic**, a music analytics tool. The goal is to explore the characteristics of the most popular songs during this period, focusing on attributes like **genre**, **mood**, **artist**, and **decade of release**. Choosic's enriched metadata helps us dive deeper into the evolving trends of popular music.

##  **Project Overview**

This analysis aims to explore:
- **Genre Trends**: What genres are dominating the Billboard Hot 100 each year?
- **Mood Shifts**: How does the emotional tone of popular music change over time?
- **Artist Landscape**: Which artists are emerging, and which are consistently popular across years?
- **Temporal Trends**: Are older songs making a comeback, or is the list dominated by new hits?

## **Data Collection**

The dataset is composed of the following:
- **Billboard Hot 100** songs from 2019 to 2023, extracted via Spotify playlists.
- **Choosic API** is used to gather enriched metadata for each track:
  - **Track Name**
  - **Artist(s)**
  - **Genre(s)**
  - **Mood(s)**
  - **Decade of Release**
  - **Popularity Metrics**

## **Limitations**

- **Regional Bias**: While Spotify is a dominant music streaming app, its popularity varies by region, which may limit the representativeness of the data in certain countries.
- **Metadata Inconsistencies**: The mood and genre classifications are based on Choosic's algorithms and may not always align with listener expectations.
- **Data Availability**: The dataset is limited to the top 100 tracks each year and may exclude songs that were popular in niche genres or underground music scenes.
