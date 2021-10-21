# Analysis of Movie Profitability

**Author**: Colm Yeh

## Overview
This project examines the successes and failures of new movie releases for the purposes of finding the most profitable and successful movie release strategy.

Drawing from IMDB databases and the movie budgets database, this analysis provides 3 concrete business recommendations to ensure a profitable market entry for Microsoft's projects:

1.) Release movies during the most profitable release months.

2.) Release movies belonging to the most profitable genres.

3.) Focus artistic and strategic direction on the end consumer, not critics.

## Business Problem
Microsoft has decided to enter the video content space, and this analysis provides actionable insights on which kind of projects perform the best. Due to the capital intensive nature of making movies, choosing projects with proven releases and genres is extremely important for meaningful return on investment.

To this end, this analysis seeks to answer the most profitable movie genres (1), the most profitable time of the year to release (2), and whether resources should be committed to pleasing critics and garner good ratings (3). These combined insights will allow Microsoft to choose projects with proven profitability.

## Data
3 Databases:

IMDB Title Basics- includes movie title and genres

    Combined with movie budgets, grouped by release month to ascertain the most profitable time to release
    
    Combined with movie budgets, grouped by genre to find the most profitable genre across 6027 movies and 2637 genres
    
IMDB Title Ratings- includes average rating of movies

    Combined with movie budgets to graph the correlation between profit and ratings
    
Movie Budgets- Movies, release date,  production budgets, domestic gross, worldwide gross, and Profit

5782 movies across multiple decades, combined with both other databases

## Methods

Key Metrics of analysis:
  Profit,
  Release month,
  genre
  
Using barplots, scatterplots, and correlation

## Results
### Most Profitable Release Month

<img width="734" alt="Screen Shot 2021-10-07 at 8 55 20 AM" src="https://user-images.githubusercontent.com/87211473/138322028-d4a75c89-6048-4a2e-be99-9b132cbe68d7.png">

### Most Profitable Genres
![download](https://user-images.githubusercontent.com/87211473/138322161-6aa872fc-291d-40f5-b324-32fdeeb3f37a.png)

### Good Ratings do not Strongly Correlate with Profit
![download-4](https://user-images.githubusercontent.com/87211473/138322314-a5f45fd4-06bc-4197-9230-f7a2ba683549.png)


## Conclusions
This analysis points to three recommendations for Microsoft's management in selecting, producing, and releasing new projects:

1.) Release movies during the most historically profitable release months. Coinciding with the summer and the holidays, these months are May, June, July, November, and December (in that order).

2.) Choose projects occupying the animation, adventure, or sci-fi genres. Historically, these genres have the highest profitability (in that order) within tolerable variability. With these genres, Microsoft will be best able to capture audiences and drive meaningful return on investment.

3.) Focus artistic and strategic direction on the end consumer, not critics. Since ratings do not correlate strongly with profitability, investing resources into pleasing critics does not necessarily result in ROI. Instead, invest in marketing and promotion targeting the end consumer. Movie critics may examine movies on different criteria (acting caliber, cinematography, total artistic worth etc.) than the average movie goer. This systematic difference results in ratings having a very weak correlation with profit. Trying to live up to artistic perfection that critics demand is simply a waste of resources.



## For More Information

For any additional questions, please contact **Colm Yeh, yehcolum@gmail.com**

## Repository Structure


```
├── README.md                           <- The top-level README for reviewers of this project
├── dsc-phase1-project-template.ipynb   <- Narrative documentation of analysis in Jupyter notebook
├── Movie Analysis.pdf                  <- PDF version of project presentation
├── data                                <- Both sourced externally and generated from code
└── images                              <- Both sourced externally and generated from code
```
