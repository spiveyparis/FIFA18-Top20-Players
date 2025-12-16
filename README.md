# FIFA 18: Top 20 Player Performance Analysis

This project analyzes a dataset of **17,981 FIFA 18 players** to identify and visualize the **top 20 highest-rated players** in the game. The goal of this project was to demonstrate the full data analytics process — from raw data extraction and cleaning to ranking and visualization.

---

## Project Overview

Starting with a raw FIFA 18 player dataset extracted from a **PDF source**, the data was cleaned, structured, and analyzed using SQL. The final output highlights the **top 20 players by overall rating**, along with the **clubs they play for** and their **nationalities**.

The cleaned and ranked data was then visualized in Tableau to provide clear, interactive insights into:
- The highest-rated players in FIFA 18
- Which clubs produced the most top-rated players
- The distribution of top talent across clubs and countries

---

## Data Preparation & Extraction Process

1. **Raw Data Source**
   - FIFA 18 player data containing **17,981 players**
   - Original format: PDF

2. **Data Cleaning**
   - Extracted player data from the PDF into a structured format
   - Removed formatting issues and inconsistencies
   - Standardized column fields for:
     - Player Name
     - Nationality
     - Club
     - Overall Rating

3. **SQL Analysis & Ranking**
   - Loaded the cleaned data into an Oracle SQL database
   - Used SQL queries to:
     - Sort players by overall rating
     - Rank players from highest to lowest
     - Extract the **top 20 players** based on overall rating
   - Selected only the relevant fields:
     - Player Name
     - Nationality
     - Club
     - Overall

4. **Export for Visualization**
   - Exported the final ranked dataset as a CSV file
   - Imported the CSV into Tableau for visualization

---

## Visualization & Insights

The Tableau dashboard presents:
- A ranked bar chart of the **Top 20 FIFA 18 Players**
- Club-level insights showing which teams host the most elite players
- Interactive filtering by club and nationality

---

## Tools & Technologies

- **Oracle SQL** – Data storage, ranking, and filtering
- **Tableau** – Data visualization and dashboard creation
- **CSV** – Data transfer between SQL and Tableau
- **GitHub** – Project version control and sharing

---

## Key Takeaways

- The analysis demonstrates how raw, unstructured data can be transformed into actionable insights
- Club dominance can be quickly identified by the number of top-rated players they host
- Ranking and filtering large datasets using SQL enables efficient and scalable analysis

---

## Files in This Repository

- `fifa18_player_rankings.csv` – Cleaned and ranked top 20 player dataset
- `FIFA18_Top20_Players.twbx` – Tableau packaged workbook with interactive visuals

---


