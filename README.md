# Kickstarting with Excel
Performing analysis on Kickstarter data to uncover trends related to the goal and launch date.

### Purpose
The client's play "Fever" came close to its fund raising goal in a short period of time, and would like to know how other kickstarter campaigns have fared in relation to launch dates and funding goals. The purpose of the analysis is to provide detailed information comparing the outcomes of theatre kickstarter campaigns in relation to both the initial goal and launch date.
## Analysis and Challenges
The analysis was conducted using data from kickstarter. The data used in this analysis are the successes, failures and canceled campaigns along with the dates related to each. Comparisons were drawn between these outcomes and both the launch date and the goals. 
### Analysis of Outcomes Based on Launch Date
One of the requested analyses is the outcomes of Kickstarter campaigns related to plays based on the the launch date of the campaign. In order to complete this analysis data was drawn from Kickstarter to compare the different outcomes of a given kickstarter campaign and the date the campaigned launched. The process involved creating a pivot table from the kickstarter data showing the months a camapaign was launched and providing the number of successes, failures, and cancelled campaigns in each month. Filters for the Parent Category and Years were added to the Pivot table as well. The Parent category was added so theatre based kickstarter launches could be focused on, and the Years category was added to allow the client to look into specific years if interested. A line chart (below) was then created to visualize the information provided.

![Theater_Outcomes_vs_Launch](https://user-images.githubusercontent.com/36859475/134844305-84343309-b6d4-4c1a-9fc9-f746d046f706.png)

### Analysis of Outcomes Based on Goals
Another requested analysis  is the Outcomes of Kickstarter campaigns for plays in relation to the goal of the campaign. Data was again drawn from Kickstarter, but this time to compare the different outcomes based the on the goal of the campaign. In order to perform this analysis a table was set up to organize the data into ranges based on the goal:
- Less than 1,000 
- increments of 5,000 increasing to 49,999 
- Anything greater than 50,000

The number of successes,failures, and canceled campaigns was then entered into each of the ranges. A total was found for each range and was then used to find the percentage of successful, failed, and canceled campaigns. These percentages were then used to create a line graph to visually show the percentage of successful, failed and canceled campaigns based on the the intial goal.
![Outcomes_vs_Goals](https://user-images.githubusercontent.com/36859475/134846207-f47af6fa-2e8e-4156-9ec3-4e7e444289c9.png)

### Challenges and Difficulties Encountered
No issues arose during the analysis, but some possible challenges that could have occured are:
- Data entry error
- Misunderstood scope of the information requested by the client
- Visualization of the information requested poorly captures the results

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?
One conclusion that can be drawn is that May would be the best month to launch a campaign. While May is biggest month for campaign launches it also has the largest increase in successful outcomes. Between April and May there is an increase of 40 successful campaigns with an increase of just 12 failures over the same time period. After May the failure rate remains pretty constant while successes mostly decline for the rest of the year. Another conclusion would be that a campaign should not be launched in December. At that point a campaign is as likely to fail as it is to succeed.
- What can you conclude about the Outcomes based on Goals?
    It can be concluded that remaining under $5,000 for a goal will give the best odds of having a succesful campaign. As the the goal increases up to 29,999 the success of a campaign decreases. At the the same time the total number of projects also decreases. The graph may show an increase from 20% to 67% between 25,000 and 44,999, but there are only a total of 9 projects at the 67% level of successin this range. This is compared to a total of 720 total projects from under $1,000 for a goal up to $5,000.
- What are some limitations of this dataset?It is possible to see these interesting trends, but there could be more insight provided as to the reason for these trends between the goal and start date. For instance more data could be gathered as to why May is the best month to launch a campaign to show what makes them more successful.
- What are some other possible tables and/or graphs that we could create?Months could be compared to the total funding provided to see if there is a correlation between a given month and the amount of money provided.A graph could be created to show total number of projects for the ranges on the Outcomes Based on Goals. This graph side by side with other graph already made would show the the decrease in projects as the goal increases.
