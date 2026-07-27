# Spotify Analytics Dashboard

**Author:** Matthew Muzofa

---

## 📌 Project Overview

This project demonstrates data visualisation skills using Tableau to build an interactive analytics dashboard. The dashboard explores patterns in Spotify music data across 2,000 songs, revealing insights about genre popularity, artist performance, and audio characteristics. Multiple interactive filters allow users to explore the data dynamically.

---

## 🗃️ Dataset

- **Source:** Spotify Songs Dataset
- **Songs Included:** 2,000 tracks
- **Time Period:** Multiple years of music data
- **Features Include:** 
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
| CSV Data | Source data format |

---

## 📊 Dashboard Visuals

| # | Visual | Type | Description |
|---|--------|------|-------------|
| 1 | Most Popular Genres | Treemap | Shows genres sized by average popularity; larger boxes = more popular genres |
| 2 | Popularity Trends | Line Chart | Tracks how song popularity has changed over years |
| 3 | Energy vs Danceability | Scatter Plot | Explores relationship between energy and danceability; colored by genre |
| 4 | Top 10 Artists | Bar Chart | Shows the 10 artists with the highest average song popularity |
| 5 | Tempo Distribution | Histogram | Shows how tempos are distributed across all songs in the dataset |

---

## 💡 Key Features

- **Interactive Filters** — Click on genres, artists, or other elements to filter all dashboard charts simultaneously
- **Multi-dimensional Analysis** — Explore relationships between audio features and popularity
- **Genre Insights** — Understand which genres dominate in popularity metrics
- **Artist Performance** — Identify top-performing artists by average song popularity
- **Audio Characteristics** — Discover patterns in song tempo, energy, and danceability

---

## 📁 File Structure

```
spotify-analytics-dashboard/
│
├── Spotify Analytics Dashboard.twbx    # Complete Tableau dashboard file (interactive)
└── songs_normalize.csv                 # Dataset with 2,000 Spotify songs
```

---

## 🚀 How to Use

**To view and interact with the dashboard:**

1. Download **Tableau Public** (free) or **Tableau Desktop** from [tableau.com](https://tableau.com)
2. Download the `.twbx` file from this repository
3. Open the file in Tableau
4. Interact with the dashboard:
   - Click on genres, bars, or points to filter
   - Hover over elements to see tooltips with detailed information
   - Use the interactive features to explore different angles of the data

**To modify the dashboard:**

1. Open the `.twbx` file in Tableau Desktop
2. Edit the worksheets or add new visualisations
3. Save your changes

---

## 💡 Insights from the Data

- Different genres show distinct patterns in energy and danceability
- Song popularity has varied across years with clear trends
- Top artists consistently produce popular tracks
- Tempo distribution reveals most songs fall within a specific range
- Energy and danceability have interesting correlations by genre

---

## 🔑 Tableau Skills Demonstrated

- **Data Connection & Preparation** — Connecting to CSV and understanding data structure
- **Multiple Visualisation Types** — Treemaps, line charts, scatter plots, bar charts, histograms
- **Interactive Dashboards** — Combining multiple sheets with filters
- **Colour Encoding** — Using colour to add dimensional information
- **Dashboard Layout** — Professional arrangement of visuals for clarity
- **Filtering & Interactivity** — Creating dynamic user experiences

---

## 📊 Comparison: Tableau vs Power BI

This project demonstrates Tableau's strengths:
- **Visualisation flexibility** — More chart type options and customisation
- **Aesthetic appeal** — Smoother, more polished default styling
- **Interactive exploration** — Intuitive filtering and drill-down capabilities
- **Colour schemes** — More sophisticated colour palettes

Combined with your Power BI experience, you now have proficiency with both leading BI tools.

---

*This project is part of my data analyst portfolio. Feel free to explore the dashboard and reach out if you have any feedback.*
