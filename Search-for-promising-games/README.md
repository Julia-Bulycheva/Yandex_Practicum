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

In general, the data provided for analysis reflect the dynamics of changes that have occurred in the video game market. By 1994, the market had developed so rapidly that it led to the formation of ratings that helped potential users navigate a large volume of diverse offerings. In 1994, the Entertainment Software Rating Board (ESRB) was created, which determines the rating of computer games and assigns them an appropriate age category. The most popular age ratings for the period are 'E', 'M' 'T' 'E10+' 'K-A' 'AO' 'EC' 'RP'.

For the analysis, the relevant period of 2014-2016 was chosen, based on the following features of the video game market's development:

1) If before 2011, the number of games released was constantly increasing, then in the period from 2012 to 2016, the number of games significantly decreased compared to the previous five years (2006-2011). Therefore, it can be concluded that the maximum analyzed period can be 5 years. 
2) The income period for a "successful" platform is a minimum of 4 years. Let's assume that 2017 will presumably be the last year to generate income. In this case, the relevant period will be 3 years. 
3) If we take only one year for analysis (for example, 2016), there is a possibility that the data will not reflect all the trends that have developed in the market (data may be missing for various reasons, force majeure circumstances may occur), or, conversely, reflect factors that are characteristic only for one year, and subsequently lose their relevance.

The analysis selected the most potentially profitable gaming platforms: 'PS4', 'WiiU', 'XOne'. An analysis of promising platforms has led to the following conclusions:

1) The highest sales volume is achieved by games with an "M" rating ("Mature") — "17+": Game content is suitable for ages 17 and older. In the total sales volume, games with an "M" rating account for 59.4% in North America, 51.3% in Europe, and 31.79% in Japan. It's worth noting that the game market in Japan is almost equally divided between games with an "M" rating - 31.79%, games with an "E" rating ("Everyone") - 29.6%, and games with an "E10+" rating ("Everyone 10 and older") - 29.4%.

2) User and critic reviews significantly influence sales volume.

3) The most popular game genres are Action, Shooter, and Sports, while Role-Playing and Racing are the outsiders. In North America and Europe, the sales leaders are Shooter and Action games, while in Japan, Shooter games dominate with a sales share of 49.3%.