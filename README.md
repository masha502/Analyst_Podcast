# Podcast Listening Records Analysis

## Introduction
This project aims to analyze podcast listening logs to understand user behavior and preferences. Through this analysis, we seek to identify the types of content users follow, as well as the countries they reside in. This information will help us provide personalized podcast recommendations that align with user interests.

## Project Goals
- **Understand User Behavior**: Analyze data to comprehend user preferences.
- **Identify Trending Content**: Discover the most popular podcast types in different regions.
- **Provide Personalized Recommendations**: Develop suggestions for podcasts based on user interests.

## Analysis Steps

### 1. Data Reading and Processing
- Read data from CSV and JSON files.
- Explore the data and understand its dimensions.
- Check for missing or outlier values.

### 2. Data Analysis
- Analyze the distribution of age, gender, and city among users.
- Explore episode categories and listening durations.
- Use aggregated data to provide insights into user behavior.

### 3. Generate Initial Recommendations
- Develop two functions to provide personalized recommendations based on users' previous listening:
  - **First Function**: Based on the user's preferred categories.
  - **Second Function**: Takes into account the popularity of global episodes.

## Outputs
- Graphs showing user distribution by gender and country.
- Analysis of average listening duration by gender.
- Personalized podcast recommendations based on user interests.

## Requirements
- Python 3.10
- Libraries: `pandas`, `matplotlib`, `seaborn`, `plotly`

## How to Use
1. Ensure the required libraries are installed.
2. Load the data into the appropriate CSV and JSON files.
3. Run the script to analyze the data and generate recommendations.

## Notes
- The model can be improved by adding more data or enhancing the recommendation algorithms.
- Natural Language Processing (NLP) can be utilized in the future to analyze the textual content of episodes.



---


