# kickstarter-analysis

## Overview of Project
As Louise’s upcoming play Fever came close to its fundraising goal and she wants to know how different campaigns resulted in based on their launch date and fundraising goals. Using my visualization on some key factors from the Kickstarter dataset I have discovered some great outcomes which can provide Louise knowledge about how other plays performs throughout the year. The main purpose of this analysis is to check if Louise's campaign goal have any outcomes that she might not be prepared for, provide her with some recommendation, fundraising goal and launch date suggestion for her play.

## Analysis and Challenges

### Analysis
- During the analysis of [Outcomes Based on Launch Date](https://drive.google.com/file/d/1c9JZMQwiextQ4dRE9LcV1LnGByaJoVtB/view?usp=sharing) I have analyzed that, the most successful plays are performed in May during the given period of time, followed by June as second most successful month of the year. On the other hand in December the number of failed and successful plays are very close to each other.

 - [Outcomes Based on Goals](https://drive.google.com/file/d/15wOHLlJ2hsoskNQHGMKmwkS8W2rnld_U/view?usp=sharing) have shown that, campaigns with fundraising goal value up to  $5000 were the only most successful one with percentage between 73-76%.  In addition, campaigns with Goal value between $35000-$45000 were also successful (67%) but not as much as the ones below $5000 range. On the other hand, campaigns with goal value above $45000 and below $50000 were encountered as most failed fundraising goal campaigns.

### Challenges during the analysis
 
- First of all,  I have encountered that given dataset needs to be properly filtered and sorted properly before using it to perform any analysis. 
- The dates provided in Unix timestamps needs to be changed to human date and years in order to get outcomes based on launch date.
- Further to get a average donation value there were some mathematical errors in dataset because some campaigns had no backers at all, which was giving wrong value and there errors needed to be resolved so that mistakes can be avoided while using that data to create Pivot tables and Charts.

## Results
### Based on outcomes form launch date
- To conclude, based on outcomes based on launch date, Louise should plan to have the play performed during the month of May, because as per the data plays during this month were most successful.
- Secondly, she should avoid to have the play during the month of December, because during this month the number of failed plays are very close to number of successful plays so there are risks of play failure.
### Based on outcomes from fundraising goals
- The data provided to us based on fundraising goal have shown that, Louise should keep her goal under $5000 to get the most successful percentage (73-76%) of plays, moreover she can plan to have the goal amount set between $35000 and $45000 , where the success percentage is almost double of the fail percentage. With her own goal value of about $12000 the success rate is barely above 50% and with failure percentage of 46 percent.

### Limitation of dataset and recommendation.
There are always some limitation need to be considered with each dataset, first of all the data provided is not always from the entire number of campaigns occurred in past. Some very successful or failed campaigns could be not recorded in the dataset many reasons. which can affect the percentages we calculated by a lot and give us wrong/inaccurate numbers of campaign results. 
My recommendation to Louise is to get additional data about the audience such as age group and gender(m/f) of the people coming to see plays. From this data I can provide her with additional chart about which age groups and genders are coming more to see the plays.  Secondly, she can have the information about the cities in which plays were performed to get the idea if the successful or failed shows are in big cities or small, because if a successful play was performed somewhere in New York city and a failed play was performed in some county area these are totally different scenarios.
