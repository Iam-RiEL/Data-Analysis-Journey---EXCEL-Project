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

 - __Work-life-balance Group__:
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
[Result.xlsx](https://github.com/user-attachments/files/17611792/githubsales.xlsx)



### Limitations


### Project Structure


### Analysis


### Result


### Recommendation
