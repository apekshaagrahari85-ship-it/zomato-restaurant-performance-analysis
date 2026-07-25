# Zomato Bangalore Restaurant Performance Analysis

SQL-based analysis of ~51,000 Bangalore restaurants listed on Zomato, exploring 
rating patterns, pricing tiers, and customer engagement.

## Tools Used
- Python (pandas) — data cleaning
- SQLite (SQL) — querying and aggregation
- Google Colab — analysis environment

## Dataset
Zomato Bangalore Restaurants dataset (Kaggle)

## Key Insights
1. Multi-cuisine restaurants dominate top ratings over single-cuisine spots.
2. Higher-priced restaurants rate consistently better (Luxury 4.16 vs Budget 3.56).
3. Koramangala and Indiranagar are Bangalore's top-performing dining hubs.
4. Online ordering is now standard (27k+ restaurants) and doesn't hurt ratings.
5. Table-booking restaurants rate half a point higher and get 5x more engagement — 
   these tend to be more established venues.
6. Byg Brewski Brewing Company leads as top performer by weighted score.

## Process
Raw data was cleaned in pandas (fixed rating format, removed cost formatting issues, 
deduplicated records), loaded into a SQLite database, and analyzed using SQL queries 
covering aggregation, grouping, subqueries, and weighted ranking.
