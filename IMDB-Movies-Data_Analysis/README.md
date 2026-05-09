# 🎬 IMDb Movies Data Analysis

## 📌 Overview

An end-to-end analytical exploration of the IMDb movie dataset to quantify the evolution of global cinema and television. This project tracks production volume, genre dominance, and the shift between family-friendly and adult-oriented content from the early 1900s through the digital and streaming eras.

---

# ⚙️ Workflow

## 📥 Ingest

Load the raw IMDb dataset containing titles, ratings, genres, and certification details.

## 🧹 Data Cleaning

* Standardized movie names
* Converted durations into integer format
* Cleaned vote counts for numerical analysis
* Handled missing and inconsistent values

## 🕒 Temporal Parsing

Utilized Regular Expressions (Regex) to extract:

* `start_year`
* `end_year`

from complex string formats to distinguish between:

* standalone movies
* multi-year television series

## 🧩 Identity Mapping

* Harmonized Director and Star IDs/Names
* Managed `Anonymous` entries
* Exported cleaned mappings into JSON format for external use

## 📈 Industry Trend Mapping

Visualized year-over-year growth of content production, identifying:

* 1950s industry expansion
* post-2000 content boom
* post-2020 contraction trends

## 🎥 Format Comparison

Compared production trajectories between:

* Movies
* TV Series

to analyze how digital platforms and streaming ecosystems influenced format preferences.

## 🎭 Dynamic Genre Analysis

Generated animated bar chart races to track the rise and fall of genre popularity across more than a century of cinema.

Genres analyzed include:

* Drama
* Comedy
* Documentary
* Action
* Romance
* Thriller

## 👥 Audience Segmentation

Categorized global certifications into three major audience groups:

* Kids
* Family
* Adult

This helped analyze long-term shifts in audience targeting strategies.

---

# 🔍 Key Insights

## 🚀 The 21st Century Content Explosion

Content production accelerated dramatically after 2000, peaking between 2015–2019 before showing a visible contraction after 2020.

## 🎬 Movie Dominance

Although TV Series experienced major growth during the Television Era (1960–1989), standalone movies still dominate total content volume.

## 📊 Genre Evolution

Drama and Comedy maintained long-term dominance, while niche genres expanded rapidly during the digital streaming era.

## 🔞 Rise of Adult-Oriented Content

Adult-focused certifications (`R`, `TV-MA`, etc.) experienced strong growth in both:

* production volume
* audience engagement

since the mid-20th century.

## 📢 Audience Engagement Patterns

While Kids and Family content maintained stable production levels, Adult and Family categories frequently generated the highest audience voting activity.

---

# 🛠️ Tech Stack

* Python
* Pandas
* NumPy
* Regular Expressions (Regex)
* Plotly Graph Objects
* Jupyter Notebook

---

# 📊 Skills Demonstrated

* Data Cleaning & Preprocessing
* Exploratory Data Analysis (EDA)
* Temporal Data Analysis
* Feature Engineering
* Regex-based Parsing
* Data Visualization
* Trend Analysis
* Audience Segmentation
* Analytical Storytelling

---


---

# ✅ Conclusion

This project demonstrates how data analytics can uncover long-term shifts in entertainment consumption, production strategies, and audience behavior across more than a century of global cinema and television history.

The analysis combines:

* structured data cleaning
* historical trend analysis
* audience segmentation
* interactive visualization

to transform raw IMDb data into actionable storytelling insights.

