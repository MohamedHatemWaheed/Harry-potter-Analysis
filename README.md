# 🧙‍♂️ Harry Potter Analysis — Power BI Dashboard

## 📌 Project Overview

This project is an interactive Power BI dashboard that analyzes various dimensions of the Harry Potter universe, including movies, chapters, characters, houses, magical species, and traits like the Patronus. The aim is to generate valuable insights and patterns from the data using advanced data modeling and visualization techniques.

---

## 🔄 Data Preparation & Modeling

### 📂 Data Collection

The data was originally scattered across multiple Excel sheets. I consolidated them into a single master file for streamlined analysis.

### 🧱 Data Modeling

- Established relationships using **Primary Keys (PK)** and **Foreign Keys (FK)** to link:
  - Characters ↔ Houses
  - Movies ↔ Chapters
  - Characters ↔ Patronus

### 🧹 Data Cleaning

- Standardized categorical values (e.g., gender, species, house).
- Addressed missing data with placeholders like “unknown” or “doesn't have”.
- Created new columns for analysis such as binary flags for Patronus presence.
- Used Power Query and DAX to clean, transform, and model the data.

### 🔍 Data Exploration

- Investigated data patterns to uncover inconsistencies and hidden trends.
- Cleaned duplicates and corrected relationships between entities.

---

## 🧭 Report Navigation

The dashboard contains three main sections:

- **🏠 Home Page**
- **🎬 Movies & Chapters**
- **🧙 Characters & Houses**

---

## 📊 Dashboard Pages Explained

### 🏠 Home Page

A welcoming interface designed with a magical theme, containing navigation buttons to explore:
- Movie & Chapters
- Characters & Houses

---

### 🎬 Movies & Chapters

#### 📈 Financial Overview

**Chart Type:** Combo chart (bar + line)

- **Bars**: Revenue, Profit
- **Line**: Budget

**Insights**:
- **Deathly Hallows Part 2** had the highest revenue and profit.
- Strong financial performance across early movies like *Philosopher's Stone*.

#### 📘 Chapter Count by Movie

**Chart Type:** Bar chart

- Visualizes how many book chapters each movie covered.

**Insights**:
- *Chamber of Secrets* and *Philosopher’s Stone* have the most chapter coverage.
- Later movies were more focused, covering fewer chapters.

#### 🎯 KPIs

- **Total Runtime**: `1179 min`
- **Longest Runtime**: `161 min`
- **Shortest Runtime**: `130 min`
- **Total Profit**: `6B`
- **Highest Profit**: `1B`
- **Lowest Profit**: `667M`

#### 🎚️ Filter

- **Release Year Slider**: Filter movies from 2001 to 2011.

---

### 🧙 Characters & Houses

#### 🏠 Character Distribution by House

**Chart Type:** Bar chart

**Insights**:
- *Gryffindor* is the most attended known house.
- Many characters are marked as “unknown” for house affiliation.

#### 👽 Species Count

**Chart Type:** Bar chart

**Insights**:
- Most characters are *human*.
- Non-human characters (Ghosts, Centaurs, etc.) reflect the fantasy aspect.

#### 🪄 Patronus Distribution

**Chart Type:** Donut chart

**Insights**:
- Only `12.05%` of characters have a Patronus.
- `87.95%` do not, highlighting its rarity.

#### 👥 Gender Distribution

**Chart Type:** Donut chart

- **Male**: 49.7%
- **Female**: 25.45%
- **Unknown**: 18.18%
- **Beast**: 6.67%

**Insights**:
- Fair gender balance.
- A notable portion of entries are unknown or classified as magical beasts.

---

## 🔍 Key Insights Summary

| Topic               | Insight                                                                 |
|--------------------|-------------------------------------------------------------------------|
| Top-Earning Movie  | `Deathly Hallows Part 2` (~£1B profit)                                  |
| House Affiliation  | `Gryffindor` dominates known house data                                 |
| Patronus Ownership | Only `12%` of characters have a known Patronus                         |
| Gender Balance     | Close male/female ratio with 25% “unknown” classification              |
| Species            | Mostly `human`, followed by unknown and magical creatures              |
| Chapter Density    | First two movies covered more chapters; final ones are more focused    |

---

## 🛠 Tools Used

- **Power BI Desktop**
- **Power Query (M language)**
- **DAX** (for calculated columns and KPIs)
- **Excel** (for data staging and integration)
- **Custom visuals and themes** to match the magical aesthetic

---

## 🚀 View the Live Power BI Dashboard

[![View Report](https://img.shields.io/badge/View%20Dashboard-Power%20BI-yellow?style=for-the-badge&logo=powerbi)](https://app.powerbi.com/groups/me/reports/fc83eba5-74fc-4961-926c-8ffd2c0ebf5f/09ae4f4777c09138ee20?experience=power-bi)

Click the button above to explore the interactive dashboard online.

---

## 👋 Final Thoughts

This project merges data storytelling with fantasy, offering a unique analytics experience. It’s designed to inspire fans and analysts alike to explore structured data through a creative lens.

