# Top Tracks Analysis: Billboard Hot 100 Trends (2019-2023)

![Spotify Badge](https://img.shields.io/badge/made_with-spotify-%231DB954?logo=spotify&logoColor=white) ![Python Badge](https://img.shields.io/badge/made_with-python-%233776AB?logo=python&logoColor=white) ![Jupyter Badge](https://img.shields.io/badge/made_with-jupyter-%23F37626?logo=jupyter&logoColor=white)

This project analyzes the **Top Tracks of the Billboard Hot 100** from 2019 to 2023, using **Spotify** playlists and data extracted via **Choosic**, a music analytics tool. The goal is to explore the characteristics of the most popular songs during this period.
## **Project Overview**

### Music Identity

- **Dominant Genres**: Analyzing which genres are most prevalent and how their dominance has shifted over the years.
- **Key Tracking**: Identifying the most commonly used musical keys.
- **BPM Trends**: Investigating the tempo trends (e.g., fast vs. slow songs) change year over year.
- **Happiness Trends**: Tracking how the overall "happiness" of songs has evolved over time.
- **Temporal Trends**: Are older songs making a comeback, or is the list dominated by new hits?

### Artist Landscape

- **Artist Consistency**: Analyzing which artists had the most tracks over time and each year.
- **Artist Collaborations**: Uncovering the most common partnerships between artists.
- **Artist Growth**: Studying the rise of artists in different years and their impact on the charts.
- **Artist Nationalities**: Analyzing the nationalities of the most prominent artists over this period.
- **Song Longevity**: Identifying tracks that stayed on the Billboard Hot 100 for more than one year.

## **Data Collection**
The names of the 100 most popular songs were extracted from the **Billboard Hot 100** songs from 2019 to 2023. via Spotify playlists, **Choosic** was used to gather enriched metadata for each track:

  - **Song Title**
  - **Artist(s)**
  - **Popularity Metrics**
  - **BPM (Beats Per Minute)** and **Time Signature**
  - **Genres** and **Parent Genres**
  - **Album Name** and **Album Release Date**
  - **Album Label**
  - **Danceability**
  - **Energy Level**
  - **Acousticness**
  - **Instrumentalness**
  - **Happiness**
  - **Speechiness**
  - **Loudness (dB)**
  - **Key** and **Camelot Key**
  - **ISRC (International Standard Recording Code)**

## **Limitations**

- **Data Bias**: While the Billboard Hot 100 is based on streaming, radio airplay, and sales data, it may not fully represent global music.
- **Metadata Inconsistencies**: The mood and genre classifications are based on Choosic's algorithms and may not always align with listener expectations.
- **Data Availability**: The dataset is limited to the top 100 tracks each year and may exclude songs that were popular in niche genres or underground music scenes.
