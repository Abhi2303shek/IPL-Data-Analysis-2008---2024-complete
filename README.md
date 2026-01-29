# IPL-Data-Analysis-2008---2024-complete
This Repository contains IPL dataset of match-wise results (Each match from 2008 First match to Final of 2024). And also one datset of delivery wise results of the match [both downloaded from Kaggle]. I have analysed both and found some interesting details . I am uploading just the gist and the main juice is with me and only request purpose.

Link to the dataset -- https://www.kaggle.com/datasets/patrickb1912/ipl-complete-dataset-20082020

# 🏏 Indian Premier League (IPL) Data Analysis (2008–2024)

# 📌 Project Overview
This project performs an end-to-end **data cleaning, analysis, and insight generation** on the **(IPL)** dataset covering seasons from **2008 to 2024**.

The analysis combines **match-level data** and **ball-by-ball (delivery-level) data** to uncover team strategies, player performance trends, and match outcome patterns using **Python**, **Pandas**and **Power BI**.

I have chosen this because **India Loves Cricket**. 

---

# 🎯 Objectives
- Clean and validate large, multi-level cricket datasets
- Analysed match outcomes, team dominance, and season trends
- Performed ball-by-ball analysis (powerplay, death overs, etc.)
- Generated actionable insights using Python, Pandas and Power BI dashboards

---

# 🗂 Dataset Description

## 1️⃣ Match-wise Dataset
- Granularity: **One row per match**
- Key attributes:
  - Season, venue, teams, city
  - Toss winner & decision, match type(league, qualifier, eliminator, playoff or final)
  - Match winner
  - Result type (runs / wickets / no result) and result_margin
  - umpires, method

## 2️⃣ Delivery-wise Dataset
- Granularity: **One row per ball**
- Key attributes:
  - Inning, betting team, bowling team
  - Batsman, bowler, runs
  - Extras, wickets, extras type and wicket type
  - Over & ball number

📌 This dual-granularity structure enables **high-detail performance analysis**.

## 🛠 Tools & Technologies
- **Python**
  - Pandas
  - NumPy
- **Power BI**
  - Interactive dashboards
  - DAX measures
- **Jupyter Notebook**

---

## 🔧 Data Cleaning & Preparation
Key steps performed:

- Standardised team and venue names
- Handled Season variables and dates
- Handled missing and inconsistent match results
- Validated ball-by-ball records
- Removed redundant columns
- Created derived metrics:
  - Run rate
  - Wickets per match
  - Powerplay & death over performance
  - Strike rate of players is dependent on balls faced.
  - Best economical bowlers

## 📊 Power BI Dashboards (Screenshots)

> Note: Dashboards were created using Power BI Desktop.  
> Interactive sharing is unavailable due to trial version limitations.

### 🔹 Match Overview Dashboard
- Matches per season
- Team-wise win distribution
- Toss decision impact

### 🔹 Team Performance Analysis
- Season-wise dominance of teams
- Home vs away performance
- Win percentage trends

### 🔹 Player & Phase Analysis
- Top run scorers and wicket takers
- Powerplay vs death over efficiency
- Player consistency across seasons

(Screenshots available in `/output/`)

---

## 📈 Key Insights

- Teams winning the toss and choosing to **chase** have a higher win percentage in most seasons
- **Powerplay overs** contribute disproportionately to match momentum
- Certain teams show strong dominance during specific eras
- Death overs have significantly higher run rates but also higher wicket probability\
- Also found Closer Index (who helped the team win the match more)
- And Anchor Index(who can anchor the innings from any situation)
- And also found the compatibility/ difficulty of batters for various type of bowlers(right arm pacer/ left arm or anything else)

---

## 📁 Project Structure
  - IPL(2008-24) Dataset(Git)
      - Notebooks
          - Delivery Ball IPL.ipynb
          - IPLMatch.ipynb
      - Output
          - Screenshots (0-4)
          - IPL PPT.pptx (PowerPoint Presentation file to show working)
