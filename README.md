# IPL Analysis 

## Title Page
**Project Title**: IPL Power BI Dashboard  
**Subtitle**: Interactive Insights on Teams, Players, and Fantasy XI  
**Authors**: Suman & Nikhil  
**Date**: April, 2025  
**Live Dashboard Link**: [Check out here](https://app.powerbi.com/view?r=eyJrIjoiYjIxZTBjNjAtNmZhOS00YTQyLWEwMDItM2FlZjAwZGEzY2VjIiwidCI6ImM2ZTU0OWIzLTVmNDUtNDAzMi1hYWU5LWQ0MjQ0ZGM1YjJjNCJ9)

---

## Table of Contents
1. [Project Overview](#project-overview)  
2. [Problem Statement](#problem-statement)  
3. [Objectives](#objectives)  
4. [Datasets Used](#datasets-used)  
5. [Data Modeling](#data-modeling)  
6. [Dashboard Overview](#dashboard-overview)  
7. [Power BI Techniques Learned](#power-bi-techniques-learned)  
8. [Key Metrics and Visuals](#key-metrics-and-visuals)  
9. [Challenges and Learnings](#challenges-and-learnings)  
10. [Conclusion](#conclusion)  

---

## Project Overview
This IPL Power BI Dashboard project was built as part of the Resume Project Challenge by Codebasics. The goal was to analyze Indian Premier League (IPL) performance data to derive player insights, team analysis, and generate a fantasy XI recommendation.

---

## Problem Statement
Cricket fans and analysts often face difficulty accessing clean, interactive data for player and team performance analysis. This dashboard bridges that gap with a visually rich, dynamic solution built using Power BI.

---

## Objectives
- Build an interactive Power BI dashboard to explore IPL insights.  
- Analyze team and player-level performance.  
- Visualize key metrics like runs, wickets, strike rates, and economy.  
- Enable fantasy XI selection using data-driven decisions.  

---

## Datasets Used

### Source Files
- `dim_players.csv`  
- `dim_match_summary.csv`  
- `fact_batting_summary.csv`  
- `fact_bowling_summary.csv`  
- `Teams_logo.xlsx`  

---

## Data Modeling
- Snowflake schema model using Player, Team, and Match dimensions.  
- Relationships established via PlayerID, TeamID, and MatchID.  
- Cleaned and transformed using Power Query before modeling.  

![Data Model](https://github.com/sumanju333/IPL-Analysis/blob/main/Data%20Model.png)
---

## Dashboard Overview

![Dashboard](https://github.com/sumanju333/IPL-Analysis/blob/main/IPL%20Dashboard.png)

The Power BI dashboard consists of five key pages:

1. **Overview Page**: Tournament summary with total matches, runs, and wickets.
 
![Overview](https://github.com/sumanju333/IPL-Analysis/blob/main/Overview%20Page.jpeg)
 
2. **Individual Player Page**: Player-level performance with scroller and dynamic image.  

![Player Page](https://github.com/sumanju333/IPL-Analysis/blob/main/Player%20Performance.jpeg)

3. **Top Players Page**: Top 5 batsmen, bowlers, and allrounders with tooltips.  

![Top Players](https://github.com/sumanju333/IPL-Analysis/blob/main/Top%20Players.jpeg)

4. **Team Performance Page**: Win/loss breakdown, win % and dynamic team logo.  

![Team Performance](https://github.com/sumanju333/IPL-Analysis/blob/main/Team%20Performance.jpeg)

5. **Fantasy XI Page**: Data-driven team selection categorized by roles.  

![Fantasy 11](https://github.com/sumanju333/IPL-Analysis/blob/main/Fantasy%2011.jpeg)


---

## Power BI Techniques Learned
- Using dynamic image URLs in visuals.  
- Implementing tooltip pages based on hover context.  
- DAX measures for Top N filtering using RANKX.  
- Power Query transformations and text manipulation.  
- Scroller visual for enhanced UX.  
- Slicer interactions and dynamic titles.  
- Optimizing Snowflake schema and cleaning raw cricket data.  

---

## Key Metrics and Visuals
- Total Runs, Wickets, and Matches.  
- Player Batting: Strike Rate, 4s, 6s, 100s, 50s.  
- Bowling: Economy Rate, Dot Ball %, Most Wickets.  
- Team Stats: Matches Played, Wins, Losses, Win Ratio.  
- Fantasy XI stats grouped by player role.  

---

## Challenges and Learnings

### Challenges:
- Getting tooltips to show the correct player context.  
- Filtering Top 5 players correctly across visuals.  
- Aligning team logos and player images dynamically.  

### Learnings:
- Importance of clean column formatting for visuals.  
- Deep DAX learning to drive dynamic visuals.  
- How slicer context affects visual results.  

---

## Conclusion

This dashboard allows cricket analysts and fans to interactively explore IPL stats with ease, compare players, and build a fantasy team with confidence.

---

## Tools Used
- Power BI Desktop  
- Microsoft Excel  
- DAX  
- Power Query  
- Canva (for mockups, if used)  
