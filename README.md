# pandas_challenge

Table of Contents
- Project Description
- DataFrame Screenshots
- Project Writeup
- Jupyter Notebook

Project Description

The goal of this project was to analyze standardized test results and other metrics for a city's school district. I was tasked
with creating multiple DataFrames/summary reports for the schools and their students, and to analyze student performance
based on a variety of subgroupings to see what factors effect standardized test scores. The results provide valueable
information that can help inform decisions regarding school budgets and priorities, and help us understand what factors
influence student performance.

DataFrame Screenshots

District Summary
<img width="931" alt="DistrictSummary" src="https://user-images.githubusercontent.com/69160361/95664378-89868000-0b04-11eb-9982-bc182595b3de.png">

School Summary
<img width="1000" alt="SchoolSummary" src="https://user-images.githubusercontent.com/69160361/95664373-7d9abe00-0b04-11eb-9cb4-4421ecd28c0f.png">

Top Performing Schools (By % Overall Passing)
<img width="1008" alt="TopSchools" src="https://user-images.githubusercontent.com/69160361/95664383-96a36f00-0b04-11eb-81e5-60ada5f615bf.png">

Bottom Performing Schools (By % Overall Passing)
<img width="1000" alt="BottomSchools" src="https://user-images.githubusercontent.com/69160361/95664388-a02cd700-0b04-11eb-834a-5d184b45e7f6.png">

Average Math Scores by Grade


<img width="446" alt="MathScoresbyGrade" src="https://user-images.githubusercontent.com/69160361/95664392-ade25c80-0b04-11eb-82f4-5a89bfc7e3a1.png">



Average Reading Scores by Grade


<img width="444" alt="ReadingScoresbyGrade" src="https://user-images.githubusercontent.com/69160361/95664397-b9ce1e80-0b04-11eb-8c97-cfd47714e3f7.png">



Scores by School Spending
<img width="829" alt="ScoresbySpending" src="https://user-images.githubusercontent.com/69160361/95641321-dc0d6100-0a5e-11eb-80af-58fd91cb0009.png">

Scores by School Size
<img width="775" alt="ScoresbySize" src="https://user-images.githubusercontent.com/69160361/95641493-dd8b5900-0a5f-11eb-9e28-25c8d7507a13.png">

Scores by School Type
<img width="732" alt="ScoresbyType" src="https://user-images.githubusercontent.com/69160361/95641495-e7ad5780-0a5f-11eb-835c-45f6a9d88017.png">


Project Writeup
Describe two observable trends based on data

1) Charter schools outperform District schools significantly on average test scores and percentage of students passing. 
This is most observable when you compare the % of overall passing (% of students passing both math and reading), 
where charter schools have a 90% overall passing rate and district schools have a 53% overall passing rate. Further,
the top 5 performing schools (measured by % overall passing) are all Charter schools, and the bottom 5 schools are
all District type. This suggests that improving the test scores in District schools is a higher priority than for Charter schools, whose students are performing very well.

2) Per student budget has an effect on average scores, but not in the way one might assume. Schools who spend less per 
student actually have better scores than schools who spend the most per student. This suggests that the allocation of
financial resources should be re-examined, to see if there is a better way to spend that money (such as decreasing the
per student budget, but increasing funding for school resources to help with testing).

Conclusion: To maximize student performance across all schools in the district, District type schools should be prioritized
because of the significant difference between District and Charter schools in terms of student scores. The data indicates that per student budget does not need to be greater than $584, and schools who are spending more than that per student may want to consider reallocating those financial resources since they do not seem to help student performance. School size is also a factor, and the data shows that students at large(2000-5000 total students) schools perform the worst. This suggests that large schools should also be prioritized when trying to implement changes to improve student test performance.

Jupyter Notebook
The jupyter notebook for this project can be found at the link below:

https://github.com/jeosqueri/pandas_challenge
