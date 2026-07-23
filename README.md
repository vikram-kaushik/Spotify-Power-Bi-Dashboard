# 🎧 Spotify Top 50 World — Power BI Dashboard

An interactive Power BI dashboard analyzing songs and artists from Spotify's **Top 50 World** playlists, covering distinct songs, popularity trends, explicit content splits, album types, and artist-level performance.

<img width="1436" height="805" alt="Screenshot 2026-07-11 210100" src="https://github.com/user-attachments/assets/9afad2cc-cdea-42e7-85d2-3581c0f54e14" />


---

## 📊 Overview

This project explores **789 distinct songs** across **342 artists**, digging into what drives popularity on Spotify's global charts — release patterns, album vs. single performance, explicit vs. non-explicit content, and how popularity shifts across months and quarters.

The dashboard is split into four pages:

| Page | Description |
|------|-------------|
| **Home** | Landing/navigation page with album art background and page navigation buttons |
| **Overview** | High-level KPIs — distinct songs, artist count, average duration, average popularity — plus breakdowns by year, album type, explicit content, and month-over-month trends |
| **Artists** | Artist-level drill-down with a searchable song/artist slicer, "Position 1" song rankings, and a detailed release table (album type, release date, duration, popularity) |
| **Songs** | Song popularity rankings and an artist comparison table (max popularity, songs per year, explicit song count, avg tracks per album) |

---

## 🖼️ Dashboard Preview

### Overview Page
<img width="1438" height="808" alt="Screenshot 2026-07-11 210132" src="https://github.com/user-attachments/assets/20cd9981-ee30-445a-b350-f400fefaa20c" />

KPI cards for distinct songs, artist count, avg duration, and avg popularity, alongside donut charts for Single vs. Album split, Explicit vs. Non-Explicit songs, Songs by Year, and Songs by Album Type. Line and bar charts track average popularity and distinct song releases by month.

### Artists Page
<img width="1440" height="808" alt="Screenshot 2026-07-11 210235" src="https://github.com/user-attachments/assets/dc6b50c8-dd45-48c1-9ff2-f133a7fa6ef9" />

Drill into any artist to see their top-ranked songs, with a detailed table showing album type, release date, average duration, and both max and average popularity per track.

### Songs Page
<img width="1440" height="807" alt="Screenshot 2026-07-11 210259" src="https://github.com/user-attachments/assets/8d9aafc8-7ae7-4166-8dab-3d2cc2fba4e3" />

Ranks songs by popularity and compares artists on max popularity, songs released per year, explicit song counts, and average tracks per album.

---

## 🔑 Key Features

- **Interactive slicers** — search and filter by artist, song, or select-all across all analysis pages
- **Cross-filtering navigation** — clicking any visual filters the rest of the report page
- **Custom KPI cards** with icon-based visuals for song count, artist count, duration, and popularity
- **Time intelligence** — average popularity and distinct song counts by month, with Month/Quarter toggle
- **Embedded media player visual** — album art with playback-style controls per selected song
- **Donut charts** for categorical splits (Single vs. Album, Explicit vs. Non-Explicit, Album Type)

---

## 🛠️ Tools & Techniques

- **Power BI Desktop** — data modeling, DAX measures, report design
- **DAX** — calculated measures for average popularity, songs per year, tracks per album, and time-based aggregations using `CALCULATE`, iterators, and time intelligence functions
- **Power Query** — data cleaning and shaping of raw Spotify track/artist data
- **UI/UX** — dark theme with Spotify-branded green accents, custom nav bar, and consistent card layout across pages

---

## 📁 Data

Track and artist metadata sourced from Spotify's Top 50 World playlists, including fields such as song title, artist, album type, release date, duration, and popularity score.

---

## 🔗 Links

- **LinkedIn:** [linkedin.com/in/vikramkaushik007](https://linkedin.com/in/vikramkaushik007)
- **GitHub:** [github.com/vikram-kaushik](https://github.com/vikram-kaushik)

---

*Part of a broader Power BI portfolio built for Data/Business Analyst job applications — see the [main portfolio index](https://github.com/vikram-kaushik) for other projects.*
