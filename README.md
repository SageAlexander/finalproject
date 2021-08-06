# Final Project
### Data By Sage Alexander <br>

This project was made possible by data from the Wall Street Journal, [Where it Pays to Attend College; Salaries by College and College Degree Program](https://www.kaggle.com/wsj/college-salaries/) and Payscale, Inc. 

My google sheets spreadsheet can be found [here.](https://docs.google.com/spreadsheets/d/1mSPW5yizGISr7Jcihzyeh2KGPuX2E4rtufE7YaNjahE/edit?usp=sharing)
Before I started, I froze and bolded the header row. On the College Type spreadsheet, I added a column for TYPE of school for ease of pivot tables. 

#### QUESTIONS:
*1. Are liberal arts colleges doorways to higher earning potential compared to other school types?*



!['screenshot1.JPG', 'College Type Earning'](/screenshot1.JPG)


To answer this question....
1. I made a pivot table on Google Sheets. 
2. I made my 'Row' was type of college
3. I made my 'Values' as Mid-Career Median Salary, Starting Median Salary, and Mid-Career 90th Percentile Salary. I chose these three values to show the median salary of a well established professional in the field, a recent college graduate, and the highest earners from the college. The starting salary did not tell me much, other than an increased earning potential for recent Ivy league graduates. 
4. I summarized the data by average and sorted by type.

> Liberal arts colleges are, on average, more expensive to attend than public universities. The mid-career median salary for the Liberal arts and Party type of schools are not significantly different, with Liberal Arts school attendees salaries about 5 thousand dollars more per year. If a student incurs significant debt from the more expensive Liberal Arts colleges, it may not be financially wise to attend one over a state/party school. However, the 90th percentile earners from Liberal Arts colleges do make $191,142.86, compared to $166,947.3 for party schools and $173,333.33 for engineering schools. Mid career, high earners from liberal arts colleges therefore earn slightly more on average than those from the two types of schools.

*2. Are party schools any different from state schools in terms of earning potential?*

!['screenshot1.JPG', 'College Type Earning'](/screenshot1.JPG)

To answer this question, I used the same pivot table as before, but instead looked at the state and party schools. 


> Party school attendees actually made *more* each year than those who attended state schools. In average mid career median salary, starting median salary, and mid career 90th percentile earners, party school attendees make slightly more on average. Starting median salaries are not significantly different, but are higher by over a thousand dollars. 

*3. Do you make more money if you graduate from certain U.S. regions?*

!['screenshot2.JPG', 'Salaries by region'](/screenshot2.JPG) 


To answer this question...
1. I made another pivot table. 
2. I made my row was region of the U.S
3. I set my value as mid-career median salary, sorted by average. I chose this value because I believe that it encompasses a data point that covers the most general statement about graduates. 


> Both California and the Northeastern regions make $93,132.14 and $91,352.00, respectively. This, compared to sub-80k salaries in the other regions, shows that graduates that attend colleges in these two areas gross higher salaries, on average. 


*4. What stem careers see earning potential stagnate?*


!['screenshot3.JPG', 'STEM majprs with lowest percent change in salary over careers'](/screenshot3.JPG)


To answer this question...
1. I sorted the percent change from Starting to Mid-Career Salary from lowest to highest
2. I found which majors are considered STEM (Science, Technology, Engineering, Math) with [this website](https://www.act.org/content/act/en/research/reports/act-publications/condition-of-stem-2013/stem-majors-and-occupations/stem-majors-and-occupations.html)
3. I manually set the STEM majors that are in the bottom ten majors by percent change in salary to italics.
4. I then sorted the list by starting median to learn more

> The three majors with the lowest change in salary over a carreer were STEM majors. Physician Assistant, Nursing, and Nutrition majors see a 23.4, 23.6, and 38.6 change respectively. Physician Assistant starting median salary is relatively high at $74,300.00, the highest starting salary out of all majors on the data sheet. The mid career median reaches $91,700.00. Nursing, on the other hand, is number 9 out of the starting salary list at $54,200.00, but only reaches $67,000.00 at mid career median. For reference, philosophy majors reach a mid career median of $81,200.00.


*5. Are there any liberal arts majors that end up making lots of money?*
