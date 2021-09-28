# Purpose: 
* To uncover patterns in the top 1000 rated IMDB movies and TV shows, and to see if there are certain characteristics that will increase chances of being in the top 1000 IMDB titles list.

# The Data
* To answer our questions, we used data accumulated from IMDB’s top 1000 titles.

* Disclaimer: 
* Our population consists of only the top 1000 rated titles on IMDB, and does not represent all titles in IMDB. Additionally, our data is not uniformly distributed, since titles with IMDB rating lower than 7.6 were not included in the data. Therefore, assumptions made in our analysis only apply to titles with higher overall viewer sentiment.

* Resources:
Shankhdhar, Harshit. “IMDB Movies Dataset.” Kaggle, 1 Feb. 2021, https://www.kaggle.com/harshitshankhdhar/imdb-dataset-of-top-1000-movies-and-tv-shows

# Question
* Does Runtime affect IMDB Ratings of the IMDB top 1000?
* Do Gross Earnings affect IMDB Ratings of the IMDB top 1000?
* Does IMDB Ratings align with Metascore?
* Is there a significant difference in the IMDB top 1000 ratings between U certificates and UA certificates?

# Analysis
* Q1: 
    * Scatterplot r-value: 0.25822381247916004. Runtime did not have an impact on IMDB ratings.
    ![IMDB V Runtime Scatterplt](/Figures/01_IMDB_v_Runtime_scatter.png "IMDB V Runtime")
* Q2: 
    * Alternative: If a high IMDB rating earned more money, then movies rated above 7.9 will make more than movies rates below 7.9.
    * Null: If a high IMDB rating does not earned more money, then movies rated above 7.9 will not make more money than movies rates below 7.9.
    * P-value=0.0707467425988131
* Q3: 
    * R-value = 0.280894. There was a positive but weak correlation between IMDB rating and metascore
    ![IMDB V Meta Scatterplt](/Figures/03_imdb_v_meta_scatter.png "IMDB V Scatterplt")
* Q4: 
    * Alternative: If A rated movies have higher overall viewer sentiment than UA rated movies, the IMDB rating for A rated movies will be higher than the IMDB rating for UA rated  movies.
    * Null: If A rated movies do not have higher overall viewer sentiment than UA rated movies, the IMDB rating for A rated movies will not be higher than the IMDB rating for UA rated movies.
    * p-value = 0.049549781805392795

<img src="" width="100" height="100">

 ![IMDB V Meta Scatterplt]("/Figures/03_imdb_v_meta_scatter.png" "IMDB V Scatterplt" width="100" height="100")

