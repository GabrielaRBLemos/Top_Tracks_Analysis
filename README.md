# Top Tracks Analysis: Popular Music Trends (2019-2023)
![Spotify Badge](https://img.shields.io/badge/made_with-spotify-%231DB954?logo=spotify&logoColor=white) ![Python Badge](https://img.shields.io/badge/made_with-python-%233776AB?logo=python&logoColor=white) ![Jupyter Badge](https://img.shields.io/badge/made_with-jupyter-%23F37626?logo=jupyter&logoColor=white)



This project analyzes the **Top Tracks of [YEAR]** playlists from Spotify over the last five years (2019-2023). The goal is to explore the characteristics of the most popular songs during this period, focusing on attributes like **genre**, **mood**, **artist**, and **decade of release**. Data is collected using **Choosic**, a music analytics tool that provides enriched metadata, allowing for a deeper analysis of current music trends.

##  **Project Overview**

This analysis aims to explore:
- **Genre Trends**: What genres are dominating the top tracks each year?
- **Mood Shifts**: How does the emotional tone of popular music change over time?
- **Artist Landscape**: Which artists are emerging, and which are consistently popular across years?
- **Temporal Trends**: Are older songs making a comeback, or is the list dominated by new hits?

## **Data Collection**

The dataset is composed of the following:
- **Spotify "Top Tracks of [YEAR]"** playlists from 2019 to 2023.
- **Choosic API** is used to gather enriched metadata for each track:
  - **Track Name**
  - **Artist(s)**
  - **Genre(s)**
  - **Mood(s)**
  - **Decade of Release**
  - **Popularity Metrics**

## **Limitations**

- **Regional Bias**: While Spotify is the **dominant music streaming app** globally, it is not equally popular in every country. This regional variation could limit the representativeness of the data for certain areas.
- **Metadata Inconsistencies**: The mood and genre classifications are based on Choosic's algorithms and may not always align with user expectations.
- **Data Availability**: The dataset is limited to the top 100 tracks each year and does not include tracks that may have been popular in specific sub-genres or underground music scenes.
