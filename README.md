# IPL Data Cleaning and Visualization Project

## Overview

This project focuses on cleaning, preprocessing, and visualizing historical Indian Premier League (IPL) match data using Python. The goal of the project is to transform raw IPL data into meaningful insights through data cleaning techniques and graphical visualizations. Various charts and graphs were generated to analyze team performance, match trends, toss decisions, venue popularity, and winning margins.

The project demonstrates the practical application of Data Analytics concepts, including data preprocessing, exploratory data analysis (EDA), and data visualization using Python libraries.

---

## Objectives

- Load and analyze IPL match data.
- Identify and handle missing values.
- Remove duplicate records.
- Perform data cleaning and preprocessing.
- Create meaningful visualizations.
- Extract insights from historical IPL match data.

---

## Dataset Information

- **Dataset Name:** IPL Data Set
- **File Used:** `matches.csv`
- **Source:** Kaggle IPL Dataset

### Key Features
- Season
- City
- Team1
- Team2
- Toss Winner
- Toss Decision
- Winner
- Venue
- Win By Runs
- Win By Wickets
---

## Technologies Used

- Python
- Google Colab
- Pandas
- NumPy
- Matplotlib
- Seaborn
---

## Data Cleaning Process

The following preprocessing steps were performed:

1. Loaded the IPL dataset using Pandas.
2. Inspected dataset structure and information.
3. Identified missing values.
4. Removed missing records.
5. Checked and removed duplicate entries.
6. Verified cleaned dataset dimensions.
7. Prepared data for visualization.

---

## Visualizations Generated

### 1. Dataset Preview
- Displayed initial records from the dataset.
<img width="879" height="982" alt="Screenshot 2026-06-18 155501" src="https://github.com/user-attachments/assets/a9c154b0-364e-4f37-89e4-1300f51b3e86" />


### 2. Missing Value Analysis
- Identified null values present in the dataset.
<img width="847" height="330" alt="Missing value analysis" src="https://github.com/user-attachments/assets/56020e7d-1082-40d0-acf7-1dac6232dc62" />


### 3. Matches Played Per Season
- Analyzed season-wise IPL match distribution.
<img width="842" height="559" alt="MATCHES PLAYED PER SEASON GRAPH" src="https://github.com/user-attachments/assets/c39b0d88-50ae-4041-84d7-c94f55f6f7b6" />


### 4. Top Winning Teams
- Visualized teams with the highest number of victories.
<img width="881" height="702" alt="most winning teams graph" src="https://github.com/user-attachments/assets/e35b47bb-941d-47cd-ab7c-61d176a1e8ac" />

### 5. Toss Decision Analysis
- Examined batting and fielding preferences after winning the toss.
<img width="451" height="403" alt="Pie chart for Toss Decisions" src="https://github.com/user-attachments/assets/937bc69c-08ce-4930-aedf-083a60c712ab" />

### 6. Winning Margins by Runs
- Visualized common victory margins achieved by runs.
  <img width="946" height="558" alt="Win by run Margin Bar Chart" src="https://github.com/user-attachments/assets/e9667ea5-8794-4abf-9a9f-e24d7277fc47" />


### 7. Winning Margins by Wickets
- Examined wicket-based victory distributions.
<img width="741" height="466" alt="Win by wicket margin bar" src="https://github.com/user-attachments/assets/f0a20cbe-e0da-42c5-a0a4-645e0a999852" />

### 8. Top IPL Venues
- Identified stadiums hosting the most IPL matches.
<img width="1343" height="730" alt="TOP IPL VENUES" src="https://github.com/user-attachments/assets/2b4a89d2-07c1-4b25-834f-db20a459405a" />

---

## Key Insights

- Mumbai Indians and Chennai Super Kings are among the most successful IPL teams.
- Most teams prefer fielding after winning the toss.
- Certain venues host a significantly larger number of matches.
- Winning margins vary across IPL matches, indicating diverse match competitiveness.
- Historical IPL data contains valuable patterns useful for sports analytics.

---

## Applications

- Sports Analytics
- Cricket Performance Analysis
- Exploratory Data Analysis
- Data Visualization Practice
- Data Science Learning Projects

---

## Project Structure

```text
IPL-Data-Cleaning-and-Visualization
│
├── matches.csv
├── IPL_Data_Cleaning_Visualization.ipynb
├── Report.pdf
├── screenshots/
│   ├── dataset_preview.png
│   ├── missing_values.png
│   ├── matches_per_season.png
│   ├── top_winning_teams.png
│   ├── toss_decision.png
│   ├── winning_margin_runs.png
│   ├── winning_margin_wickets.png
│   ├── top_venues.png
└── README.md
```
---

## Results

The project successfully cleaned and analyzed IPL match data and generated multiple visualizations to identify trends, patterns, and insights. The findings demonstrate the importance of data cleaning and visualization in transforming raw datasets into meaningful information for decision-making and analysis.

---

## Conclusion

This project successfully applied data cleaning and visualization techniques to IPL match data. Through preprocessing and exploratory analysis, meaningful insights regarding team performance, toss strategies, venue popularity, and match outcomes were discovered. The project highlights the practical use of Python-based analytics tools for understanding and interpreting sports data.

---

## References

- Kaggle IPL Dataset
- Pandas Documentation
- Matplotlib Documentation
- Seaborn Documentation
- Python Official Documentation

---

### Author

**Devesh Roy**  
B.Tech – Data Science  
Dayananda Sagar Academy of Technology and Management (DSATM)
