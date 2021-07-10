# Kickstarting with Excel

## Overview of Project
   - Analyzing with Excel how different campaigns fared in relation to their launch dates and funding goals. 
### Purpose
   - To provide Louise with more in depth analytical information to help with decision making on when to try and launch a kickstarter, and how much a campaigns goal affects success rate. 
## Analysis and Challenges
   - I will be showing, in two seperate graphs, how success rate of kickstarter challenges are affected by both date of launch and the goal amount respectively. 
### Analysis of Outcomes Based on Launch Date
   -Below is a line graph showing the number of successful, failed, and canceled theater kickstarters based on the month they were launched:
    ![image](https://user-images.githubusercontent.com/86524863/125148672-0e3d1380-e102-11eb-8e44-35a0ccd9dea7.png)

### Analysis of Outcomes Based on Goals
   -Below you'll find a line graph displaying the percentage of both successful and failed plays in $5,000 increments based on their goals:
    ![image](https://user-images.githubusercontent.com/86524863/125148681-1e54f300-e102-11eb-960b-7efb99b852a7.png)
    
### Challenges and Difficulties Encountered
   - Deconstructing the data from the launch date to find the year, then creating a pivot table to only display months gave a better understanding on what time of year was best to launch a kickstarter campaign. The data only gave epoch time which we converted into years first, then extracted the years from that and sorted them further by month in the pivot table. This was challenging but necessary to give a clearer picture from the dataset for Louise to base her decisions on.
   - Sorting the plays by goal amount and then summing those projects in their respective ranges gave a clearer picture of different plays all in the same range of goal amount. Making sure to count the right type, and also only the plays in the correct range and then summing them was challenging- but that allowed me to calculate the percentage of successful, failed, and canceled plays much easier.  

## Results

   - To improve the success rate when launching a kickstarter campaign, I can recommend launching the campaign in the months of May through July. The outcomes VS launch line graph shows that the number of successful theater plays launched during this time period was the highest compared to the other months. If we think about these summer months it does make sense- more kids are out of school, the weather is nice and more people are likely to have more free time and contribute to the kickstarter. 
 
   - The plays with lower goals: less than $1,000 and $1,000-$4,999 were the most successful at 76% and 73% respectively. Smaller goals are easier to attain so this is intuitive. The third highest success rate interestingly enough is a goal ranging from $35,000-$44,999 at 67%. Smaller goals are easier obtained therefore producing the highest success rates, but for more expensive plays the ideal goal range is $35,000-$44,999.

   - This dataset gave us much more data then we needed- parent categories such as technology, publishing, games, music et cetera- needed to be filtered out. Also the launched date being in epoch time posed conversion challenges to see the data in more understandable times.

   - I would like to see the correlation between number of backers and success rate. Do plays with more backers always equal a high success rate? Or does it depend more on the average amount of donation rather than amount of backers?

I hope this analysis has helped you in making the best decision on when to launch your kickstarter, and different goal values affect success rate. I wish you the best of luck and will be first in line to come see your play!
