# Microsoft Film Analysis Project
![mmm7.jpg](attachment:mmm7.jpg)


## Overview
We've been hired to discover trends in movie data in order to guide a new streaming platform/movie studio on what sort of content they should be creating. Ultimately, our analysis proved fruitful delivering the following valuable recommendations:
1. Analyzing a movie's popularity in relation to movie year: We encourage Microsoft to give greater consideration to trends in more proximal years, as these are a stronger reflection of their current audience's desires.
2. Per Genre:  We recommend Microsoft invests primarily in the production of Action-Adventure-SciFi Movies, followed by a mix of Action-Adventure-Comedy films, and drama films.
3. Per Producer: We would first and foremost advise Microsoft to hire Christopher Nolan and Anthony Russo followed by Dennis Villeneuve and Quentin Tarantino as directors. 


## Business Problem 
As the markets and demand for movie streaming platforms continues to climb, various tech corporations have investigated creating streaming services of their own. A historic and cutting edge player in the technology field, Microsoft Corporation, has developed a new branch for this very purpose, Microsoft Movie Studios(MMS).  MMS has hired us to conduct an exploratory data analysis on recent films in order to advise them on film creation - style, genre, directorship, etc.to give them the greatest chance at finding popularity and success. 



## Data
We obtained our data from the Internet Movie Database - or IMDB-  one of the most popular and extensive movie data sources in the world.

Starting with over 14,000 movies(from the year 2010-2019),  we distilled our list to the 100 most popular films, from which we were able to discover trends that will serve of great value to MMS.  


## Methods 
The first thing we did, is created a standardized variable, POPULARITY,  that would allow us to more fairly compare and judge these films. 

![Screen%20Shot%202022-04-22%20at%201.39.37%20PM.png](attachment:Screen%20Shot%202022-04-22%20at%201.39.37%20PM.png)

In order to predict movie popularity, we decided to analyze three variables that would provide actionable and relevant insight to MSS: 
1. MOVIE YEAR
2. MOVIE GENRES
3. MOVIE PRODUCER 

The questions we sought to answer: 
1. In what years are the most popular and relevant trends - informing genre(s) and producer?
2. What genre(s) will be most successful with Microsoft's target audience?
3. What director(s) creates the most engaging and likable films?


## Results

#### Movie Year vs. Average Popularity rating  
![Screen%20Shot%202022-04-22%20at%202.12.22%20PM.png](attachment:Screen%20Shot%202022-04-22%20at%202.12.22%20PM.png)

We decided the more recent the movie was produced, the more valuable its rating should be, as this is a more accurate reflection of today's audience - the audience that Microsoft will be creating content for. 

We found that our Year vs. Average Popularity Rating graph followed a nearly perfect trendline, confirming that our popularity calculation was properly adjusted, giving slightly more weight to the popularity ratings the more recent the movie was produced.  


#### Genre(s) and Directors 
The two most important actionable items we investigated were genre(s) and directors. Specifically, we determined the modal genre(s) and the directors who directed the greatest number of films in our top 100 most popular film list from the last decade. The charts with these numbers are seen below: 

![Screen%20Shot%202022-04-22%20at%201.48.18%20PM.png](attachment:Screen%20Shot%202022-04-22%20at%201.48.18%20PM.png)

![Screen%20Shot%202022-04-22%20at%201.47.47%20PM.png](attachment:Screen%20Shot%202022-04-22%20at%201.47.47%20PM.png)

## Conclusion and Next Steps 

As previously stated, our sugguestions include:
1. We encourage Microsoft to give greater consideration to trends in more proximal years, as these are a stronger reflection of their current audience's desires.
2. Per Genre:  We recommend Microsoft invests primarily in the production of Action-Adventure-SciFi Movies, followed by a mix of Action-Adventure-Comedy films, and drama films.
3. Per Producer: We would first and foremost advise Microsoft to hire Christopher Nolan and Anthony Russo followed by Dennis Villeneuve and Quentin Tarantino as directors.


We believe there is additional value to be gleaned from this data, namely a comparison of production budget vs. popularity, as well as an investigation into the domestic/worldwide gross according to our same metrics.

We believe this will allow Microsoft to further maximize its budget and its investors' resources, determining what genres and directors will create the most effective and popular product for the lowest necessary cost. 
