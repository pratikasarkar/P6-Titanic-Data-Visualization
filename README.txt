Summary:

In Titanic Disaster Female chances of Survival was more compared to Male. The passengers travelling in Class-1 were more likely to survive than the passengers travelling in Class-2, which inturn were more likely to survive than Class-3 passengers. Children and Young passengers survival was more likely compared to middle-aged and Senior-citizens.

Design:

The Survival Information and the Sex of the passenger are the two most important information in the dataset, so they were included along the y and x axis respectively.

I chose "Sex" to plot along the x-axis, so that the viewer can easily differentiate between the number of passengers surviving in each group.

I chose Bar chart, as "Sex" is a categorical variable and Survival Rate is a continuous variable; although bubble and scatter plot could have been used, but bar chart gave a better visual encoding for the same.

"Age" was another factor effecting the survival of the passengers, so I tried to integrate it into the chart by encoding it using the color hue, to make the viewers comfortable with the color encoding a legend was added to the chart.

"Pclass" i.e the class of the Passenger was also a significant variable driving the survival of the passengers in the titanic dataset, so I tried to integrate it into my graph by animating it automatically once, then giving the control over to the user to try and see the number of passengers surviving in each class by the navigation link provided in the side.

I modified the tooltip provided by dimple to show the percentage of different age groups people surviving in each category.

I included a title and some text at the right bottom of the graph to give an overview to the users about what the graph represents.

After Taking the Feedback from my friends, I tried to do the following modifications to my graph.

1.Filtered the dataset to removed the age group with "NA" as its value.
2.Gave text values to the age bucket like "young","middle-aged" etc, so that the viewer can easily relate to the graph. 
3.Removed the age var appearing in the right navigation tooltip.
4.Gave a title to my plot and included some text giving information about the total percentage of passengers surviving in the titanic disaster.
5.Enhanced the tooltip information provided in the bar chart to give the viewer more insight into the data.
6.Splitting the survivors into many subgroups based on age seemed a bit confused in the visualization, so I reduced the Age bucket size to 4 for better visualization.
7.Showed the percentage of survivors in each class instead of the number of survivors along the y-axis.


After reviewing the project, the reviewer Martin suggested some great insights on the graph and gave various suggestions about the changes in the graph. Following are the further changes I took care of : 
1. The title needed to be clearly explanatory. So I made sure to change the title from a generalized one to a more specific one.
2. Changed back from multiset bar to stacked bar chart as it was indeed difficult to read due to the width and the colors of the chart.
3. Corrected the figures to match in both index_2.html and index_3.html.
4. In the legend of index_2.html, the order of the legend is not correct. So corrected the order of legend in index_3.html.
5. To avoid the chartjunk, removed the unnecessary data from the tooltip which can otherwise be interpreted from the chart itself.
6. The color pallete choice is selected as I think it clearly shows different type of data in different colors and is thus easy for the readers to understand what exactly is happenning in the chart.
7. The age buckets have been chosen so as to get a check on what proportion of people for particular age group are onboard titanic. As the chart shows that the maximum frequency is for the age group ranging from 19 to 40. This could be mainly due to fact that titanic was mainly known for carrying the wealthiest people in the world, as well as hundreds of emigrants from Great Britain and Ireland, Scandinavia and elsewhere throughout Europe seeking a new life in North America.
8. The total number of passengers were not available in the previous version of the project. I made sure that the total number of persons on the ship was displayed.
9. NA is a value in the dataset which is assigned when there is no value available for the field. I made sure to remove the NA in chart 2 and chart 3 as it was seen in chart 1 and did not seem to give any information about the event.
10. I have made some changes in the data set as well as the chart to show more details with respect to the non-surviving people too. Have added a multiseries graph in combination with stacked bar chart.
11. Added labels below each bar to represent the survived and the died passengers.


Feedback: 

 Name : Abhijeet Chavan

    Survival for the persons between the age group of 18-40 was more both in the case of female and male.
    The total no of persons in the ship is not indicated.
    Number of female survivors is always more as compared to male.
    The Survival of female passengers is more in Class 1 as compared to class 2 and 3.
    On hovering over the side navigation bar a Pclass and Age appears, that age variable is confusing.

	
Name : Shubhendra Chauhan

    The females in all the 3 classes have survived more.
    Female survival rate is more.
    Females and people of the age group 18-40 have survived more.
    What the NA is in the age group?

Name : Sai Charan Adhurthi
 

    The females in all the 3 PClass have survived more.
    The age group representation are not ordered properly and there is no title in the plot.
    People of Class 1 and feamle passengers have survived more.
    Female passengers and Class 1 passengers have survived more.
    The ordering of the age groups and the total no of people in the dataset is not understood properly.