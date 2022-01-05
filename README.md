# Student Success and Teacher Salaries in Tennessee
_Do better-paid teachers make higher-achieving students?_

## Table of Contents
- [Motivation] (#Motivation)
- [Data Question] (#Data-Question)
- [Research and Findings] (#Research-and-Findings)
- [Challenges and Further Research] (#Challenge-and-Further-Research)
- [Technologies and Data Sources] (#Technologies-and-Data-Sources)

## Motivation
To put it simply, my wife and I are heavily involved in education; she's a middle school social studies teacher, and I've spent all of my career so far working in higher education. Because of this, we both have a passion and natural curiosity for learning and teaching. Ultimately, through this project, I wanted to explore issues that are near and dear to most teachers: student success and wage suppression. If you live in the U.S., you've more than likely heard the stories—teacher walkouts nationwide due to low salaries. Through this project, I hoped to gain some insight on this complicated issue.

## Data Question
The primary question I sought to answer is this: do higher paid teachers make better students?

Now, before I present findings, I want to put a few caveats in place. **First**, this issue is incredibly nuanced, and my research can only scratch the surface. I'll link some other studies for further reading at the end that help bring some alternative perspectives. **Second**, I limited this research to the state of Tennessee, specifically over the last three years because the narrow scope was much more manageable, and it's difficult to compare across states due to differences in local education systems. **Third and finally**, access to individual student and teacher data would be ideal for this project, but it was impossible to get that proprietary data from each school, so I worked with district level data. Now, onto the findings.

## Research and Findings
After compiling district level data for student performance and salaries, I decided to focus my analysis on four economic variables and two success variables. The economic variables were teacher salary, percentage of federal funding, percentage of state and local funding, and total dollars spent on a student. The success variables considered were ACT scores and graduation rate. Ultimately, I chose these success variables because they were available, easily comparable, and significant for a student's future.

Below, you will find a link to the interactive dashboard that will allow you to explore the correlation between the economic variables. Here's a brief summary of my conclusions:

- In Tennessee, teacher salary appears to have a statistically significant impact on student achievement among students of all kind. Examine the R2 and p-values in the trendline tooltip and you will find that teacher salary has the highest R2 value relating to average ACT scores when compared to the other economic variables.

- As federal funding goes up, teacher salary goes down – incidentally, so does student achievement.

- Grad rate seems to be steady regardless of economic variable.

- Ultimately, it’s a chicken or the egg question: do teacher salaries have strong relationship with achievement because of affluence, or is the variable independent? There's no way to draw a causal link between the two variables, but based on the evidence, there is reasonably strong evidence that teacher salary is one of, if not the best, places to put school funds.

Link to Dashboard: [Education Dashboard](https://public.tableau.com/app/profile/christian.mack8569/viz/education_dashboard_16397121544800/Dashboard1?publish=yes)

## Challenges and Further Research
As mentioned above, finding data was a challenge, and even when data was found, it was not very standardized. As such, this project has its limitations; a broader scope with individual student and teacher data would more than likely be the best way to answer this question. In the realm of this project, though, I think there are more variables that could be tested, and a weighting/normalizing of district cost of living would help to answer the chicken or the egg question.

If you're interested in a more global approach, you can find a 2019 article by Eric A. Hanushek, Marc Piopiunik, and Simon Wiederhold [here](http://hanushek.stanford.edu/publications/value-smarter-teachers-international-evidence-teacher-cognitive-skills-and-student-0) that has a similar conclusion to mine, but with a much broader scope.

Also, [here](https://journalistsresource.org/education/school-teacher-pay-research/)'s an article by Denise-Marie Ordway in Journalist's Resource that compiles quite a bit of research on the subject.

## Technologies and Data Sources
### Technologies
- Excel
- Python
- Jupyter Notebooks
- Tableau

### Data Sources
- TN Government: [Data Downloads](https://www.tn.gov/education/data/data-downloads.html)
- National Education Association: [Data](https://www.nea.org/research-publications)
- Data.gov: [District Shapefiles](https://catalog.data.gov/dataset/tiger-line-shapefile-2018-state-tennessee-current-unified-school-districts-shapefile-state-base)
