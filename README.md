# ATP 2024 Season Analysis

## Overview

This project analyzes the **ATP 2024 tennis season** using match-level data to explore player performance, match outcomes, and season-level trends.

The dataset used in this project is sourced from the well-known open tennis data repository maintained by Jeff Sackmann:

📊 **Dataset source:** [https://github.com/JeffSackmann/tennis_atp/tree/master](https://github.com/JeffSackmann/tennis_atp/tree/master)



The notebook is structured into the following logical sections:

### 1. Data Loading

* Loads ATP match data for the 2024 season from CSV files.
* Uses common Python data science libraries such as **pandas**, **numpy**, **matplotlib**, and **seaborn**.

### 2. Data Cleaning & Preprocessing

* Handles missing or inconsistent values.
* Converts data types (dates, numeric columns, categorical fields).
* Filters matches to focus specifically on ATP-level events.

### 3. Feature Engineering

* Extracts useful features such as:

  * Match duration
  * Player rankings and ranking differences
  * Surface type (hard, clay, grass)
* Creates derived metrics to better compare player performance.

### 4. Exploratory Data Analysis (EDA)

* Examines distributions of:

  * Match outcomes
  * Player rankings
  * Wins by surface
* Visualizes trends using plots and summary statistics.

### 5. Insights & Observations

* Identifies notable performance patterns during the 2024 season.
* Highlights relationships between ranking, surface, and match outcomes.

---



## Data Attribution

All tennis match data used in this analysis comes from the **Jeff Sackmann Tennis ATP dataset**, which is publicly available and widely used for tennis analytics and research:

[https://github.com/JeffSackmann/tennis_atp](https://github.com/JeffSackmann/tennis_atp)

---

## Notes

* This project is intended for educational and analytical purposes.
* The dataset is maintained independently; any data updates or corrections should be obtained directly from the source repository.

---

## Author

Analysis prepared as part of an exploratory study of the ATP 2024 season.
