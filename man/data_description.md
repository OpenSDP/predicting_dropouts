## About the data

The data used in this guide is a set of simulated data for matriculating 9th 
graders in the state of "Faketucky." Definitions of the features used in the
guide are listed below. Response variable is indicator `dropout`, which
indicates if student eventually dropped out of high school or did not drop out
of high school.


### Definitions of features

The data used in this guide 

| File Column Location | Variable Name       |Definition                                                    | Type       | Range/Key  |
| :-----               | :--------           | :------------------------                                    | :--------  | :----------------------  |
| 11                   | `male`              | gender of student                                            | Indicator  | 0 = female <br> 1 =  male |
| 12                   | `race_ethnicity`    | race-ethnicity of student                                    | Categorical| Levels: <br> African-American <br> Asian/Pacific Islander <br> Hispanic <br> Multiple/Native America <br> White |
| 13                   | `frpl`              | indicator if enrolled in free or reduced price lunch program | Indicator  | 0 = not enrolled <br> 1 = enrolled | 
| 14                   | `iep`               | indicator if enrolled in special education program           | Indicator  | 0 = not enrolled <br> 1 = enrolled | 
| 15                   | `ell`               | indicator if enrolled in English language learners program   | Indicator  | 0 = not enrolled <br> 1 = enrolled | 
| 16                   | `gifted`            | indicator if enrolled in gifted program                      | Indicator  | 0 = not enrolled <br> 1 = enrolled | 
| 17                   | `ever_alternative`  | indicator if ever enrolled in alternative school             | Indicator  | 0 = never enrolled <br> 1 = enrolled at least once | 
| 20                   | `math_ss`           | scale score on standardized 8th grade math exam              | Percentage | Possible range: 0-100  | 
| 21                   | `read_ss`           | scale score on standardized 8th grade reading exam           | Percentage | Possible range: 0-100  | 
| 22                   | `pct_days_absent`   | percent of 8th grade school days marked absent               | Percentage | Possible range: 0-100  | 
| 24                   | `gpa`               | grade point average in 8th grade                             | Continuous | Possible range: 0.00 - 4.00  | 
| 33                   | `dropout`           | indicator if student eventually dropped out of high school   | Indicator  | 0 = did not drop out <br> 1 = dropped out | 


