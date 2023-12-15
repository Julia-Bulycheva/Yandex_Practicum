# The research on the quality of a mobile application for selling food products

In this project, the principles of event analytics were utilized. I constructed a sales funnel, examined user journeys leading to a purchase, and analyzed the results of an A/B test for the introduction of new fonts. I compared two control groups to ensure proper traffic allocation and then compared them to the test group. It was found that the new font had a negligible impact on user behavior.

# Project objective

The aim of this project was to study the behavior of users of a startup - a mobile application that sells food products. During the project, the following tasks needed to be addressed:

Understand how users navigate through the application to make a purchase.
Determine how many users reach the purchase stage and how many get stuck at the previous steps.
Identify the specific steps where users tend to drop off.

To address these tasks, an analysis of the results of an A/A/B experiment was conducted. During this experiment, users were divided into three groups: two control groups with old fonts and one experimental group with new fonts.

Creating two A groups instead of one had certain advantages in ensuring the accuracy of the experiment and detecting factors that led to result distortions.

Based on the results of the A/A/B experiments, the following was determined:
- Which font is more user-friendly for the application users.
- How much time and data will be needed for further tests.

# Technology Stack

Python with the following libraries:
- pandas
- scipy
- numpy
- matplotlib
- math
- scipy
- stats

# Project Status

Project completed.

# Key results and conclusions

The aim of this project was to research the behavior of startup users - a mobile application that sells food products. During the project, an analysis was conducted in several directions:

1. To find out how users go through the purchase process.
2. To determine how many users reach the purchase stage and how many "get stuck" at previous steps.
3. To identify the specific steps where users tend to drop off.

The preliminary analysis revealed that there are 5 events in the log: 'CartScreenAppear', 'MainScreenAppear', 'OffersScreenAppear', 'PaymentScreenSuccessful', and 'Tutorial'. Among these, 'MainScreenAppear' is the most common event. The data from August 1, 2019, to August 7, 2019, are distributed quite evenly, while from July 25, 2019, to July 31, 2019, there is almost no data, so these dates were excluded from the analysis.

The sequence of events represents a sequential chain: users first enter the site ('MainScreenAppear'), then explore the offer (Event A - transition to 'OffersScreenAppear'). If they like it, they proceed to the cart ('CartScreenAppear'), and finally, they make a payment ('PaymentScreenSuccessful'). The number of users decreases from one event to the next. The biggest drop occurs at the first step, with a 38.09% drop-off rate. The ratio of the number of users with event B to the number of users with event A is -18%, and the ratio of the number of users with event C to the number of users with event B is -5.22%. Comparing the number of users who made a purchase to the number of users who visited the site, their share was 1.47%.

To address the stated tasks, a study of the results of an A/A/B experiment was conducted, in which users were divided into 3 groups: 2 control groups with old fonts (groups 246 and 247) and one experimental group with new fonts (group 248). The number of unique users in group 246 was 2484, in group 247 was 2513, and in group 248 was 2537.

Testing the control groups in the A/A experiment showed that the number of users in control groups 246 and 247 differs insignificantly (by 1.15%), as well as the share of the number of unique users in groups 246 and 247 participating in each event.

During testing the control groups in the A/A experiment, the correctness of the hypotheses was verified: Null Hypothesis - there is a significant difference between the proportions. Alternative Hypothesis - there are no grounds to consider the proportions different. These hypotheses will be tested further during the A/B experiment.

Comparing the proportions of two general populations (groups 246 and 247) was done based on samples from them: the first sample - users who reached the MainScreenAppear stage, the second sample - users who reached the OffersScreenAppear stage, the third sample - users who reached the CartScreenAppear stage, and the fourth sample - users who reached the PaymentScreenSuccessful stage. All comparisons of proportions showed that there is no statistically significant difference between the groups (p-value >0.1), and the null hypothesis could not be rejected. The shares of unique visitors who reached each stage of the funnel are the same. Testing the control groups in the A/A experiment confirmed the correctness of all mechanisms and calculations used in their formation.

Similarly, testing the control groups in the A/B experiment was performed. Null Hypothesis: The proportions of unique visitors who reached each stage of the funnel are the same. Alternative Hypothesis: There is a significant difference between the proportions of unique visitors who reached each stage of the funnel. The samples were divided into groups. When testing statistical hypotheses, a significance level (p-value) of 0.05 was used. A total of 12 A/B tests were conducted.

The A/B experiment showed the following:

1. Comparison of user behavior between control group 246 and experimental group 248: According to the calculations, the number of users in control group 246 and experimental group 248 differs by 2.09%. There is a significant statistical difference between the proportions of users in groups who made payments in relation to the total number of users who visited the application. The null hypothesis was confirmed. It was concluded that changing the font in the application has a statistically significant impact on the behavior of online store users.

2. Comparison of user behavior between control group 247 and experimental group 248: According to the calculations, the number of users in control group 247 and experimental group 248 differs by 0.95%. There is no statistically significant difference between the proportions of users in the groups at each stage of the funnel.

3. Comparison of user behavior between control group 249 (combined group from 246 and 247) and experimental group 248: There is also no statistically significant difference between the proportions of users in the groups at each stage of the funnel. Therefore, it can be concluded that changing the font in the application does not have a statistically significant impact on the behavior of online store users, i.e., it does not affect the sales volume.

In the case of multiple tests, the probability of making a Type I or Type II error increases, meaning that we may detect a difference between groups when there isn't one (false positive result) or fail to detect a difference when it actually exists (false negative result).

In the present case, a Type II error, or a false negative result, may occur. This indicates that there are differences between the groups, but the test showed a p-value greater than the significance level α, giving us no grounds to reject H₀ (the null hypothesis).

One way to reduce Type II errors is to increase the power of the test. However, for the A/B test in question, a significance level of α = 0.05 was chosen, which is already quite high.

Therefore, to make a decision on whether to change the font of the text on the store's website, one should consider the potential consequences of accepting or not accepting this decision. The only way to simultaneously reduce the probabilities of Type I and Type II errors is to increase the sample size.