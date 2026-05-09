# ODI-Cricket-Database-System
A relational database system designed to manage and analyze One Day International (ODI) cricket match data spanning 1992–2023.

## **What I Built**

Designed a full Entity-Relationship (ER) model with 16 entities including strong, weak, and supertype/subtype entities (Player → Batsman, Bowler, All-Rounder; Official → Umpire, Referee)
Mapped the ER model to a normalized relational schema of 20 tables with proper primary keys, foreign keys, and CHECK constraints
Implemented the database in MySQL with 725 rows of real cricket data sourced from Kaggle
Wrote 13 SQL queries covering player stats, bowling economy, partnerships, win percentages, toss analysis, and more
Built advanced features: 2 indexes, 2 views (career batting/bowling summaries), 2 stored procedures (player performance report, team win record), and a BEFORE INSERT trigger for bowling data validation
Connected the database to Python using mysql.connector to execute all queries and demonstrate INSERT, UPDATE, and DELETE operations programmatically

Author - Yashika Jethwani
