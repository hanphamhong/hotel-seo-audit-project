# Hotel Google Business Profile Sentiment Audit

This project is a data-driven audit of five hotel Google Business Profiles, combining sentiment analysis of guest reviews and listing optimization insights. The goal is to identify service gaps, improve online visibility, and enhance local SEO performance through technical and content-based strategies.

## Project Overview

- **Audit Focus:** Google Business Profile (GBP) data for 5 major hotel brands
- **Techniques Used:** Sentiment analysis, citation audit, TF-IDF word cloud, and simulated listing issue resolution tracking
- **Goal:** Improve Local Pack visibility by resolving inconsistencies and analyzing review trends

## Key Features

- Applied sentiment analysis to 500+ guest reviews using VADER
- Identified NAP (Name-Address-Phone) inconsistencies and content gaps
- Simulated listing updates and tracked fixes using a Salesforce-modeled ticketing workflow
- Generated word clouds with TF-IDF to extract brand-specific guest concerns
- Normalized sentiment comparisons across hotel brands

## Tools & Technologies

- Python (pandas, nltk, matplotlib, seaborn, wordcloud)
- VADER Sentiment Analyzer
- Jupyter Notebook
- Google Maps data (scraped via manual collection)

## 📁 Files

| File | Description |
|------|-------------|
| `sentiment_analysis_50.ipynb` | Main notebook with data cleaning, analysis, and visualizations |
| `review_scrape_50.csv`        | Anonymized review data for sentiment analysis |
| `figures/`                    | Folder containing saved plots and word clouds |
