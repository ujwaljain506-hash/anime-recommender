# Anime Recommendation System

A content-based anime recommendation system built using TF-IDF Vectorization 
and Cosine Similarity on a dataset of ~20,000 anime from MyAnimeList (2023).

## How It Works
1. Anime genres are cleaned and converted into TF-IDF vectors
2. Cosine similarity is calculated between all anime pairs
3. Given an anime title, the system returns the 10 most similar anime

## Tools Used
- Python (Google Colab)
- Pandas (data cleaning & EDA)
- Scikit-learn (TF-IDF Vectorization, Cosine Similarity)
- Matplotlib (visualizations)

## Key Insights
- Comedy is the most common anime genre (7,000+ anime)
- Most anime score between 6-7 on MyAnimeList (bell curve distribution)
- ~5,000 anime had UNKNOWN genres and were removed during cleaning
- Dataset contains ~20,000 anime after cleaning

## Example
Input: "Demon Slayer: Kimetsu no Yaiba"
Output: Top 10 similar anime based on genre patterns

## Project Structure
- `day1_loading_data.ipynb` - Loading and exploring the dataset
- `day2_tfidf_vectorization.ipynb` - Cleaning genres and TF-IDF vectorization
- `day3_recommendation_function.ipynb` - Building the recommendation function
- `day4_eda_insights.ipynb` - EDA insights and polished output
