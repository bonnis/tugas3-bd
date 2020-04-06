# Knime Movie Recommendation

## Business Understanding
In this workflow sample, we are given data of movie ratings. This data can be further processed for prediction. In this sample, we use the data to predict movie recommendation based on user ratings.

## Data Understanding
The data is consisted of six .csv files that act as tables that refer to each other using foreign keys. These tables with their each attributes are listed as follows :  
1. Tag
   - userId
   - movieId
   - tag
   - timestamp
2. Rating
   - userId
   - movieId
   - rating
   - timestamp
3. Movie
   - movieId
   - title
   - genres
4. Link
   - movieId
   - imdbId
   - tmbdId
5. Genome Score
   - movieId
   - tagId
   - relevance
6. Genome Tag
   - tagId
   - tag

## Data Preparation
