# Purpose 
* To uncover patterns in the top 1000 rated IMDB movies and TV shows, and to see if there are certain characteristics that will increase chances of being in the top 1000 IMDB titles list.

# The Data
* Data accumulated from IMDB’s top 1000 titles

* Our population consists of only the top 1000 rated titles on IMDB, and does not represent all titles in IMDB. Additionally, our data is not uniformly distributed, since titles with IMDB rating lower than 7.6 were not included in the data. Therefore, assumptions made in our analysis only apply to titles with higher overall viewer sentiment.

* Resources:
Shankhdhar, Harshit. “IMDB Movies Dataset.” Kaggle, 1 Feb. 2021, https://www.kaggle.com/harshitshankhdhar/imdb-dataset-of-top-1000-movies-and-tv-shows

# Questions & Statistical Analysis
#### Q1: Does Runtime affect IMDB Ratings of the IMDB top 1000?
    * Scatterplot r-value: 0.25822381247916004. 
    * Runtime does not appear to have an impact on IMDB ratings.
    ![IMDB V Runtime Scatterplt](/Figures/01_IMDB_v_Runtime_scatter.png "IMDB V Runtime")
    
#### Q2: Do Gross Earnings affect IMDB Ratings of the IMDB top 1000?
    * Hypothesis Test
      * Alternative: If a high IMDB rating earned more money, then movies rated above 7.9 will make more than movies rates below 7.9.
      * Null: If a high IMDB rating does not earned more money, then movies rated above 7.9 will not make more money than movies rates below 7.9.
      * P-value=0.0707467425988131
    * Higher gross earnings would not correspond with higher rated titles.

#### Q3: Does IMDB Ratings align with Metascore?
    * R-value = 0.280894. There was a positive but weak correlation between IMDB rating and metascore
    ![IMDB V Meta Scatterplt](/Figures/03_imdb_v_meta_scatter.png "IMDB V Scatterplt")
    * IMDB and Metascore rating data is not aligned well.

#### Q4: Is there a significant difference in the IMDB top 1000 ratings between U certificates and UA certificates?
   * Hypothesis Test
      * Alternative: If A rated movies have higher overall viewer sentiment than UA rated movies, the IMDB rating for A rated movies will be higher than the IMDB rating for UA rated  movies.
      * Null: If A rated movies do not have higher overall viewer sentiment than UA rated movies, the IMDB rating for A rated movies will not be higher than the IMDB rating for UA rated movies.
      * p-value = 0.049549781805392795
   * A certificate tend to have higher IMDB rating than UA certificates among the IMDB top 1000.


# Findings
* Q1:
   * Result: Does not affect IMDB ratings of the current top 1000 IMDB titles
   * Inferences: Identifying a target runtime won’t necessarily chance of being in the IMDB top 1000.
* Q2:
   * Result: There is no statistically significant difference in the gross earnings of high rated (above 7.9) vs. low rated (below 7.9) titles, for the top IMDB top 1000. 
   * Inferences: If your goal is to make the IMDB top 1000 list, we conclude that focusing on gross earnings will not affect your chances.
* Q3:
   * Result: IMDB Rating were not well aligned with Metascore Ratings.
   * Inferences: IMDB Ratings might not be the best measure of success. 
* Q4:
   * Result: A Certificate movies generally rated higher than UA movies. 
   * Inference: You are more likely to be ranked higher on IMDB top 1000 if the title has an A certificate, rather than UA. 





