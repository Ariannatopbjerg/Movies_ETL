# Movies_ETL

## Project Purpose
Amazing Prime Video team wants to develop an algorithm to predict which low budget movies being released will become popular, so they can buy the streaming rights at a bargain. To inspire the team and connect with the local coding community, Amazing Prime has decided to sponsor a hackathon; providing a clean dataset of movie data and asking participants to predict the popular movies. To acquire this clean dataset of movie data, we must make it.

This project will be creating an automated pipeline that takes in new data from Wikipedia data, Kaggle metadata, and the MovieLens rating data. Then it will perform the appropriate transformations and loads the data into a PostgreSQL database. 

## Project Breakdown:
1) Write an ETL Function to Read Three Data Files
2) Extract and Transform the Wikipedia Data
3) Extract and Transform the Kaggle data
4) Create the Movie Database

## Summary
The ETL function that has been created, extracts, and cleans movie data from various sources ─ Wikipedia stored as a JSON, Kaggle (movie metadata), and ratings csv files. It transforms and merges the data as wanted and loads it into two PostgreSQL dataset tables. The tables are ready to be used by the hackathon participants for their movie analysis. 

