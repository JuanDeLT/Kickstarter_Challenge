# Kickstarting with Excel

## Overview of Project

    This project seeks to identify trends in Kickstarter campaign data.

### Purpose

    The specific purpose of this project is to help our client determine the efficacy of previous Kickstarter 
    campaigns in reaching their goal given their launch date and their target goals. This analysis is done through
    both tabular data and their corresponding visual graphs.

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date

    'screenshot


    Firstly, the analysis of Outcomes based on Launch Date demonstrably shows a relationship between when a 
    theater campaign is successful and when it is launched. This graph's y-axis is based on the total number 
    of campaigns in its respective category, while the x-axis is the month they were launched. It is apparent 
    that time of year that a campaign is launched likely affects whether or not it will succeed. Specifically, 
    during the months of May and June there is a marked increase in the amount of successful campaigns. 
    Interestingly, there is also an increase in the amount of failed campaigns during this time, but it is not 
    alone as their are other times of the year when campaigns launch and fail just as much. 

### Analysis of Outcomes Based on Goals

    'screenshot

    Secondly, the analysis of Outcomes Based on Goals also reveals some interesting relationships between the 
    goals of the play campaigns and their success. There seems to be an inverse relationship between the number of 
    successful and failed campaigns given their campaign goals, but this relationship is likely explained by the 
    fact that it is based on percentages of the outcomes with respect to the total amount of campaigns in a given
    value range. The most successful campaigns are in the sub-$1,000 to $5,000 range, with some successes in the 
    $35,000 to $4,499 range.

### Challenges and Difficulties Encountered

    The primary challenges were in the organization and exclusion of specific data for the analysis.
    
    The organization of the Pivot Table for the Theater Outcomes Based on Launch Date required some thought, 
    but it did not create any serious issues. However I do think that the organization and exclusion of the 
    data could result in some issues. 

    Some of the challenges in this analysis were extracting the correct data that was needed from the entire 
    Kickstarter dataset. There were times when the data extracted were too inclusive, specifically when constructing 
    the Outcomes Based on Goals graph, so that it was not representing what it was intended to represent, and 
    instead showed larger sect of the data than intended.

## Results

- Two conclusions you can draw about the Outcomes based on Launch Date

    It is apparent that other campaigns are aware to launch at around the same times, since the number of successful launches coincided with an increase in failed launches as well. This would indicate to some degree there may be some "best practices" to follow to give your campaign a better shot that people are aware of, like launching during the beginning of the summer months. 

- Conclusions about the Outcomes based on Goals

    It is abundantly clear that campaigns that had larger goal amounts fared worse than those with smaller goals, with some exceptions in the $35,000 to $4,499 range. The inverse relationship is obviously apparent, as goal amounts increase, the chances to succeed decrease. It would be advisable to maintain the goal of the campaign to sub-$5,000.

- Limitations of this dataset

    This dataset offers a lot of information that could be used for all sorts of interesting analysis. One potential downside of this dataset is that it does not contain the creators of the campaigns. It would be enlightneing to see how many campaigns they had run before and how successful they were in those campaigns. Perhaps there is some level of reputation that goes into successful campaigns that could explain the anomalous results in the $35,000 to $4,499 range in the Outcomes Based on Goals analysis.

- Other possible tables and/or graphs that we could create

    An interesting graph that would be interesting to see would be one which combined both of the mentioned characteristics into one. A graph showing how successful campaigns are given BOTH their goals and their release date would be very informative for this analysis.
