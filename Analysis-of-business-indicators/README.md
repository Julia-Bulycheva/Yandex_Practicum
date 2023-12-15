# Analysis-of-business-indicators

Task for a marketing analyst at the entertainment app Procrastinate Pro+. Despite significant investments in advertising, the company has been running at a loss for the past few months. The task is to investigate the reasons behind this and help the company turn a profit. Data analysis from ProcrastinatePRO+ has been conducted. Various metrics have been calculated, including cohort analysis: LTV, CAC, Retention rate, DAU, WAU, MAU, etc. Metric calculation functions were used, and conclusions were drawn based on the obtained data.

# Project objective

The project aims to study the following:
- where users come from and what devices they use.
- how much it costs to attract users from different advertising channels.
- how much money each customer brings.
- when customer acquisition costs pay off.
- what factors hinder customer acquisition.

# Technology Stack

Python with the following libraries:
- pandas
- datetime
- timedelta
- seaborn 
- pyplot 
- numpy 

# Project Status

Project completed.

# Key results and conclusions

Despite significant investments in advertising, the company has been incurring losses for the past few months, especially from the entertainment application Procrastinate Pro+. The project's task is to understand the reasons for the current situation based on data about users attracted from May 1st to October 27th, 2019.

Profiles of 150,008 users from France, Germany, the United Kingdom, and the USA have been created, and the analysis of these profiles has led to the following conclusions. The application is most popular in the USA, where it has the largest number of paying users both in absolute and relative terms: 6,902 people, which constitutes 6.9% of the total number of users in the USA. The devices preferred by all customers and the devices preferred by paying customers are 'Android,' 'iPhone,' 'Mac,' and 'PC.' Among paying users, Mac and iPhone are the most popular (6.36% and 6.21% of the total number of users, respectively).

The channels that have the highest share of paying users are Faceboom, AdNonSense, and LambdaMediaAds, accounting for 12.20%, 11.34%, and 10.47% of the total number of users in these channels, respectively. However, the leaders among the channels in terms of the number of users are Organic, FaceBoom, and TipTop.

The total marketing expenses amount to 105,497.3. The main advertising sources are TipTop with 54,751.30 and FaceBoom with 32,445.60. The rest of the marketing expenses are distributed among 6 other sources. Speaking of the dynamics of expenses, different advertising campaign strategies have been chosen for TipTop and FaceBoom. For the FaceBoom channel, advertising expenses are evenly distributed from 1000 to 2000 weekly. For the TipTop channel, a different strategy of advertising campaigns was chosen, with expenses increasing and reaching a maximum in September.

The highest average cost of acquiring one user (CAC) is associated with the TipTop source, which amounts to 2.80. FaceBoom and AdNonSense sources rank second and third in terms of CAC (1.11 and 1.01, respectively). Through the TipTop source, 1,878 paying users were acquired, while FaceBoom and AdNonSense sources attracted 3,557 and 440 paying users, respectively.

It's worth noting the organic source, which attracted customers without incurring advertising expenses. However, the number of its paying users reached 1,160. Users from the Organic source were not included in the analysis, as their acquisition was done without advertising expenses.

Thus, when identifying the reasons for the low effectiveness of advertising expenses, it is necessary to pay attention to the TipTop and AdNonSense channels.

Analysis of advertising profitability. The analysis moment is November 1, 2019. The analysis horizon is two weeks after attracting the user, as this period is set in the business plan as the payback period.

Overall, the analysis of indicators for profiles of paying users allowed the following conclusions: 

1. The cumulative revenue constantly grew during the analysis horizon; 

2. The cumulative revenue remained roughly at the same level throughout the entire period; 

3. CAC increased throughout the entire period; 

4. ROI did not reach profitability levels throughout the period; 

5. The overall ROI trend showed a tendency to decrease, and by June, advertising expenses stopped paying off.

The analysis of the user conversion revealed that conversion does not depend on the date of the first user visit or on the devices they use. Users who own Mac and iPhone have higher conversion rates than other users. Users from the USA are significantly outperforming other users as the highest conversion rates shows. The graph of advertising sources shows that the maximum conversion rate is reached in the second week and then stabilizes at a certain level. The channels FaceBoom, adNonSense, and LambdaMediaAds show the highest conversion rates.

Charts of the user retention show that the lowest retention rate is consistently demonstrated by the advertising channel 'FaceBoom.' The relatively low level of retention among US users reflects the high market competition and the population's high financial capacity.

Revenues from users in the United States were growing at a faster pace than from users in other countries. However, advertising expenses to attract them had higher growth rates and did not pay off in the short or long term. Advertising expenses in other countries began to pay off after 6 days of the user's first visit and showed good profitability in the long term. The U.S. market is the largest and most financially capable, but as mentioned above, it faces stiff competition and low margins. A more thorough analysis is needed to study the further prospects for promoting the application in the U.S. or to focus on other countries.

Over the analyzed period, the revenues generated by users had a growth trend regardless of the devices they used. However, the cost of acquiring users also increased, with users of Mac and iPhone devices increasing at higher rates compared to other devices. For PC users, the cost of acquiring them was significantly lower, and the return on investment was higher than for other devices. It can be said that only advertising expenses targeting PC users paid off. Therefore, it is considered necessary to draw the attention of marketers to the segment of users who access the application via PC.

The analysis of advertising profitability broken down by advertising channels once again confirmed that advertising on AdNonSense, FaceBoom, and TipTop channels was unprofitable both during the analysis horizon and throughout the entire period for which information is provided. If expenses for other advertising channels were distributed evenly, then advertising campaigns on the TipTop channel, with significant and constantly increasing budgets, did not justify themselves. In order to increase the efficiency of advertising expenses on the TipTop advertising channel, you can consider advertising on channels like lambdaMediaAds, MediaTornado, and YRabbit, which show positive results with a small budget.