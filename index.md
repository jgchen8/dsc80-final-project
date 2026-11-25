# Predicting Spotify Track Popularity from Audio Features 
*Exploratory Data Analysis, Hypothesis Testing, and Regression Modeling*

---

## 1. Introduction

### Dataset & Research Question
This project explores Spotify track metadata and audio features from `music_tracks.csv`, which contains five tracks across different musical genres. The central question driving this investigation is: **Do tracks that are more danceable tend to be more popular, and how well do audio and metadata features predict a track's popularity?**[cite: 5, 11]

### Why This Matters
Understanding what makes a song resonate on streaming platforms is valuable for independent artists, music producers, and recommendation engineers alike[cite: 11]. By identifying which audio characteristics correlate with higher popularity, we can better separate musical qualities from algorithmic momentum[cite: 5, 11].

### Relevant Columns
Below are the columns in `music_tracks.csv` relevant to our exploratory analysis, hypothesis testing, and predictive modeling:

| Column | Description |
| :--- | :--- |
| `track_id` | Spotify's unique identifier for the track |
| `track_name` | Name of the track |
| `artists` | Name(s) of the artist(s), separated by semicolons |
| `popularity` | Spotify popularity score from 0–100, based on total plays and recency (higher = more popular) |
| `danceability` | How suitable the track is for dancing, based on tempo, rhythm stability, and beat strength (0–1) |
| `energy` | Perceptual intensity and activity: fast, loud, noisy tracks score high; classical scores low (0–1) |
| `duration_ms` | Duration of the track in milliseconds |
| `release_date` | Release date of the track (`YYYY-MM-DD`, `YYYY-MM`, or `YYYY`) |
| `explicit` | Whether the track contains explicit content |
| `loudness` | Overall loudness of the track in decibels (dB), typically ranging from -60 to 0 dB |
| `valence` | Musical positiveness: high values sound happy and cheerful; low values sound sad or angry (0–1) |
| `tempo` | Estimated beats per minute (BPM) |
| `acousticness` | Confidence that the track is acoustic rather than electronically produced (0–1) |
| `time_signature` | Estimated number of beats per measure (typically 3 or 4) |
| `track_genre` | Genre of the track, as labeled by Spotify[cite: 2, 3, 11] |
