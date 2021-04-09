# Excel-Challenge
In this Excel Homework, students are asked to analyze a dataset with 4,000 past Kickstarter projects and to uncover some market trends.

## Table of Contents ##
* [Summary](https://github.com/adriana-icasiano/Excel-challenge#Summary)
* [Analysis](https://github.com/adriana-icasiano/Excel-challenge#Analysis)
* [Data Limitation](https://github.com/adriana-icasiano/Excel-challenge#Data-Limitation)
* [Additional Tables and Graphs](https://github.com/adriana-icasiano/Excel-challenge#Additional-tables-graphs)
* [Bonus Statistical](https://github.com/adriana-icasiano/Excel-challenge#Bonus-Statistical)
## Summary ##
Kickstarter is a popular platform for crowdfunding campagins in the arts. Campaigns related to theater, music and film are the most common. Successful is defined as 100% or more of the fundraising goal was met. Documentary and rock music campaigns have zero failure rate, while theatrical plays campaigns have a higher failure rate than success rate. The high failture rate of theatrical plays campaigns may benefit from more targeted marketing assistance from Kickstarter.

## Analysis ##
### 1. The majority of Kickstarter campaigns are in music and film in the US, Canada and UK.   
The top three most successful categories are in the Theater, Music and Film & Video categories. Within those categories, the top three most successful sub-categories are theatrical plays, documentary and rock music.  Refer to  [Table 1 Successful vs Failure Percentages by Category](https://github.com/adriana-icasiano/Excel-Challenge/blob/9ffd2485729ed910c9da63ddc2c2a7a5e59f67e0/Chart%203.PNG)

![Successful vs Failure Percentages](https://github.com/adriana-icasiano/Excel-Challenge/blob/9ffd2485729ed910c9da63ddc2c2a7a5e59f67e0/Chart%203.PNG)

### 2) Successful campaigns provide pointers for key campaign attributes. ###
   > a) While the other months have similar number of successful campaigns, the month of May have a slightly higher success rate than other months. Refer to [Table 2 Successful Campaigns by Launch Month](https://github.com/adriana-icasiano/Excel-Challenge/blob/ba0cbe901e4c649212892871ba9321deb16738cf/Chart%209.PNG)

![Successful Campaigns by Launch Month](https://github.com/adriana-icasiano/Excel-Challenge/blob/ba0cbe901e4c649212892871ba9321deb16738cf/Chart%209.PNG)

   > b) The median campaign duration is 30 days. The duration of successful campaigns varied between 2 to 90 days; however, the average duration is 30 days.
   
   > c) The median goal amount is $3,500. The goal amount ranged from $1 to $400,000. However, the median goal amount is $3,500, and the upper bound for outlier is $22,750. Tyically campaigns that failed or cancelled have relatively high dollar amounts. Refer to [Table 3 Goals Dollars by State and Subcategory](https://github.com/adriana-icasiano/Excel-Challenge/blob/addba171ae993d55a5a5a2f0e7a4457e7c9f5bc0/Chart%2010.PNG)
   > 
![Goals Dollars by State and Subcategory](https://github.com/adriana-icasiano/Excel-Challenge/blob/addba171ae993d55a5a5a2f0e7a4457e7c9f5bc0/Chart%2010.PNG)

   > d) The median percent pledged is 112% of goal. The upper bound for outlier is 189% of goal meaning it is highly unlikely for the pledge amount to go beyond this percentage.

   > e) The lower the goal amount the higher likelihood of success except for the goal range $15,000 and 19,999. Goal set between $15,000 and 19,999 has a 47% of chance of success, 45% of failure and 8% of cancelation, meaning there is only a 2% gap in the chance of success and failure. Refer to  [Table 4 Goal vs. Percentage Pledge]( https://github.com/adriana-icasiano/Excel-Challenge/blob/bb782020a2b83f9cec5b96901f4eb5db9eebfaa9/Chart%207.PNG)

![Goals Vs. Percentage Pledge](https://github.com/adriana-icasiano/Excel-Challenge/blob/bb782020a2b83f9cec5b96901f4eb5db9eebfaa9/Chart%207.PNG)

### 3) Fundraisers for theatrical plays may benefit more targeted marketing assistance from Kickstarter. ### 
While many campaigns are started in the the theatrical plays sub-category, this particular sub-category had failed campaigns than other popular sub-cateogires such as documentary and rock campaigns, which had zero canceled or failed campaigned - i.e. a success rate for those subcategories was 100%. Further, the total goal in dollars for failed campaigns is higher than successful campaigns. 100% of failed theatrical campaigns did not use the marketing feature "spotlight" and all successful campagins did use the marketing feature, which indicates the high effectiveness of the tool. Refer to [Table 5 State of Campaigns by Subcategory](https://github.com/adriana-icasiano/Excel-Challenge/blob/8478346951723cd4961c65631e160ebb64acf870/Chart%208.PNG)
f
![State of Campaigns by Subcategory](https://github.com/adriana-icasiano/Excel-Challenge/blob/8478346951723cd4961c65631e160ebb64acf870/Chart%208.PNG)

## Data Limitation ##
> 1.  It was difficult to find a representative median from the data because the goals varied widely. 
> 2.	There are very limited successful datapoints. At only ~4000 data points, it is hard to get an accurate analysis and create meaningful trendlines. 
> 3.	The data doesn’t show if any money was spent on efforts spent on advertising or marketing help from Kickstarter such as BoostYourCampaign services or other professional Kickstarter marketing companies.
> 4.	There are various outliers that make it challenging to analyze the data. For example, the campaigns with goal amounts of $1 to $50 are outliers, but they skew the data for successful campaigns


## Additional Tables and Graphs ##
> 1.	A scatter plot of campaigns on a map so viewer can get an idea of how the usage spreadout geographically.
> 2.	A table of failed campaigns and spotlight attribute to analyze the impact of the spotlight feature. Did not having it possible cause the failure? Did having it not make an impact at all?
> 3.	Bar graphs of categories and sub-categories

## Bonus Statistical ##
> 1.	The dataset has many extremes. For example, the number of backers for successful campaigns has a minimum of 1 and a maximum of 26457. The average of this range which is 194.42 would not be representative of the population. Therefore, the median being the middle of the data would summarize more meaningfully.

> 2.	The variance of successful campaigns is much higher than the failed ones. This makes sense because there is no limitation as to how many backers can back a campaign. If it is popular it can have as little as 1 or as many backers there are to support the campaign. Failed campaign is likely to have 0 to a number of backers that tends to be low; therefore, there is less variability in the smaller range. 

