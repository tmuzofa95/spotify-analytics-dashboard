# Spotify Analytics Dashboard

Author: Matthew Muzofa

---

## 📌 Project Overview

This project demonstrates data visualisation skills using Tableau to build an interactive analytics dashboard. The dashboard explores patterns in Spotify music data across 2,000 songs, revealing insights about genre popularity, artist performance, and audio characteristics.

---

## 🗃️ Dataset

- Source: Kaggle - Spotify Songs Dataset
- Songs Included: 2,000 tracks
- Time Period: Multiple years of music data
- Features Include: 
  - Song metadata (artist, title, year, duration)
  - Audio characteristics (energy, danceability, acousticness, valence, tempo)
  - Popularity metrics
  - Genre classifications
  - Explicit content flag

---

## 🛠️ Tools Used

| Tool | Purpose |
|------|---------|
| Tableau Desktop 2026.2 | Dashboard creation and interactive visualisation |
| Kaggle | Dataset Source |

---

## 📊 Dashboard Visuals

| # | Visual | Type | Description |
|---|--------|------|-------------|
| 1 | Most Popular Genres | Treemap | Shows genres sized by average popularity (larger boxes = more popular genres) |
| 2 | Popularity Trends | Line Chart | Tracks how song popularity has changed over years |
| 3 | Energy vs Danceability | Scatter Plot | Explores relationship between energy and danceability (colored by genre) |
| 4 | Top 10 Artists | Bar Chart | Shows the 10 artists with the highest average song popularity |
| 5 | Tempo Distribution | Histogram | Shows how tempos are distributed across all songs in the dataset |

---

## 💡 Key Features

- Interactive Filters - Click on genres, artists, or other elements to filter all dashboard charts simultaneously
- Multi-dimensional Analysis - Explore relationships between audio features and popularity
- Genre Insights - Understand which genres dominate in popularity metrics
- Artist Performance - Identify top performing artists by average song popularity
- Audio Characteristics - Discover patterns in song tempo, energy, and danceability

---

## 📁 File Structure

```
spotify-analytics-dashboard/
│
├── Spotify Analytics Dashboard.twbx    # Complete Tableau dashboard file (interactive)
└── songs_normalize.csv                 # Dataset with 2,000 Spotify songs
```

---

## 💡 Insights from the Data

- Different genres show distinct patterns in energy and danceability
- Song popularity has varied across years with clear trends
- Top artists consistently produce popular tracks
- Tempo distribution reveals most songs fall within a specific range
- Energy and danceability have interesting correlations by genre

---
