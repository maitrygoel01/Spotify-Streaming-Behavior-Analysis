# Spotify-Streaming-Behavior-Analysis

## 📌 Project Overview

Spotify Streaming Behavior Analysis Dashboard is an end-to-end Power BI solution designed to analyze personal music streaming habits and listening patterns using Spotify streaming history data sourced from Kaggle. The dashboard provides a centralized view of key listening metrics, enabling users to explore artist preferences, album engagement, track popularity, platform usage, and listening behavior through interactive visual analytics.

The project analyzes years of Spotify listening activity across multiple devices and platforms, helping uncover trends in music consumption, user engagement, and listening preferences over time.

---

# 🎯 Business Problem

Music streaming platforms generate large amounts of user interaction data, but extracting meaningful insights from this information can be challenging.

This dashboard helps answer key questions such as:

* Which artists, albums, and tracks are listened to most frequently?
* How have listening habits evolved over time?
* Which platforms are used most often for streaming?
* What are the peak listening hours and days?
* How does shuffle and skip behavior impact listening patterns?
* Which songs receive the highest engagement?
* What listening trends can be identified across years?

By transforming raw streaming history into interactive dashboards, users can better understand their listening behavior and preferences.

---

# 📊 Listening Performance KPIs

| KPI                    | Value                                |
| ---------------------- | ------------------------------------ |
| Total Albums Played    | 7,383                                |
| Total Artists Played   | 3,835                                |
| Total Tracks Played    | 12,724                               |
| Unique Albums          | 7,907                                |
| Unique Artists         | 4,112                                |
| Unique Tracks          | 13,665                               |
| Average Listening Time | 2.14 Minutes                         |
| Analysis Period        | Multi-Year Spotify Listening History |

---

# 🔷 1. Executive Listening Overview

The Executive Dashboard provides a consolidated view of Spotify listening behavior.

### Key Insights

### Album Analytics

* Tracks album listening trends over time.
* Measures yearly album engagement.
* Identifies most played albums.

### Artist Analytics

* Highlights favorite artists.
* Measures artist discovery and engagement trends.
* Compares yearly artist listening activity.

### Track Analytics

* Identifies most frequently played tracks.
* Measures track-level engagement.
* Tracks listening growth over time.

### Listening Trends

* Monitors yearly listening behavior.
* Compares weekday and weekend listening activity.
* Identifies peak engagement periods.

---

# 🔷 2. Album Performance Analysis

The Album Dashboard focuses on album-level listening behavior.

### Business Questions Answered

* Which albums are played most frequently?
* How has album listening evolved over time?
* Which albums receive the highest engagement?
* What are the yearly trends in album consumption?

### Analysis Performed

### Album Trends Over Time

Tracks annual album listening activity and identifies listening peaks.

### Top Albums Analysis

Ranks albums by total play count.

Top Albums Include:

* The Beatles
* Past Masters
* Abbey Road
* The Wall
* Revolver

### Album Engagement Distribution

Analyzes album listening patterns across weekdays and weekends.

### Business Value

* Understands album loyalty.
* Identifies long-term listening preferences.
* Reveals music consumption trends.

---

# 🔷 3. Artist Performance Analysis

The Artist Dashboard provides artist-level listening insights.

### Key Metrics

| Metric                | Value       |
| --------------------- | ----------- |
| Total Artists Played  | 3,835       |
| Unique Artists        | 4,112       |
| Top Artist            | The Beatles |
| Artist Trend Analysis | Available   |

### Analysis Performed

### Artist Discovery Trends

Measures growth in artist exploration across years.

### Top Artist Ranking

Identifies artists with the highest stream counts.

Top Artists Include:

* The Beatles
* The Killers
* John Mayer
* Bob Dylan
* Paul McCartney

### Artist Engagement Analysis

Compares frequency of listening among favorite artists.

### Business Value

* Measures artist loyalty.
* Tracks music discovery patterns.
* Identifies dominant listening preferences.

---

# 🔷 4. Track Performance Analysis

The Track Dashboard focuses on song-level engagement and popularity.

### Key Metrics

| Metric                 | Value        |
| ---------------------- | ------------ |
| Total Tracks Played    | 12,724       |
| Unique Tracks          | 13,665       |
| Average Listening Time | 2.14 Minutes |

### Analysis Performed

### Top Tracks Analysis

Most Played Tracks Include:

* Ode To The Mets
* In The Blood
* Dying Breed
* 19 Dias y 500 Noches
* Concerning Hobbits

### Track Frequency Analysis

Measures how often tracks are replayed.

### Listening Duration Analysis

Analyzes average listening time per track.

### Business Value

* Identifies favorite songs.
* Measures listener engagement.
* Reveals replay behavior.

---

# 🔷 5. Listening Behavior Analysis

The Listening Behavior Dashboard provides insights into when and how music is consumed.

### Analysis Performed

### Listening Hours Heatmap

Analyzes listening activity across:

* Hours of the Day
* Days of the Week

### Peak Listening Periods

Highest activity occurs during:

