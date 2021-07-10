# Kickstarting with Excel

## Overview of Project

### Purpose

The purpose of this project is to recommend Louise the best possible Kickstarter campaign for her play *Fever* based on a dataset of several thousand 
crowdfunding Kickstarter campaign data to uncover trends. Specifically, we will be looking at Outcomes based on the launch date and goals of other Kickstarter campaigns. 

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date

To determine which date is statistically best for Louise to start her Kickstarter campaign for her play *Fever*, the Kickstarter data set was used to determine the
amount of successful, failed, and canceled Kickstarter campaigns by the month of the year the campaigns were started. Based upon the Kickstarter data set and the line graph below, 
we were able to determine that statistically the best month to start a campaign based on the amount of successful campaigns is May. Although May also has the most total campaigns
out of every other month, the percentage of successful campaigns are also greater than any other month as you can see by the large gap between the Successful campaigns (blue line)
and the Failed campaigns (Red line). Lastly, although there is a slight difference in canceled campaigns month to month, the changes are so small it should not affect which date
a campaign would begin. 
[GitHub Pages](https://github.com/taestylobster/kickstarter-analysis/blob/cdd7d461885696bade62840c50796afb396f0afe/resources/Theater_Outcomes_vs_Launch%202.0.png)

### Analysis of Outcomes Based on Goals

To determine which Kickstarter campaigns have the highest success rates based upon the initial requested outcome dollar amounts of the campaigns based upon the Kickstarted dataset,
the below line graph shows the percentage of successful, failed, and canceled campaigns based upon the initial requested outcome dollar amounts. From this data, we can see that
the range of successful campaigns that has a higher than 70% success rate is from less than $1,000 to $4,999. However, there is also a success rate over %60 from $35,000 to $44,999, 
which may be a better option depending on the specific situation for Louise's play. Lastly, it is also inherent that canceled plays reach their goal 0% of the time since they end 
prior to the end of the campaign and likely wouldn't be canceled if they were on track to fund the campaign.
[GitHub Pages](https://github.com/taestylobster/kickstarter-analysis/blob/05385767abd3ef9095c3548e56618a1c0f77b536/resources/Outcomes_vs_Goals.png)

### Challenges and Difficulties Encountered

The biggest challenge and difficulty I had when analyzing this data was trying to portray the best case scenario for what goal outcome Louise should utilize. There are many factors
such as location and level of production that I would think affect the amount of money Louise should try to raise. Sure, $1,000 to $4,999 has the highest success rate, but depending
on other factors of the play, Louise may need much more funding than that so a slightly lower success rate may be the better option. 

Another challenge I faced was trying to get the legend for the Theater_Outcomes_vs_Launch line graph in the correct order. It showed the order of the filtered column from the
spreadsheet in the order they were in the data set. I then realized I could filter the legend of the graph reverse alphabetically which gave me a more user friendly way to read
the line graph.

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?
The first conclusion I can draw is that the data for canceled campaigns is insignificant in the overall picture. There were so few campaigns that got canceled that it shouldn't
affect Louise's decision.

The second conclusion I got was that although May had the most failed campaigns, the amount of successful campaigns vastly outperformed the failed campaigns. If I was Louise, I
would try to start my campaign in May.

- What can you conclude about the Outcomes based on Goals?

I can conclude that the most successful campaigns tend to be ones that start with a lower requested goal amount. There is an exception to this at $35,000 to $44,999, but there is also
very few times campaigns used goals in this range.

- What are some limitations of this dataset?

One limitation is the amount of data for campaigns that have a much higher initial goal. This makes sense because typically plays in these ranges for production requirements will
already have money fundraised to make the play. This could also be because the data set has such a large amount of categories and subcategories.

Another limitation I noticed was the lack of data for where the campaigns were being held. We were only given the country of the campaigns, but cities would give a much better
picture for how much of a goal a campaign could generally request. Larger populated cities have a higher percent chance to make money for a play since it is an event consumers
need to physically attend, in my opinion.

- What are some other possible tables and/or graphs that we could create?

Instead of the percentage of Outcomes based on Goals, I would've used just the total amount of successful, failed, and canceled. Percentages are great except when your data values
are right skewed. Another possible table I would use is incorporating staff picks. I would like to know if the staff picks have a better chance at reaching their initial goal or not.
Lastly, I would definitely have looked at the average pledge amount more indepth. Do higher averages relate to less or more of a chance of reaching the goal? Are higher pledge amounts
related to which country, category, or subcategory type?
