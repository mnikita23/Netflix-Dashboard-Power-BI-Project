# 🎬 Netflix Dashboard – Power BI Project

An interactive dashboard built in Power BI to visualize and analyze Netflix’s global content from a CSV dataset.

## 📌 Project Overview

This project transforms a raw dataset of Netflix titles into an insightful and interactive dashboard using **Power BI Desktop**.

Key goals:
- Explore how content is distributed across the globe.
- Understand the balance between Movies and TV Shows.
- Identify trends over time in content production.
- Enable filtering by country, year, genre, and type.

## 📊 Dashboard Features

- **📍 Map of Content by Country**  
  Interactive map showing how many titles are available per country.

- **🧾 Content Type Breakdown**  
  Pie chart comparing Movies vs TV Shows.

- **📅 Release Year Timeline**  
  Bar chart showing how many titles were released each year.

- **📂 Genre/Category Filter**  
  Bar or stacked visuals to view dominant genres over time.

- **🎛️ Filters/Slicers**  
  Users can interactively slice data by:
  - Actors
  - Country
  - Director
  - IMDB Score
  - Genre
  - Languages
  - Title
  - View Rating

## 🛠 Tools & Skills Used

- **Power BI Desktop**
- **Power Query** for data transformation
- **DAX** for calculated columns and measures
- **Data Modeling** to relate tables (if multiple datasets used)
- **Dashboard Design** best practices for clarity and interaction


## ⚙️ How It Works

1. **Data Import:**  
   Imported the Netflix CSV dataset into Power BI.

2. **Data Cleaning (Power Query):**
   - Removed rows with nulls or missing titles.
   - Split the “listed_in” column into individual genres (if required).
   - Standardized release year and country fields.

3. **Modeling:**
   - Created calculated columns for type count.
   - Used DAX measures for total content per country/year.

4. **Visualization:**
   - Built interactive visuals with built-in Power BI charts.
   - Applied slicers to allow deep filtering.

5. **Export:**  
   - Saved the report as `.pbix` (Power BI project file).
  

## 📂 File Included

- `Netflix Dashboard.pbix` – Power BI dashboard file
- `netflix_titles.csv` – Original dataset
