# Movie Industry Analysis

## Introduction
In this project, we will focus on EDA or Exploratory Data Analysis in Python using pandas, numpy, matplotlib and seaborn libraries. We are going to observe, clean, and translate our findings to help Microsoft better understand the film industry and provide actionable insights so that the executives can use our recommendations to make decisions.


## The Dataset

Included in the repository (in the folder zippedData) is some movie-related data from:
1. Box Office Mojo
2. IMDB
3. Rotten Tomatoes
4. TheMovieDB.org

## Questions

There are hundreds of factors that can contribute to the success of a movie. The classical factors include producer, production house, director, cast, runtime of the movie, the genre, the script, time of release. 

In addition to the classical factors, there are a lot of social ones too. To name a few- the IMDb ratings, the viewer and critic reviews, the ongoing social, cultural, political and economic trends also are major deciding factors in the success of a film.

After exploring the given dataset, I decided to focus the following questions:

1. Which genres make the most profit?
2. When should we release our films?
3. Which director(s) should we hire?
4. Which studio are some of the biggest competitors?

## Results & Recommendations
Below are the final visualizations and recommendations I concluded based on my analysis. For more details, please see MovieIndustryAnalysis.ipynb.

1. What are the top 5 most profitable genres?
    - From the top 200 most profitable movies, Microsoft should invest in Adventure, Action, Sci-Fi, Animation, and Comedy movies
 ![](https://raw.githubusercontent.com/helenpham0229/Images/main/genres.png)

2. When is the best time to release movies?
    - Based on the line plot above, June, July, and November are the most profitable months to release movies.
![](https://raw.githubusercontent.com/helenpham0229/Images/main/release.png)

3. Who should we hire as director(s)?
    - Directors who directed 4 or more films would make positive net profit
![](https://raw.githubusercontent.com/helenpham0229/Images/main/filmdirected.png)
    - Out of those directors who led 4 or more movies, we shoud hire Joss Whedon, Christopher Nolan, and/or Jon Favreau.
![](https://raw.githubusercontent.com/helenpham0229/Images/main/directors.png)

4. Who are our biggest competitors?
    - From the top 50 most profitable films, BV (one of divisions and subsidiaries of The Walt Disney Company) and WB (an American diversified multinational mass media and entertainment conglomerate) are our biggest competitors
![](https://raw.githubusercontent.com/helenpham0229/Images/main/competitors.png)

## Presentation
Please refer to file presentation.pdf to see the non-technical results of this project.

## Future Analysis

- Collect more recent data from movies released in the past 5 years to keep up with the new trends/technology.
- Analyze the relationships or correlations between movies released only in theaters and movies released in theaters and on streaming services (such as Netflix, Hulu, etc.)
- Analyze budget details to see estimates in different stages of production


```python

```
