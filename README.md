# Sentiment-Analysis-of-Drugs-Reviews
A  Pharmaceutical company has collected comments for various products scraping from various online sources and wish to create a sentiment analysis engine that can track the sentiment regarding a specified drugs from 3 categories namely positive negative and neutral. 

Every sample will contain the text mentioning a drug name and the comment pertaining to it. Multiple products could be there within a single comment.

# Data Description

## train.csv
Comments with actual labels

| Variable | Definition   | 
| :---:   | :---: |
| id | id |
| comment | text pertaining to the drugs |
| product | product name for which the sentiment is provided |
| sentiment | (Target) 0-positive, 1-negative, 2-neutral |

## test.csv
Expected to predict the sentiment for the products mentioned with comments in the test set

