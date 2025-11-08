# Track-Hub Music Database

A Python + SQLite project for exploring, analyzing, and exporting insights from a structured music library database.

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/soulafterdark/Track-Hub-music-db/blob/main/notebooks/TrackHub_%E2%80%94_A_Python_%2B_SQLite_Music_Database_Project.ipynb)
![Made with Python](https://img.shields.io/badge/Made%20with-Python-blue)
![Database](https://img.shields.io/badge/Database-SQLite-informational)
![License: MIT](https://img.shields.io/badge/License-MIT-green)

---

## 📌 Overview

Track-Hub is a lightweight, end-to-end data project that demonstrates how to:

- Build and query a relational music database in **SQLite**
- Use Python (**Pandas + SQL**) to extract insights
- Generate reusable **CSV exports** for reporting and analysis
- Package the project in a clean, reproducible, portfolio-ready repo

This project can be expanded into a real-world **music catalog**, **DJ library manager**, **recommendation system dataset**, or **ETL demo**.

---

## 🗄️ Database Schema (Auto-Detected)

| Table  | Key Fields |
|--------|------------|
| Artist | `id`, `name` |
| Album  | `id`, `title`, `artist_id` |
| Genre  | `id`, `name` |
| Track  | `id`, `title`, `album_id`, `genre_id`, `milliseconds` |

✅ No ORM required — everything runs in raw SQL.

---

## 📂 Repository Structure

Track-Hub-music-db/
├── data/
│ ├── musicdb.sqlite
│ ├── exports/
│ │ ├── albums_by_artist.csv
│ │ ├── top_artists.csv
│ │ ├── top_genres.csv
│ │ └── tracks_sample.csv
│ └── raw/
│ └── README.md
├── notebooks/
│ └── TrackHub_—A_Python+_SQLite_Music_Database_Project.ipynb
├── .gitignore
├── LICENSE
└── README.md





---

## 👨‍💻 Who Would Use This

- Data Engineers / Analysts prototyping ETL and SQL workflows  
- DJs cleaning and organizing personal music libraries  
- Product Managers evaluating music analytics and catalog tools  
- Developers building Spotify-style apps, playlist APIs, or AI recommenders  

---

## 🚀 Future Enhancements

- Add BPM, key, mood, and energy metadata for DJ/performance analysis  
- Build a playlist generator (e.g., “Give me 15 house tracks under 128 BPM”)  
- Integrate Spotify API to enrich the dataset with popularity + release data  
- Package into a Python CLI tool or Flask app  
- Add dashboards for trends (genres per year, artist activity, etc.)  

---

## 📜 License

This project is licensed under the **MIT License**.  
Project by **Gabe Chavez (soulafterdark)**.