* Evening Hours
* Night-Time Listening Sessions
* Weekend Periods

### Listening Frequency Analysis

Tracks:

* Listening Time
* Stream Frequency
* Song Engagement

### Business Value

* Understands listening routines.
* Identifies peak engagement periods.
* Reveals behavioral listening patterns.

---

# 🔷 6. Platform Usage Analysis

The dashboard allows users to analyze listening activity across multiple Spotify platforms.

### Platforms Included

* Android
* iOS
* Mac
* Windows
* Web Player
* Cast To Device

### Analysis Performed

### Platform Distribution

Measures streaming activity by device type.

### Platform Trends

Tracks listening behavior across platforms over time.

### Business Value

* Understands preferred listening devices.
* Measures cross-platform engagement.
* Reveals technology adoption trends.

---

# 🔷 7. Shuffle & Skip Behavior Analysis

The dashboard includes advanced behavioral filters to analyze listening engagement.

### Analysis Performed

### Shuffle Analysis

Tracks:

* Shuffled Playback
* Non-Shuffled Playback

### Skip Analysis

Measures:

* Skipped Tracks
* Completed Plays

### Business Value

* Understands engagement quality.
* Identifies favorite versus exploratory listening behavior.
* Reveals content consumption patterns.

---

# 📈 Key Insights

## Listening Insights

* Classic Rock and Legacy Artists dominate listening activity.
* Album-based listening remains a strong preference.
* Listening behavior peaked around 2021–2022.

## Artist Insights

* A small group of artists account for a significant share of streams.
* Listener loyalty is concentrated among favorite artists.

## Track Insights

* Frequently played songs are not always listened to for the longest duration.
* High-frequency tracks indicate strong personal preferences.

## Behavioral Insights

* Listening activity is highest during evenings and weekends.
* Users follow consistent listening routines throughout the week.

## Platform Insights

* Mobile platforms contribute significantly to overall listening activity.
* Multi-platform listening behavior demonstrates flexibility and convenience.

---

# 🛠️ Technical Implementation

## Data Modeling

A star schema model was implemented for efficient reporting and analytics.

### Fact Table

* Spotify Streaming History

### Dimension Tables

* Dim Date
* Dim Album
* Dim Artist
* Dim Track
* Dim Platform

---

## Power Query Transformations

The ETL process included:

* Data Cleaning
* Null Value Handling
* Date Formatting
* Data Type Conversion
* Relationship Creation
* Derived Columns
* Performance Optimization

---

## DAX Measures

* Total Albums Played
* Total Artists Played
* Total Tracks Played
* Average Listening Time
* Listening Time by Platform
* Top Album Ranking
* Top Artist Ranking
* Top Track Ranking
* Year-over-Year Growth
* Listening Frequency Metrics

---

# 🎨 Dashboard Features

## Interactive Navigation

* Overview Dashboard
* Listening Behavior Analysis
* Album Detail Analysis

## Dynamic Filters

* Year
* Platform
* Shuffle Status
* Skip Status

## User Experience

* Cross Filtering
* Dynamic Slicers
* Interactive Tooltips
* Drill-Through Analysis
* Responsive Layout

---

# 🧰 Tools & Technologies

| Tool             | Purpose                |
| ---------------- | ---------------------- |
| Power BI Desktop | Dashboard Development  |
| Power Query      | Data Transformation    |
| DAX              | KPI & Measure Creation |
| Kaggle Dataset   | Data Source            |
| Data Modeling    | Star Schema Design     |

---

# 📷 Dashboard Screenshots

## Executive Dashboard

<img width="1105" height="732" alt="image" src="https://github.com/user-attachments/assets/6bf4a232-fbbc-4ae5-bfd0-52d09f5ee8e1" />


## Listening Behavior Dashboard

<img width="1106" height="742" alt="image" src="https://github.com/user-attachments/assets/9225692c-0ac3-4a49-8d09-5a0a82e573e5" />


## Album Details Dashboard

<img width="1117" height="741" alt="image" src="https://github.com/user-attachments/assets/c158c693-6917-4a78-801a-3ddb48162d0a" />

---

# 📂 Project Structure

```text
Spotify-Streaming-Behavior-Analysis/
│
├── Dataset/
│   └── spotify_streaming_history.csv
│
├── Dashboard/
│   └── Spotify_Streaming_Behavior.pbix
│
├── Images/
│   ├── executive-dashboard.png
│   ├── listening-behavior.png
│   └── album-details.png
│
└── README.md
```

---

# 📌 Conclusion

The Spotify Streaming Behavior Analysis Dashboard provides a comprehensive music analytics platform that enables users to explore listening habits, identify favorite artists and albums, analyze engagement patterns, understand platform usage, and uncover meaningful insights from years of Spotify streaming history through interactive visualizations.

---

# ⭐ Project Summary

An interactive Power BI dashboard that analyzes Spotify streaming history to uncover listening patterns, artist preferences, album engagement, track popularity, platform usage, and user behavior through advanced analytics and interactive visual storytelling.
