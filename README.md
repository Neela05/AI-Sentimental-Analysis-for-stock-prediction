# AI-Sentimental-Analysis-for-stock-prediction

## Overview
This project analyzes Reddit discussions about popular companies and uses sentiment analysis to estimate public opinion. The sentiment scores are then used to identify companies that may have positive or negative market sentiment.

## Features
- Collects Reddit posts using the Reddit API (PRAW)
- Performs sentiment analysis using VADER
- Calculates sentiment scores for each company
- Identifies top positive and negative companies
- Generates sentiment-based insights for stock prediction
- Supports word cloud visualization for sentiment trends

## Technologies Used
- Python
- PRAW (Reddit API)
- VADER Sentiment Analyzer
- Pandas
- Matplotlib
- WordCloud

## How It Works
1. Fetch Reddit posts related to selected companies.
2. Analyze the sentiment of each post using VADER.
3. Calculate average sentiment scores for each company.
4. Rank companies based on positive and negative sentiment.
5. Identify companies with strong positive sentiment that may have growth potential.

## Example Companies Analyzed
- Tesla
- Apple
- Google
- Microsoft
- Amazon
