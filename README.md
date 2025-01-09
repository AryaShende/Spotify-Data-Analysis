# Spotify Dataset Analysis

This project analyzes a dataset containing information about the most famous songs of 2023 on Spotify. The analysis aims to uncover trends, patterns, and insights that can be valuable for music industry professionals, artists, and music enthusiasts.

---

## Table of Contents
- [Introduction](#introduction)
- [Dataset Overview](#dataset-overview)
- [Technologies Used](#technologies-used)
- [Data Preprocessing](#data-preprocessing)
- [Data Analysis and Visualization](#data-analysis-and-visualization)
- [Key Insights](#key-insights)
- [Conclusion](#conclusion)
- [Contributors](#contributors)

---

## Introduction

Spotify is a leading music streaming platform offering access to a vast library of songs, podcasts, and more. This project provides insights into the attributes, popularity, and streaming performance of tracks listed on Spotify.

---

## Dataset Overview

The dataset used in this project includes details such as:
- Track names and artist information.
- Release dates.
- Presence on Spotify, Apple Music, and Deezer playlists and charts.
- Audio features (e.g., BPM, danceability, energy).
- Streaming statistics.

**Dataset Source**: [Top Spotify Songs 2023](https://www.kaggle.com/datasets/nelgiriyewithana/top-spotify-songs-2023)

---

## Technologies Used

- **Python**: Data analysis and visualization.
- Libraries:
  - `pandas`
  - `matplotlib`
  - `seaborn`
  - `numpy`

---

## Data Preprocessing

### Steps Taken:
1. **Handling Missing Values**:
   - Replaced missing rankings with "Not Ranked" for interpretability.
   - Converted numerical values for machine learning readiness.
   - Dropped rows with missing musical key values.
2. **Data Type Adjustments**:
   - Combined year, month, and day into a single release date.
   - Converted numerical columns for accurate analysis.
3. **Defined Percentage Columns**:
   - Standardized columns like `danceability_%` and `energy_%`.

---

## Data Analysis and Visualization

1. **Histograms**:
   - Visualized distributions for numeric features like BPM, danceability, and streams.
2. **Correlation Analysis**:
   - Heatmaps for identifying relationships between features.
3. **Insights from Streaming Platforms**:
   - Examined cross-platform performance of tracks.
4. **Top Artists and Tracks**:
   - Identified the most streamed songs and artists.

---

## Key Insights

1. **Most Streamed Songs**:
   - "Blinding Lights" by The Weeknd leads with over 3.7 billion streams.
2. **Popular Artists**:
   - Artists with the most tracks in playlists include [Top Artists].
3. **Temporal Trends**:
   - Majority of tracks released in the 2020s.
4. **Audio Features**:
   - Danceability and valence are positively correlated.
   - Energetic tracks tend to have lower acousticness.

---

## Conclusion

The analysis highlights:
- Trends in streaming performance and temporal release patterns.
- Insights into audio features driving track popularity.
- Cross-platform presence of tracks and artists.

These findings are valuable for music professionals and enthusiasts in decision-making and strategy planning.

---

## Contributors

- **Atharva Kolhe**
- **Arya Shende**
- **Neel Panday**

**Guided by**: Dr. Prachi Natu

---
