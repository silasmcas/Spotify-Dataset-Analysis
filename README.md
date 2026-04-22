# Spotify Dataset Analysis & Exploration
Collaborators: Silas McAllister-Spooner, Manyu Ghildiyal, Craig Sirota, Simon T. Rubinstein

## Overview
This project explores a Spotify dataset containing approximately 232,000 samples and 18 features to analyze song features and listening patterns, to generate insights into music trends and user preferences. These features include musical characteristics, such as tempo and valence, as well as metadata attributes, such as artist and genre.

## Goals
- Analyze audio features (energy, danceability, valence, etc.)
- Explore correlations between song attributes and popularity
- Explore the relationship between artist brand equity and song success
- Generate actionable industry insights

## Dataset
Source: https://www.kaggle.com/datasets/zaheenhamidani/ultimate-spotify-tracks-db

## Tools Used
- Python
- Pandas
- NumPy
- Matplotlib / Seaborn
- Jupyter Notebook

## Key Insights
- Loudness is a top predictive feature
- Danceability correlates with audience engagement
- Vocal segments improve recall and memorability
- Feature based screening supports A&R decisions
- Arist brand recognition dominates popularity outcomes

## Future Improvements
- Expand dataset with temporal trends to analyze how features that drive popularity evolve over time
- Incorporate artist level and release strategy features (release timing, genre positioning)
- Build a predictive scoring tool for A&R decision-making
- Integrate playlist and streaming data to model distribution impact
- Develop a dashboard for label/artist insights
- Conduct further genre specific filtering of dataset to synthesize genre-specific insights
- Experiment further with popularity thresholds when filtering, filtering out the lowest performing artists as well
- Deploy as web app

## How to Run
```bash
pip install -r requirements.txt
