 # Data-Analysis-Journey---EXCEL-Project
## This is a documentation of my EXCEL lesson Project. 

In a bid to solidify my knowledge of  __EXCEL__ as a student of Biomedical Engineering aiming to delve into Data Analysis and research, I decided to work on a __Mental Health survey of Workers__. 

## PROJECT TOPIC: MENTAL HEALTH RISK OF REMOTE WORKERS
### Table Of Content

### Project Overview

The younger generation of workers mostly believe that remote work is a flex. While that might seem true, in regard to flexibility and freedom, it still does not guarantee that remote workers would be exempted from other issues like the mental health risk, that a conventional employee might have to deal with in the work space. 

The mental health of workers is a very crucial topic to consider. And while remote work seem like an escape route, this analysis aims to bring perspective to how much remote workers are likely to be at risk of mental health issues.   

### Data Source and size
- The data used for this analysis is a mental health survey among workers - Remote, Non-remote and Hybrid.
- The data was gotten from Kaggle.
- It contained a total of 3000 respondent

### Tools Used
- EXCEL <img width="3000" height="2000" alt="Microsoft_Excel-Logo wine" src="https://github.com/user-attachments/assets/9bdc7f4c-733d-48db-82a0-88c587cd8001" />
 [Download tool here](https://microsoft-excel.en.softonic.com/)

This is the only tool I used for;
- Data Cleaning and data manipulation, using Excel formulas
- Analysis, using Pivot tables
- A report dashboard, using an entirely new sheet in the workbook

#### Data Cleaning/Manipulation: 
Since the aim of the project is to analyze only the response of remote workers in the survey, I extracted the data for only remote workers into another sheet in the workbook using the Excel formula; 

```
=FILTER(Array, Including)
```
I removed some columns that were not necessary for the analysis. Also, I generated new columns from the exixting ones. 
- __Age Group__:
  - Youth 20 - 35
  - Young Adult 36 - 45
  - Adult 46 - 70
  - Elder 70 above

 - __Work-life-balance Group (WLB)__:
   - Poor Balance 0 - 3
   - Moderate Balance 4 - 6
   - Healthy Balance 7 - 10

I used the formula below for this processes;
```
=IF(Logical_test, Value_if_true, [Value_if_false] )
```
Also, I did a count of the each age group using the formula;
```excel

=COUNTIF(Range, Criteria)

```

Using the burnout risk scale;

"0" for No burnout 

"1" for At risk of burnout

I did a count of respondent according to age group who are at risk and not at risk of burnout. See the formula below.

```excel
=COUNTIFS(Range 1, Criteria 1, [Range 2, Criteria 2]...)
```

For easier visualization I added a screenshoot of my outcome

<img width="1920" height="1037" alt="Screenshot 2025-09-06 093201" src="https://github.com/user-attachments/assets/01d85e0c-06f7-496a-a23d-bf82d71bfab0" />

#### Pivot Tables

I used Pivot Tables to smmarize the data into tables. These tables show 

          1. Work hours per week/ Sleep hours by Job role/ Dept
<img width="733" height="223" alt="Screenshot 2025-09-06 101847" src="https://github.com/user-attachments/assets/19800650-2700-4c70-8adf-ee121504acb2" />

           2. Burnout Risk By Age Group
<img width="335" height="146" alt="Screenshot 2025-09-06 095739" src="https://github.com/user-attachments/assets/fa8f7655-eb6f-4faf-bad5-58734ee49a34" />

            3. Average work hours per weel/ Sleep hours
<img width="565" height="144" alt="Screenshot 2025-09-06 101715" src="https://github.com/user-attachments/assets/fb5c3050-6882-41d8-a414-556d135ff648" />

             4. Commute time by WLB group
<img width="428" height="124" alt="Screenshot 2025-09-06 101726" src="https://github.com/user-attachments/assets/a0cabfc7-4715-4c62-a121-96c3df6ec777" />

             5. Max stress level by WLB group 
<img width="431" height="127" alt="Screenshot 2025-09-06 101735" src="https://github.com/user-attachments/assets/52e48849-08cd-4fc3-940c-17a4a0cdbf91" />

              6. Work hours per week/ Sleep hours by Country
<img width="607" height="207" alt="Screenshot 2025-09-06 101744" src="https://github.com/user-attachments/assets/ccce51aa-caed-4bdc-a8eb-2ee8da1075ba" />

               7. Average Burnout level by Country
<img width="428" height="205" alt="Screenshot 2025-09-06 101803" src="https://github.com/user-attachments/assets/bafc702e-754a-46a1-b48c-e563e17f2215" />

               8. Max Burnout level by Age group 
<img width="386" height="148" alt="Screenshot 2025-09-06 101818" src="https://github.com/user-attachments/assets/ea8b1477-5f37-423c-b632-24f6190be2d7" />

#### Dashboard
Thereafter, I created a beautiful dashboard that explains my analysis at first glance. 

               WELL BEING METRICS FOR MENTAL HEALTH
<img width="1881" height="773" alt="Screenshot 2025-09-06 134015" src="https://github.com/user-attachments/assets/6c45105d-287a-44d3-ba32-7e5bda90e0e3" />

               JOB FACTORS OF MENTAL HEALTH
<img width="1887" height="774" alt="Screenshot 2025-09-06 134435" src="https://github.com/user-attachments/assets/6e8906de-3ce8-4574-8b7b-0fb017e4cc6f" />


### Limitations
The limitation of this analysis is in the sample size. After extracting the data for remote workers only, I had a total number of 988 respondents. However, the result cannot be generalized or conclusive as the number of respondent in each age group is not equal. For instance, the number of respondents in the Youth age group is more than those in the elder age group. So the analysis cannot profoundly say that one age group is at more risk compared to the other. I can only assume. 

### Analysis and Result
I didn't do much analysis with formulas, majorly used pivot tables to to do them.  

So from the analysis, youths and young adults show the highest burnout risk with a total of 121 and 94 rsptectively. Which would mean that these two age group are more vulnearble to mental health based on this metric of burnout. However, 

Although, looking from the WLB metric, 433 out of 988 reported an healthy balance. However, even though poor balance came out with the lowest number of 225 respondents, it was as a result of higher commute time and stress level. The stress level with 10 as its peak from the respondent, came from people with poor balance. Mind you, the poor balance group is populated by the youth and young adult with high commute time and stress level. Youth having the highest number of 359 commute time. This further solidifies the   

In lieu to work hours and sleep, the awerage work hours across the respondents is approximately 44 to 45 per week. The average work hour of the Elder age group - 45.6 however seem to counter the fact that youth and young adult age group are at more risk of mental health. Meanwhile, the Elders age group sleep less and they still have have a less burnout risk. This would mean that the quality of sleep above the duration of sleep, should be condidered of which the data is not available.   

Moving on, the analysis based on job roles, data scientists have the highest work hours per week. And this might be from imbalaced workloads, size of team. Having an average of 23.8, being the lowest. 

### Recommendation
- Organizations should create mental health awareness sessions focused on the youth and young adult age group.
- Make sure that team leads monitor workoverload to share fairly anomg team members.
- Organizations should partner with wellness providers for sleep hygiene training.
- Educate remote workers on how to balance work and life.

### Conclusion
This analysis shows that the the youger generation workers are at more risk of mental health problem than elders. This would mean that any initiative to mitigate the risk of mental health issues should prioritized this age group.

Follow me on GitHub 

Follow me LinkedIn 


