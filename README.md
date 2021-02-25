# Video-Game-Sales-Data-Analysis - How have game sales changes over the years?
GA Pyth 127 class - Miranda Powell

# **About the dataset**
Dataset was created by a web scrape of [VGChartz](https://www.vgchartz.com/) and a web scrape of [Metacritic](https://www.metacritic.com/browse/games/release-date/available). 
#**Data Dictionary**
*   Name - Game title
*   Platform - Console on which the game is running
*   Year_of_Release - Year game was released
*   Genre - Game's category
*   Publisher - Party responsible for distributing the game
*   NA_Sales - Game sales in North America (in millions of units)
*   EU_Sales - Game sales in the European Union (in millions of units)
*   JP_Sales - Game sales in Japan (in millions of units)
*   Other_Sales - Game sales in the rest of the world, i.e. Africa, Asia excluding Japan, Australia, Europe excluding the E.U. and South America (in millions of units)
*   Global_Sales - Total sales in the world (in millions of units)
*   Critic_score - Aggregate score compiled by Metacritic staff
*   Critic_count - The number of critics used in coming up with the Criticscore
*   User_score - Score by Metacritic's subscribers
*   User_count - Number of users who gave the userscore
*   Developer - Party responsible for creating the game
*   Rating - The ESRB ratings
*   Console_Summary - Grouping platforms together by company<sup>1</sup>

<sup>1</sup>Not from original data source. Created mid-analysis

# **Data Source**
*   https://www.kaggle.com/rush4ratio/video-game-sales-with-ratings

# **Data Source**
*   https://www.kaggle.com/rush4ratio/video-game-sales-with-ratings

#**Problem Statement**
*   How have game sales changes over the years?

#**Hypothesis**
*   The type of game sold will likely change over time with the addition of new genres over time.
* As the adoption of video game consoles increases, video game software consumption sales should follow a similar path
*   With more mainstream games, such as Zelda and Elder Scrolls, role playing games may grow in sales from 1990 to 2016

# **Conclusion**
When reviewing “Count of Games by Platform”, we see that the PS2 and DS drove the most game releases. When reviewing industry news, this can be attributed to the high sales volume of the PS2 and the DS consoles. Likely due to the low price barrier and value propositions of both consoles, Sony and Nintendo were able to sell 153 and 155 million units, respectively. The more units sold, the greater the console's ability to sell software. Behind the PS2 and DS, we see the PS3 is the third highest ranking platform. The PS3 sold 87 million units, a far cry from the 150 million plus units of the DS and PS2.

The role-playing genre has reached mainstream status. The data in the “Games Sold by Genre” chart shows that role-playing game sales increased between 1990 and 2005. However, we see this general growth with all genres. In order to understand if the popularity was increasing, we created the “Games Sold by Genre (%)” graph. This bar graph by year allows us to examine the percentage share of role playing games year by year. Based on the results, we see that role-playing games did increase in popularity, going from 6.8% in 1986 to 13.9% in 2016. Role-playing games peaked in 2010, consisting of 69.6% of units sold. Other notable genres that increased in popularity are sports games. The opposite can be said for puzzle games. Shooter games remain popular in 2016, however, they  do not own the majority share of the audience as they did in 1980.

Per the “Average Global Sales vs. Critic Score graph, we see that there is a link between average critic scores and global sales between the years of 1995 and 2001. This indicates that during that time period, critics had a very direct link in influencing people to purchase games. However, in the following years between 2002 and 2015, we see a change in this relationship. For example, in 2007, regardless of the critic score being low (average 66.2%), we still had global sales rising. On the contrary, 2015 shows that even though critic scores were rising (72.9%), sales in video games generally showed a decline. 

When comparing user scores to global sales, we see a very strong link between the two. Generally, as user scores decline, sales performance quickly follows. However, this relationship changed in 2004, as the two fell out of sync. This could potentially be attributed to the rise of “youtube gaming”, in which people watch others play video games. The “average score by genres” chart shows that average critic scores across all genres between 1996 and 2016. This could potentially be attributed to the increasing expectations of video game quality and video game complexity.

The “Top 10 Global Sales” depict the strongest genre and best performing video games. The genres analysis shows that Action, Sports and Shooters generally dominated the sales between 1990 and 2016. When reviewing individual games, we see Wii Sports was the most popular, at 82.5 million units sold. Followed by Grand Theft Auto (56.6 million) and then Super Mario Bros (45.3 Million). 

In last section we do see a general trend of positive growth in sales for Microsoft, Sony, and Nintendo and PC software. However, in the Microsoft, Sony and Nintendo charts, we do see major dips in software sales. 
Upon further review of industry news, Microsoft’s dip in sales can be attributed to the poor sales of the Xbox One in 2013. Industry experts point to Microsoft’s poor communication and branding of the Xbox One. Microsoft positioned the Xbox One as an all round TV centric media device. Moving the focus away from gaming hurt Microsoft's ability to sell units, which thus hurt game publishers ability to sell software. Sony, in a very similar situation, sees a major increase between the Playstation 1 and 2. The increasing success of the second playstation can be attributed to the inclusion of DVD playing capabilities in the 2nd playstation. With an increase in units sold, Sony saw a major leap in software sales, as we see in our data. However, we see a fall in software sales in the Playstation 3 category. Upon further review of industry news, the fall in software sales can be attributed to the low sales performance of Playstation 3 units, which can further be attributed to the high price stage Sony placed on the Playstation 3.
