
# ds4002_project1

Project 1 github repository for DS 4002 group 16

## Contents

Sentiment analysis of the "grit" of high school recruits for the UVA football team. Comparison of established "gritty" players provided by the UVA coaching staff to sentiment scores of recruits.

## Software and Platform

The software used in this project includes Google Collab and python, along with the python packages Tweepy and VADER. ChatGPT was used to help generate code and the X API free plan was used to extract data. This project was conducted on Mac and Windows platforms.

## Map

### LICENSE: 

MIT License dictating how this data and analysis can be used.

### SCRIPTS:

1_Data_Extraction_script: Script used to extract data using the free X API, with placeholders for unqiue user's bearer token provided by X.

2_EDA_script: Script used to conduct exploratory data analysis and discern trends within the player data.

3_VADER_script: Script used to perform sentiment analysis, returning a sentiment score for each tweet extracted.

4_Stat_script: Script used to conduct statistical analysis of the VADER scores, including a t-test and an ANOVA analysis.

### DATA

Recruit_names: List of recruits as provided by UVA football team

Established_names: List of established players as provided by UVA football team

Recruit_data: Data on each high school recruit, including X username, player name, XOS star rating, hometown, and tweet.

Established_data: Data on established "gritty" players, including X username, player name, and tweet.

VADER_scores: Database with VADER scores achieved from sentiment analysis.

### OUTPUT

VADER_scores: Composite seniment scores obtained through the VADER_script

STAT_results: Results of statistical tests ran

## Reproducing Results

To replicate results from this project, begin by extracting data using the free X API and the 1_Data_Extraction script. Replace the bearer_token variable with unique bearer token in the X Developer profile. Generate recruit data for high school recruits using the usernames provided in the Recruit_names data file. Generate established data for established gritty players using the usernames provided in the Established_names data file. The tweets pulled from X should be copied into the file containing additional user information, as seen in the Recruit_data and Established_data files. Perform exploratory data analysis on this data using the EDA_script and find trends.

Once the database of tweets is established, VADER sentiment analysis can be performed using the VADER_script. Load the Recruit_data and Established_data into the VADER_script and save the results as the VADER_scores csv. 


