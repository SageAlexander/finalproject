# Final Project
### By Sage Alexander <br>

This project was made possible by data from the Wall Street Journal, [Where it Pays to Attend College; Salaries by College and College Degree Program](https://www.kaggle.com/wsj/college-salaries/) and Payscale, Inc. 

My google sheets spreadsheet can be found [here.](https://docs.google.com/spreadsheets/d/1mSPW5yizGISr7Jcihzyeh2KGPuX2E4rtufE7YaNjahE/edit?usp=sharing)
Before I started, I froze and bolded the header row. On the College Type spreadsheet, I added a column for TYPE of school for ease of pivot tables. 

#### QUESTIONS:
*1. Are liberal arts colleges doorways to higher earning potential compared to other school types?*



!['screenshot1.JPG', 'College Type Earning'](/screenshot1.JPG)


To answer this question....
1. I made a pivot table on Google Sheets. 
2. I set my 'Row' as type of college
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


*5. Are there any liberal arts majors in the top 10 median earners?*

!['screenshot4.JPG', 'top median earners'](/screenshot4.JPG)

To answer this question...
1. I selected the other columns I wanted to hide
2. I sorted Mid career salary by highest to lowest
3. Here, I looked up to try and find what qualifies as liberal arts. I was not able to find a real list of what is considered liberal arts.
4. Economics was the only one not on [this website](https://www.act.org/content/act/en/research/reports/act-publications/condition-of-stem-2013/stem-majors-and-occupations/stem-majors-and-occupations.html), but it seems like the category is a little squishy. For example, the University of Pennsylvania considers it STEM.

> No there are not. There is, however, a non-STEM major in the top 10 median earners, economics. If we look in other categories, like the Mid-Career 90th Percentile Salary, Philosophy is at #10, making the top 10 cutoff! Economics is #1, Finance is #2, Marketing is #7, Construction is at #9, which are all non-stem. I would probably not consider any of them other than marketing a liberal arts, either. 



# Is majoring in Nursing worth it?

### Story Pitch

Students pursuing a degree in Nursing are often looking for a stable career with good pay. The tradeoff that students accept is the hard work they put in as an undergraduate. Nursing majors have to keep high GPAs, take intense and difficult classes, and are often applying to programs that are heavily impacted (too many students are applying at once). While nursing major’s median starting salary is in the top ten of majors analysed by the Wall Street Journal at $54,200, their growing potential is limited. Nursing majors have a percent change from starting salaries to mid career salaries of only 23.6, the lowest of all majors analysed. Why are nursing majors not paid well for the high stress student lifestyle?

## Who I would contact

> National Nurses United, Press contact. Email press@calnurses.org Rachel Berger – (510) 433-2780

The national contact for the Nurses Union, Rachel Berger, will help put into context what the current market for working nurses is like. This kind of broad overview will help me understand whether or not gains have been made recently for nurses.

> Sharon Warner Associate Director and interim MSN (Entry into Nursing) Recruitment, Johns Hopkins University
> 410-502-7215 | swarner7@jhu.edu 

According to U.S. News and World Report, Johns Hopkins has the #1 nursing program in the U.S. Sharon Warner will help me understand if all Nursing students end up getting certified, and what Nursing students usually do after they graduate.

> Robert Rosseter
> rrosseter@aacnnursing.org
> (202) 463-6930, ext. 231

The American Association of Colleges of Nursing (AACN) put out a report in 2019 that studied the inadequate number of open seats for otherwise qualified nursing students, and Robert Rosseter is the contact. I can ask him why he thinks nursing students aren’t being paid that much if there’s a high demand and shortage of nurses.


## Data Sources:

> 1. Bureau of Labor Statistics, [Nursing](/https://www.bls.gov/oes/current/oes291141.htm#(2)) 

Occupational Employment and Wages, May 2020 29-1141 Registered Nurses. I can compare what the median wage for working nurses is for nursing majors. For example, it says “The median annual wage for registered nurses was $75,330 in May 2020.”, which is different than what the median annual wage is for nursing majors. 

> 2. The American Association of Colleges of Nursing, [2019 report](/https://www.aacnnursing.org/news-information/fact-sheets/nursing-faculty-shortage)

The American Association of Colleges of Nursing (AACN) published this report in 2019. In the report it said it “found nursing schools could not accept over 75,000 qualified applicants for baccalaureate and graduate nursing programs in 2018 due to inadequate faculty, clinical sites, classroom space, clinical preceptors and budgets”. 



