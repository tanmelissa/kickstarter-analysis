# Kickstarting with Excel
## Overview of Project
### Purpose
This analysis is to help Louise gain the insights needed to create a successful Kickstarter Campaign to fund her new play, "Fever". This project will take data from Kickstarter and focus on the data for plays to gain insights on how to help Louise create a successful Kickstarter Campaign.
## Analysis and Challenges
### Analysis of Outcomes Based on Launch Date
Here is a line chart showing how many successful, failed, and canceled campaigns for plays there were each month of the year. This line chart was created by first creating a pivot table with filters including category and years, legend (series) including outcomes, axis (categories) including date created, and the values being the count of outcomes.

<img width="283" alt="Theater Outcomes Based on Launch Date" src="https://user-images.githubusercontent.com/102273449/166122600-6257ae9f-4f27-4a88-b597-bb0371308227.png">

This shows us that the months with the most successful campaigns were May, June, July, Aug, with February and March close behind. 

We can also see that the difference between the number of successful and failed projects changes with each month the project is launched in. From this data, I would recommend that Louise launches her Kickstarter in May.
### Analysis of Outcomes Based on Goals
Here is a line chart comparing the percentage of successful play campaigns vs the percentage of failed play campaigns by price range of their campaign goals. This was created by first counting the number of successful, failed, and canceled play campaigns in each goal range, then calculating the percentage of successful, failed, and canceled campaigns for each range.

<img width="396" alt="Oucomes_vs_Goals" src="https://user-images.githubusercontent.com/102273449/166122764-ed08f4a0-ae76-41ba-838d-64f354e1bfca.png">

We can see that from 0 to 19999 and from 35000 to 44999 had more percentage of successful campaigns than failed campaigns.
Although there are more campaigns that were successful than failed at Louise's budget of over 10,000, her budget is getting close to the range where the percentage of campaigns that fail is increasing and will soon exceed that of those that are successful.

Based on this data, I would recommend that Louise either lower her goal amount slightly, or to not increase it.
### Challenges and Difficulties Encountered
The most difficult part of this analysis was keeping track of when we wanted to filter by which categories. It was hard to keep track of when we wanted to filter by country. I felt that knowing a bit more about what Louise was looking for and what questions she specifically had and would like us to look into from the start would help me focus my analysis on answering her specific questions. This would help me to keep the end goal and purpose in mind through out the whole analysis.
## Results
### Conclusions from Theater Outcomes by Launch Date
In every month more campaigns succeed than fail. (You can note that there isn't much of a difference in December. In addition, if you filter for country, you see the number of successful and failed campaigns are equal in December. If you also filter for plays, there are more failed campaigns in December than successful ones.)

However, I would recommend that Louise start in May because the data shows that there is a greater chance of success if the campaign is launched in that month. In May 111 campaigns were successful, 52 failed, and 3 canceled meaning 67% of campaigns succeeded, the highest percentage of successful campaigns per month.

### Conclusions from the Outcomes based on Goals
The goal range with the highest percentage of successful campaigns was less than 1000, with 1000-4999 and 35000-39999 close behind. The only other range with a higher percentage of successful campaigns than failed campaigns was 5000-9999 and 10000-14999.

The goal range from 15000 to 35000, and 40000 and above are the most risky. The percentage of failed campaigns is higher than the percentage of successful campaigns in these goal ranges.

I would recommend that Louise keeps her goal under 15000, or to keep it within 35000 to 39999.

### Limitations of this dataset
1. Sample size. There are only 1369 total theater campaigns, with only 900 being in the US, and 662 in the US and plays. Having more data would allow us to see more trends and to see trends amongst the campaigns that are the most similar to Louise's.
2. This data is a bit old. It spans 2009-2017. However, more recent data may help Louise get a better picture of what is happening on Kickstarter now. Especially since theater has suffered since the pandemic. These numbers and also the success rates we gather from them may no longer give us an accurate picture of what is happening now.
3. This dataset doesn't give us information outside of Kickstarter. We do not know if or how the Campaign was advertised. It's very likely that there are many outside factors that affect the success rate, however, this dataset does not give us that information.

Further analysis of the length of the campaign and the success rate would give us more insight into how long Louise should have her campaign for. We could also narrow our current charts and graphs to include only the US and only campaigns for plays to focus our attention on campaigns that most closely resemble her own. We could also examine the blurbs for each of the plays in the US and divide them into categories. This would allow us to examine the plays that are most like her own which could give us additional insight on how likely her campaign is to succeed.

