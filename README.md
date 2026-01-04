# Netflix Content Analytics (Tableau)

## Overview
An interactive Tableau dashboard visualizing Netflix’s global content catalogue.  
The dashboard includes filters, country distribution, ratings analysis, top genres, and content trends over time, demonstrating skills in data cleaning, visualization design, and building an immersive, cohesive dashboard theme.

---

## Dataset

- Source: Netflix Titles dataset (`netflix_titles.csv`) from GitHub.
- Contains approximately 8,000+ movie and TV show entries.
- Columns:
  - `show_id` – Unique identifier for each title
  - `type` – Content type (`Movie` or `TV Show`)
  - `title` – Movie or TV show name
  - `director` – Director(s) listed (may contain missing values)
  - `cast` – Cast members (may contain missing values)
  - `country` – Country of production
  - `date_added` – Date the title was added to Netflix
  - `release_year` – Original release year
  - `rating` – Age rating (e.g., PG‑13, TV‑MA)
  - `duration` – Duration (minutes or number of seasons)
  - `listed_in` – Genre categories
  - `description` – Title description :contentReference[oaicite:1]{index=1}
- Raw dataset: `netflix_titles.csv`

---

## Data Preparation (Tableau)

All data preparation was performed within Tableau, including:

- Standardizing missing values and cleaning inconsistent entries.
- Parsing duration fields for separate handling of movies vs TV shows.
- Extracting year, month, and other fields for time-based analysis.
- Creating calculated fields for genre counts, rating groups, and country distributions.
- Preparing data for dynamic filters and interactive visualizations.

---

## Analysis

- Explored **content distribution** by type, genre, and country.
- Analyzed **ratings breakdown** and how it varies by content type.
- Identified **top genres** globally and in specific regions.
- Examined **trends over time** (release year and date added to Netflix).
- All insights are presented in an interactive Tableau dashboard.

---

## Visualization

- Interactive dashboard built in **Tableau**.
- Includes filters for country, content type (Movie vs TV Show), rating, and genre.
- Dashboard designed with a cohesive branded theme and clear stories for each insight.

🔗 **[Tableau Public dashboard](https://public.tableau.com/app/profile/tung.yee.sia/viz/Netflix_17648574386780/Netflix?publish=yes)** 

---

## Skills Demonstrated

- Tableau: interactive dashboards, filters, calculated fields, and design
- Data cleaning and preparation within Tableau
- Analytical thinking: trend and distribution analysis
- Visualization design: cohesive theme and interactive exploration

---

## Project Structure

```
netflix-content-analytics/
│
├── netflix_dashboard.twb         # Tableau packaged workbook
├── netflix_titles.csv            # Raw dataset
|
├── images/
│ └── dashboard_overview.png      # Dashboard preview
|
└── README.md                     # Project background and overview
```

---

This repo demonstrates a **complete analytics workflow**:  
**data extraction → data preparation → analysis → data visualization**
