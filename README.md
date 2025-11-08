# Track-Hub Music Database  
A Python + SQLite project for exploring, analyzing, and exporting insights from a structured music library database.

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/soulafterdark/Track-Hub-music-db/blob/main/notebooks/TrackHub_%E2%80%94_A_Python_%2B_SQLite_Music_Database_Project.ipynb)

---

## 📌 Overview  
Track-Hub is a lightweight, end-to-end data project that demonstrates how to:

- Build and query a relational music database in **SQLite**
- Use Python (Pandas + SQL) to extract insights
- Generate reusable CSV exports for reporting and analysis
- Package the project in a clean, reproducible, portfolio-friendly repo

This project can be expanded into a real-world music catalog, DJ library manager, recommendation system dataset, or ETL demo.

---

## 🗄️ Database Schema (Auto-Detected)

| Table | Key Fields |
|--------|------------|
| **Artist** | `id`, `name` |
| **Album** | `id`, `title`, `artist_id` |
| **Genre** | `id`, `name` |
| **Track** | `id`, `title`, `album_id`, `genre_id`, `milliseconds` |

✅ No ORM required — everything runs in raw SQL

---

## 📂 Repository Structure

👨‍💻 Who Would Use This
Data Engineers / Analysts prototyping ETL and SQL workflows
DJs seeking to analyze and clean up personal music libraries
Product Managers evaluating music analytics and catalog tools
Developers building Spotify-style apps, playlist APIs, or AI song recommenders
🚀 Future Enhancements
Add BPM, key, mood, and energy metadata for performance/DJ analysis
Build a playlist generator: “Give me 15 house tracks under 128 BPM”
Add Spotify API integration to enrich the dataset with popularity, release date, etc.
Package into a Python CLI tool or Flask app
Visualize data via dashboards (genres per year, artist timelines, etc.)
