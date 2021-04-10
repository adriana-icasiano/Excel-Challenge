# Excel-Challenge
In this Excel Homework, students are asked to analyze a dataset with 4,000 past Kickstarter projects and to uncover some market trends.

## Table of Contents ##
* [Summary](https://github.com/adriana-icasiano/Excel-challenge#Summary)
* [Analysis](https://github.com/adriana-icasiano/Excel-challenge#Analysis)
* [Data Limitation](https://github.com/adriana-icasiano/Excel-challenge#Data-Limitation)
* [Additional Tables and Graphs](https://github.com/adriana-icasiano/Excel-challenge#Additional-tables-graphs)
* [Bonus Statistical](https://github.com/adriana-icasiano/Excel-challenge#Bonus-Statistical)
## Summary ##
The Data is categorized by four statuses (referred to as state in the data), success, failure, canceled and live. Successful is defined as *100% or more of the fundraising goal met*. Due to the nature of the business, the data values are widely spread out from the mean - for example, campaign goals ranged from $1 to $400,000 and the mean is $3,500. Campaigns related to theater plays, documentary and rock are the most common and successful.  Although theatrical play is the most popular subcategory and raised the most dollars in total, it has a high failure rate. The high failure rate of theatrical plays campaigns may be reduced by spending on marketing tools from Kickstarter, such as spotlight.

## Analysis ##
### 1. Fundraisers in theatrical plays, documentaries and rock music industries from US, Canada and UK make up most Kickstarter campaigns.   
The top three most successful categories are in the Theater, Music and Film & Video categories. Within those categories, the top three most successful sub-categories are theatrical plays, documentary and rock music. As such, some of our analysis is focused on these sub-categories. All the campaigns spanned across 21 countries, 74% of which is based in US, 15% the UK, and $4 Canada. Refer to  [Table 1 Successful vs Failure Percentages by Category](https://github.com/adriana-icasiano/Excel-Challenge/blob/9ffd2485729ed910c9da63ddc2c2a7a5e59f67e0/Chart%203.PNG) and [Table 2 Campaigns by Country](https://github.com/adriana-icasiano/Excel-Challenge/blob/cad4790127aa0eb60945d941704d5f839325315e/Chart%2017.PNG)

![Successful vs Failure Percentages](https://github.com/adriana-icasiano/Excel-Challenge/blob/9ffd2485729ed910c9da63ddc2c2a7a5e59f67e0/Chart%203.PNG)

![Campaigns by Country](https://github.com/adriana-icasiano/Excel-Challenge/blob/cad4790127aa0eb60945d941704d5f839325315e/Chart%2017.PNG)

### 2) Successful campaigns provide pointers for key campaign attributes. ###
   > a) While the other months have similar number of successful campaigns, the month of May have a slightly higher success rate than other months. Refer to [Table 3 Successful Campaigns by Launch Month](https://github.com/adriana-icasiano/Excel-Challenge/blob/ba0cbe901e4c649212892871ba9321deb16738cf/Chart%209.PNG)

![Successful Campaigns by Launch Month](https://github.com/adriana-icasiano/Excel-Challenge/blob/ba0cbe901e4c649212892871ba9321deb16738cf/Chart%209.PNG)

   > b) The duration of successful campaigns varied between 2 to 90 days; however, the average duration is 30 days.
   
   > c) The goal amount for successful campaigns ranged from $1 to $400,000, and the median goal amount is $3,500. The upper bound for outlier for goal is $22,750. Tyically campaigns that failed or cancelled have relatively high dollar amounts. Refer to [Table 4 Goals Dollars by State and Subcategory](https://github.com/adriana-icasiano/Excel-Challenge/blob/3bd6d2c56fa51723346032022a7053ae0a1301ef/Chart%2013.PNG) and [Table 5 Goals Scatter Plot](https://github.com/adriana-icasiano/Excel-Challenge/blob/3a202e31f417086dffe65c9dbf2ffb0b823c8376/Chart%2016.PNG)
   > 
![Goals Dollars by State and Subcategory](https://github.com/adriana-icasiano/Excel-Challenge/blob/3bd6d2c56fa51723346032022a7053ae0a1301ef/Chart%2013.PNG)

![Goals Scatter Plot](https://github.com/adriana-icasiano/Excel-Challenge/blob/3a202e31f417086dffe65c9dbf2ffb0b823c8376/Chart%2016.PNG)


   > d) The median percent pledged is 112% of goal. The upper bound for outlier is 189% of goal meaning it is highly unlikely for the pledge amount to go beyond this percentage.

   > e) The lower the goal amount the higher likelihood of success except for the goal range $15,000 and 19,999. Goal set between $15,000 and 19,999 has a 47% of chance of success, 45% of failure and 8% of cancelation, meaning there is only a 2% gap in the chance of success and failure. Refer to  [Table 6 Goal vs. Percentage Pledge]( https://github.com/adriana-icasiano/Excel-Challenge/blob/bb782020a2b83f9cec5b96901f4eb5db9eebfaa9/Chart%207.PNG)

![Goals Vs. Percentage Pledge](https://github.com/adriana-icasiano/Excel-Challenge/blob/bb782020a2b83f9cec5b96901f4eb5db9eebfaa9/Chart%207.PNG)

### 3) Use of spotlight or other marketing assistance may reduce failure rate. ### 
In general, all campaigns that used spotlight were successful and those who did not failed. To demonstrate this, we looked into the top three successful cateogries. Documentary and rock campaigns used spotlight had zero canceled or failed campaign. By contrast, in the theatrical plays sub-category, the goal dollars in failed campaigns exceeded sucessful campigns. This indicates the the high effectiveness of the spotlight and using it may reduce the failure rate. Refer to [Table 7 Spotlight vs. Success Rate](https://github.com/adriana-icasiano/Excel-Challenge/blob/0f278756ba7ffe2c27cd8243307e296186df0cc8/Chart%2012.PNG)

![Spotlight vs. Success Rate](https://github.com/adriana-icasiano/Excel-Challenge/blob/0f278756ba7ffe2c27cd8243307e296186df0cc8/Chart%2012.PNG)

## Data Limitation ##
> 1.  Many data values (e.g. goals, backers and percentage pledged) varied widely from the median, so it was hard to establish a trendline or clear on those values. The dots on the scatterplots appear too close together because of the outliers. 
> 2.	At only 4000 data points, it is hard to get an accurate analysis of the outliers. E.g. there was only one case with $400,000 goal and was successful. If there were more data available, and more outliers, I might then be able to analyze the patterns of the outliers and see if its consistent with those data points closer to the mean.
> 3.	The data doesn’t show how much money was spent on spotlight or other advertising/ marketing help from Kickstarter such as BoostYourCampaign services or other professional Kickstarter marketing companies.


## Additional Tables and Graphs ##
> 1.	A scatter plot of campaigns on a map so viewers can visualize how the usage spreadout geographically.
> 2.	A table of failed campaigns and spotlight attribute to analyze the impact of the spotlight feature. Did not having it possible cause the failure? Did having it not make an impact at all?
> 3.	Bar graphs of categories and sub-categories

## Bonus Statistical ##
> 1.	The dataset has many extremes. For example, the number of backers for successful campaigns has a minimum of 1 and a maximum of 26457. The average of this range which is 194.42 would not be representative of the population. Therefore, the median being the middle of the data would summarize more meaningfully. However, it seems that actually neither the mean or median is very meaningful in thise case and makes me wonder if a more advanced statistical analysis is neccessary.

> 2.	The variance of successful campaigns is much higher than the failed ones. This makes sense because there is no limitation as to how many backers can back a campaign. If it is popular it can have as little as 1 or as many backers there are to support the campaign. Failed campaign is likely to have 0 to a number of backers that tends to be low; therefore, there is less variability in the smaller range. 

