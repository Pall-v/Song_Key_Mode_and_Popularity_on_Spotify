# DSCI522_Pall-v_sedv8808


## Spotify Analysis Proposal


In music, most notes can have a lower or a higher pitch. Same as with beats making a song more "likeable", we believe that the mode of a song interfers on a person's preference to listen to it more. 

Through this evaluation, we will go through spotify's data sets to analize whether people are actively listening to more songs that are on the higher or lower mode. As a null hypothesis, we would think this mode would not interfer with likeability. 


1) Question: Does a song with a higher note make it more likeable?

2) Name of dataset: Top Spotify Tracks of 2017 (top-tracks-of-2017.csv) and Spotify's Worldwide Daily Song Ranking (data.csv)

Link to the data sets: We loaded the dataset using tidyverse in R.

https://www.kaggle.com/edumucelli/spotifys-worldwide-daily-song-ranking
https://www.kaggle.com/nadintamer/top-tracks-of-2017


3) Analysis:

We want to determine if the role of a mode modifies the popularity of a song in Spotify. We know the 100 most popular songs, however, we would like to see what the 10 most popular usually look like.

Our estimate would be the proportion of songs with mode 1 and songs with mode 0 in the top 10.

In order to do this analysis, we will use Hypothesis tests and confidence intervals to see how the proportions change for different groups depending on the mode.

Null Hypothesis : Songs with mode 1 are listenend just as much as songs with mode 0. (Same proportion)

Alternative Hypothesis: Songs with mode 1 are not listened in the same proportion as songs with mode 0.

4) In order to evaluate this proportions, we need to do some wrangling between Spotify data bases. In the top 100, we need to merge all the attributes of each song - particullarly, mode.

We will consider a threshold of 0.05.
