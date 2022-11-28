# Information-Visualization

Legend:
The X axis represents the seasons, and the Y axis represents Stars(rating out of 10) for the episodes.
The tv show has 10 seasons. Different color depicts a different season. The thick line running through the center shows the average rating for that season. 
Each season has several episodes which is shown by the lines in either direction of the center line based on the ratings it received. 
At the end of each line there is a filled circle(dot) with varying widths. It shows the number of votes that episode has received. Small dots are for episodes that have less votes and big dots are for episodes that received more votes.

Findings:
The average stars for the TV show remains in the range of 8.3 to 8.7 making it a good tv show. Only a few episodes received less than or equal to 7.5 stars, but many episodes have stars above 9. However, number of episodes with less votes are pretty much equal to the number of episodes with more votes. 

Data & Method:
The data used for this figure has 9 columns (Year of Production, Season, Episode No., Episode Title, Duration, Summary, Director, Stars and Votes). The main columns used are season, episode no., episode title, stars, and votes. With the help of season, episode no., and stars, the mod, average and mid is calculated. Another data frame is created to help create the episode lines by melting and grouping the episodes and calculating the maximum and minimum stars of each season.  Finally using matplotlib’s scatter, vlines and text functions, the figure is created. 

Importance:
This figure can help the production team of the series to understand how the tv show is being perceived by the audience. This one figure gives the viewer most of the important information like which episode did well, received more votes and the vice versa. It helps to understand the overall picture and analyze different aspects of the show. It also helps in understanding which aspects need improvement and which need to be kept the same.
