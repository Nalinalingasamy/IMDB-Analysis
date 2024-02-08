# IMDB-Analysis
## IMDB Movie Analysis With PowerBI
## Introduction: 
   The IMDB Movie Analysis Project aims to explore the factors influencing the success of movies on IMDB, focusing on their ratings. By analysing a dataset containing information about various movies, including genres, directors, budgets, durations, and languages, the project seeks to provide insights that can guide stakeholders in the film industry, such as producers, directors, and investors, in making informed decisions for future projects. 
 
## Problem statement: 
The primary problem addressed in this project is understanding what factors contribute to a movie's success on IMDB, particularly in terms of high ratings. The project seeks to uncover the relationships between different variables such as movie genres, durations, languages, directors, and budgets, and their impact on IMDB scores. 
The analysis conducted in this project holds significant implications for stakeholders in the film industry. Understanding the factors influencing a movie's success can help producers and directors make strategic decisions in various aspects of filmmaking, including genre selection, budget allocation, and directorial choices. Investors can also use these insights to assess the potential profitability of investing in specific movie projects. 
 
## Data cleaning and Pre-processing:
Dataset was loaded in Jupyter notebook.

Null values and datatypes where checked for all columns in the dataset. 

For various numerical columns in the data, distribution plot was made by importing seaborn library.

If the distribution was normal, null values were replaced with mean of the particular column. If it is not normal, null values were replaced with median of the particular column. 

For columns like Actor’s name, Director’s name, null values were filled with “Not specified” string. 

Some of the column’s null values were filled with mode of the particular column. 

The column “genres” contains many categories separated by “|”. It was splitted using string split method and splitted categories were exploded into separate rows. 

The genres list was further grouped based on IMBD score and its mean, median, mode, max, min, standard deviation, variance was calculated.

The treated data frame was then saved as an excel file and loaded into PowerBI. 

## DATASET LINK:

https://drive.google.com/file/d/1bXz_ksbuLRFP9wDZBE53MyeQi2Ko54PI/view?usp=sharing
