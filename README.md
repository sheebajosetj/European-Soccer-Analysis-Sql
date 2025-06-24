# Eupropean-Soccer-Analysis-Sql


This project explores the European Soccer Database using SQL queries via a Python environment (Pandas + SQLite). It analyzes match results, player data, team performance, and more, spanning the seasons from 2008/2009 to 2015/2016.

# Project Description
The dataset includes:
25,000+ matches
10,000+ players
11 countries with their top leagues
Team lineups, match stats, betting odds, and player attributes
This project demonstrates how to use SQL for data exploration within a Python notebook, using clear queries and joins to answer real-world football questions.

# Key Insights
Countries & Leagues: Extracted all participating countries and linked each to its league (e.g., Spain → Spain LIGA BBVA).
Match Analysis: Retrieved detailed match info including teams and goal stats by season.
Team Performance:
Total and average goals scored per team
Top goal-scoring teams like FC Barcelona and Real Madrid
Player Attributes:
Tallest player: Kristof van Hout (208.28 cm)
Lowest weight: Juan Quero
Average player weight: 168.38 lbs
CASE Statements:
Custom outcome logic for Tottenham Hotspur matches (Win/Loss/Tie)
Goal summaries by season

# SQL Concepts Covered
Basic SELECT, WHERE, and ORDER BY
Aggregation with COUNT, SUM, AVG
JOINs (INNER and LEFT)
GROUP BY and HAVING
Subqueries
CASE WHEN for conditional logic
Filtering NULLs and pattern matching with LIKE

# Tables Used
Match – Core match-level data
Player and Player_Attributes – Player metadata
Team and Team_Attributes – Team metadata
League, Country – Contextual tables for regions and competitions

# Purpose
To demonstrate how relational data stored in SQLite can be queried using SQL and interpreted for sports analytics. This is helpful for anyone learning SQL, working with relational data, or interested in football data exploration.
