# Using Hypothesis Testing to Determining Artist Popularity Differences by Genre

## Project Members:

**Data Scientists** - Daniel Torres & Max Tingle

**Flatiron School** - Data Science Fellowship Module 2 Project

## Project Goals:

Our analysis examines Spotify artist popularity differences by genre. We collected data from Spotify's Web API that included 53,244 artists, their genres, popularity score, and follower count. We confined the scope of this project to artists who exclusively fall within the pop, hip-hop, rock, or country genres.

Then we asked two research questions:
1) Do artists' popularity scores differ significantly by genre?
2) Do artists' follower counts differ significantly by genre?

For each question, we followed the same statistical approach for the popularity score and follower count metrics.
1. We took a sample from each genre. 
2. Performed an ANOVA test to determine whether the genre means are all equal.
3. Performed a Tukey's HSD (honestly significant difference) test to find genre means that are significantly different from eachother.
4. Performed Welch t-tests for each pairwise combination of the four selected genres to test whether the means are equal. (We included the Welch t-test to compare results with the Tukey test.)


## Repository Files:

*To dive into our analysis code, skip to the data_analysis_popularity_score.ipnby and data_analysis_follower_counts.ipnby Jupyter Notebooks.*

- **README.md:** repository overview document

- **data_collection.ipynb:** technical Jupyter Notebook that retrieves data from Spotify API

- **data_cleaning.ipynb:** technical Jupyter Notebook that cleans data from Spotify API

- **data_analysis_popularity_score.ipynb:** technical Jupyter Notebook performing statistical tests for popularity score by genre

- **data_analysis_follower_counts.ipynb:** technical Jupyter Notebook performing statistical tests for follower counts by genre

- **spotify_artist_popularity_differences_by_genre.pdf:** pdf presentation of results

- **data:** folder containing data

  - **spotify_artists.csv:** resulting csv from data collection notebook

  - **spotify_artists_cleaned.csv:** resulting csv from data cleaning notebook

- **python_files:** folder containing Python files

  - **data_cleaning.py:**

  - **hypothesis_tests.py:**

  - **visualizations.p:y**

- **images:** folder containing exported images from technical notebooks


## Responsibilities:

- Data Collection & Cleaning (Notebooks) - Daniel driving, Max navigating

- Data Analysis for Popularity Score (Notebook & Visualizations) - Daniel

- Data Analysis for Follower Counts (Notebook & Visualizations) - Max

- Spotify Artist Popularity Differences by Genre (PDF) - Max & Daniel
