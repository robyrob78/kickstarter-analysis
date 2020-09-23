# Kickstarting with Excel

## Overview of Project
Performing analysis on Kickstarter data to uncover trends

### Purpose
The purpose of this project was to analyze Kickstarter data in order to help our client, Louise, get a better understanding of why some Kickstarter campaigns are successful, and why others fail. 

## Analysis and Challenges
### Analysis of Outcomes Based on Launch Date
One of our main areas of focus when analyizing the data was to look at the successs rate based on the time of year the campaign was created. Once we narrowed the data field to focus on only theater productions, we were able to take that data and get a visual representation of success rates based on time of year. [this chart](https://github.com/robyrob78/kickstarter-analysis/blob/master/resources/Theater_Outcomes_vs_Launch.png) shows all of our data visualized based on success or failure and the time of year these campaigns were launched. As we can see from the chart the months of May, June, and July were cleary the most successful times to launch a campaign. While this data is helpful we also looked at another factor, the goal ammount of the campaign. 

### Analysis of Outcomes Based on Goals
The next variable we took into consideration when analyzing this data was the goal, or the ammount of money the original author of the campaing was asking for. We again had to narrow our data field to focus only on theater productions. Once we had that data, we were able to generate [this chart](https://github.com/robyrob78/kickstarter-analysis/blob/master/resources/Outcomes_vs_Goals.png) which shows the percentage of campaigns that were successful based on how much money they asked for. Unsurprisingly, the chart shows a general trend that the lower the goal amount, the more likely the campaign would be successful. From the chart we can see that the campaigns that had the most success, set their goal at $4,999 or less. 

### Challenges and Difficulties Encountered
One of the difficulties I encounterd while working on this project was using pivot tables. Initially, choosing the categories for the values and rows and columns didn't seem very intuitive. I knew what data I wanted to visualize, but I wasn't entirely sure which categories to put where. The more I worked with it and played around with choosing different categories, I started to see the relationships. Another area I struggled a bit with was the COUNTIF function. The initial function seemed daunting. There were a lot of letters and symbols and I wasn't really sure what it was saying. As I kept going though, I started to be able to read what the function was saying. Breaking it up into individual pieces made it much easier to understand rather than looking at it as a whole.

## Results
Looking at all the data we analyzed, we were able to draw some final conclusions. Based on the launch dates of the campiagn we can clearly see that the most successful months to launch a campaign were May, June, and July. We can also conclude that the least successful months were January, March, November, and December. The most successful time to launch would be in the middle of the year during the summer months, and the least succesful times were at the very beginning and very end of the year during the winter months. Therefore, our conclusion is that campaigns launched in May, June, or July have a higher probability of being successful than any other months with May being the highest. 

Next, looking at the outcomes based on goals, we were also able to draw a conclusion. Generally, the conclusion with this data is that the higher the goal, the lower the chances were that the campaign would be successful. We saw the highest rate of success with campaings that aksed for $4,999 or less. The success rate for campaigns that asked for less than $1,000 was 76%, and the success rate for campaigns that asked for between $1,000 to $4,999 was 73%. From there, the likelihood of success tends to decrease the higher the goal is. Our conclusion in this area is that the lower the goal amount, the higher the chances the campaign will be successful in meeting its' goal. 

Even though we were able to draw some pretty solid conclusions from our data, we do have to acknowledge some of the limitations. One limitation was the lack of data points or projects in the higher goal areas. For example, when looking at the [outcomes based on goals chart](https://github.com/robyrob78/kickstarter-analysis/blob/master/resources/Outcomes_vs_Goals.png) there is a spike in success in the ranges between $35,0000 and $44,999, however, there were only 9 projects in this range while the other generally successful areas had hundreds of projects. That is to say that although it might appear based on the graph that asking between $35,0000 and $44,999 was fairly successful, we didn't really have enough data in this range to say with any certainty that would be the general success rate. In fact, our more statistically significant data points to the contrary, that the higher the goal ammount, the lower the chances of success. Another limitation of our data is that people's tastes are subjective and some campaigns may have been more successful based on their subject matter, rather than launch date or goal. For example, someone putting on a play about Star Wars would gather far more recongition and have more mass appeal than someone who wants to do a play about a family of farmers during the 15th century or something obscure like that.

While we were able to visualize a lot of our data through charts and graphs, there is some other data that would have been helpful to visualize. One table that would be helpful would be to look at campaign goals by the month they were launched. Instead of just looking at whether the campaign was successful or not based on the month of launch, we could also look at what the campaign's goal was. Perhaps there were more campaigns with lower goals that launched in May, June, or July and that is skewing our data a little. Or we could confirm that, yes there were all different campaings with different goals launched equally throughout the year and May, June, and July were still the most successful months. 

Another table that might give us some insight would be to look at the average donations depending on the year and country. This might give us some insight into how the economy was doing that year. Countries with strong economies at the time might skew towards higher average donations and a higher amount of successful campaigns. Countries with weaker economies during certain years might tend towards lower average donations and a higher amount of failed campaigns. This would be helpful variable for people to assess the likelihood of success of their kickstarter based on their countries' curretn economic conditions. 
