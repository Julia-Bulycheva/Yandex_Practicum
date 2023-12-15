# Searching for patterns that determine the success of a computer game

Using data on video game sales, user and expert ratings, genres, and platforms, patterns determining the success of a game were identified. Parameters determining game success in different regions of the world were also identified. Based on this, a report was prepared for a computer game store to plan advertising campaigns. Data preprocessing and analysis were conducted, and a relevant time period for analysis was selected. User profiles for each region were created. Hypotheses were tested: whether the average user ratings for the Xbox One and PC platforms are the same and whether the average user ratings for the Action and Sports genres are different. The Student's t-test for independent samples was used for the analysis.

# Project objective

The goal of the research is to identify patterns that determine the success of a game. This will allow the research client to focus on potentially popular products and plan advertising campaigns for 2017.

# Technology Stack

Python with the following libraries:
- pandas
- numpy 
- matplotlib.pyplot 
- plotly.express 
- seaborn 
- statistics 

# Project Status

Project completed.

# Key results and conclusions 

The study was conducted based on data from an online store, which sells computer games worldwide. Historical data on game sales, user and expert ratings, genres, and platforms (e.g., Xbox or PlayStation) are available from open sources. The goal of the study is to identify patterns that determine the success of a game. This will allow the research client to focus on potentially popular products and plan advertising campaigns for 2017.

In general, the data provided for analysis reflect the dynamics of changes that have occurred in the video game market. By 1994, the market had developed so rapidly that it led to the formation of ratings that helped potential users navigate a large volume of diverse offerings. In 1994, the Entertainment Software Rating Board (ESRB) was created, which determines the rating of computer games and assigns them an appropriate age category. The most popular age ratings for the period are 'E', 'M' 'T' 'E10+' 'K-A' 'AO' 'EC' 'RP'.

For the analysis, the relevant period of 2014-2016 was chosen, based on the following features of the video game market's development:

1)If before 2011, the number of games released was constantly increasing, then in the period from 2012 to 2016, the number of games significantly decreased compared to the previous five years (2006-2011). Therefore, it can be concluded that the maximum analyzed period can be 5 years. 

2)The income period for a "successful" platform is a minimum of 4 years. Let's assume that 2017 will presumably be the last year to generate income. In this case, the relevant period will be 3 years. 

3)If we take only one year for analysis (for example, 2016), there is a possibility that the data will not reflect all the trends that have developed in the market (data may be missing for various reasons, force majeure circumstances may occur), or, conversely, reflect factors that are characteristic only for one year, and subsequently lose their relevance.

The analysis selected the most potentially profitable gaming platforms. The following criteria were taken into account when choosing them:

1)The game release date should not be later than 2014 (based on the chosen relevant period).

2)The availability of data on positive ratings and user reviews for the game (if the rating is high and the reviews are positive, then the sales revenues are more likely to grow).

3)The availability of sales data for all regions and the highest sales figures for the game.

As a result of the analysis, the following promising gaming platforms were selected: 'PS4', 'WiiU', 'XOne'

The PS4 platform is distinguished by having the highest number of games (237), which indicates financial stability. The presence of a significant number of high-revenue games allowed this platform to take the leading positions. The game "Grand Theft Auto V," placed on this platform, generated the highest revenue for the entire analyzed period - $12.62 million. The PS4 gaming platform is the leader in sales in North America and Europe, accounting for 60.5% and 82.6% of the total sales volume, respectively.

The WiiU platform lags in terms of sales volume behind the rating leader - the PS4 platform. The total number of games on this platform is 43, three of which (the most successful of which is "Mario Kart 8" with $7.09 million) provided high revenues from sales for the entire platform during the analyzed period. The WiiU gaming platform is the sales leader in Japan, with a share of 55.1% of the total sales volume, while the PS4 is in second place with a share of 43.9%.

The XOne platform is another successful platform. Analytical data on this platform reflects the components of a successful perspective platform: a large number of games (in this case - 155) in general and the presence of nine high-revenue games. The game "Grand Theft Auto V" also generated the highest revenue for this platform - $5.47 million.

The average user ratings for the Xbox One and PC platforms are the same - the statistical hypothesis regarding the average values of two populations, where the averages of the two populations are equal to each other, was not confirmed.

The average user ratings for the Action and Sports genres are the same - the statistical hypothesis regarding the average values of two populations, where the averages of the two populations are not equal to each other, was confirmed.

An analysis of promising platforms has led to the following conclusions:

The highest sales volume is achieved by games with an "M" rating ("Mature") — "17+": Game content is suitable for ages 17 and older. In the total sales volume, games with an "M" rating account for 59.4% in North America, 51.3% in Europe, and 31.79% in Japan. It's worth noting that the game market in Japan is almost equally divided between games with an "M" rating - 31.79%, games with an "E" rating ("Everyone") - 29.6%, and games with an "E10+" rating ("Everyone 10 and older") - 29.4%.

User and critic reviews significantly influence sales volume.

The most popular game genres are Action, Shooter, and Sports, while Role-Playing and Racing are the outsiders. In North America and Europe, the sales leaders are Shooter and Action games, while in Japan, Shooter games dominate with a sales share of 49.3%.