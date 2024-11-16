# Top Tracks Analysis: Billboard Hot 100 Trends (2019-2023)

![Spotify Badge](https://img.shields.io/badge/made_with-spotify-%231DB954?logo=spotify&logoColor=white) ![Python Badge](https://img.shields.io/badge/made_with-python-%233776AB?logo=python&logoColor=white) ![Jupyter Badge](https://img.shields.io/badge/made_with-jupyter-%23F37626?logo=jupyter&logoColor=white)

This project analyzes the [Top Tracks of the Billboard Hot 100](https://www.billboard.com/charts/year-end/2023/hot-100-songs/) from 2019 to 2023, using **Spotify** playlists and data extracted via [Choosic](https://www.chosic.com/), a music analytics tool and [LyricsGenius](https://github.com/johnwmillr/LyricsGenius), a Python library that interacts with the Genius API. The goal is to explore the characteristics of the most popular songs during this period.

## Business Problem

Music tastes evolve over time, influenced by cultural shifts, technological advances, and global events. By analyzing Billboard Hot 100 tracks from 2019 to 2023, the goal is to identify how listener preferences have changed and what factors have driven these shifts.

### Areas of Focus

#### Music Identity

- **Dominant Genres**: Analyzing which genres are most prevalent and how their dominance has shifted over the years.
- **Key Tracking**: Identifying the most commonly used musical keys.
- **BPM Trends**: Investigating the tempo trends (e.g., fast vs. slow songs) change year over year.
- **Happiness Trends**: Tracking how the overall "happiness" of songs has evolved over time.
- **Temporal Trends**: Are older songs making a comeback, or is the list dominated by new hits?
- **Lyrics**: Analyzing the lyrics of the top tracks over the years.

#### Artist Landscape

- **Artist Consistency**: Analyzing which artists had the most tracks over time and each year.
- **Artist Collaborations**: Uncovering the most common partnerships between artists.
- **Artist Growth**: Studying the rise of artists in different years and their impact on the charts.
- **Artist Nationalities**: Analyzing the nationalities of the most prominent artists over this period.
- **Song Longevity**: Identifying tracks that stayed on the Billboard Hot 100 for more than one year.

## Methodology

### Data Collection

The names of the 100 most popular songs were extracted from **Billboard Hot 100** songs from 2019 to 2023. Via Spotify playlists made by me, **Choosic** was used to gather enriched metadata for each track:

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

Additionally, **LyricsGenius** provided the **lyrics** for each track.

### Data Analysis

In progress.

## Skills

- **Python**: Pandas, Matplotlib, Jupyter Notebooks, LyricsGenius API
- **Data Analysis**: Data cleaning, aggregation, trend analysis, and visualizations
- **APIs**: Interacting with external APIs (Genius API for lyrics)
- **Data Visualization**: Creating impactful charts and graphs to communicate trends and patterns

## Limitations

- **Data Bias**: While the Billboard Hot 100 is based on streaming, radio airplay, and sales data, it may not fully represent global music.
- **Metadata Inconsistencies**: The mood and genre classifications are based on Choosic's algorithms and may not always align with listener expectations.
- **Data Availability**: The dataset is limited to the top 100 tracks each year and may exclude songs that were popular in niche genres or underground music scenes.
