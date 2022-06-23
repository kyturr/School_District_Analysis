# School_District_Analysis

## Overview of School District Analysis

The purpose of this project is to analyze the performance in a city school system given the testing results of each of the students in the school system. From this data set we are able to judge the efficacy of the education the students received based on grade, school type, budget per capita, and school size. Using this data, districts may have insights on any adjustments they might want to make to future programs and budgets. This analysis takes into account the cheating disqualification of one of the grades at one of the schools, and reflects the adjustments in the challenge file. In addition, this project demonstrates proficiency in using pandas as well as python notebooks as a means to sort and analyze data.

##Results
461 students in the 9th grade at Thomas High School were complicit in the testing fraud. There were thus several consequences that echoed through the reports. In most all the cases, the stats were inflated by the dishonest results, but the specifics are as follows:
* For the district summary, the average in math score, as well as all the passing percentages were reduced by 0.1-0.3 percent. 

![image](https://user-images.githubusercontent.com/103979048/175188518-86a76e83-1a8b-4868-947e-cc0ad649f40a.png)

* The Thomas High School had reductions in average math scores, as well as all the passing percentages while the average reading scores actually improved by omitting the 9th grade scores.  All other schools were unaffected. 

![image](https://user-images.githubusercontent.com/103979048/175188564-327af3af-9a3a-405e-9cfe-f8d429143064.png)


* Even with the removed scores, Thomas High School remains the school with the 2nd greatest overall passing percentage.

![image](https://user-images.githubusercontent.com/103979048/175188621-92be09d8-f7fe-4879-a366-e82a2d35a53a.png)


* For the rest of the reporting, the data was not affected as either the data could not affect other categories (scores by grade) or the changes were too small to be reflected in the less precise reports.(scores by spending, size, and type). 
    * The per grade data for Thomas High School 9th grade was disqualified, all other data remained unchanged.
    * Thomas High has a per capita spending of $638, so the changes would be reflected in the third bin of $631-645 with decreases in average math score, and all the passing percentage categories and an increase in average reading score.  
    * Thomas High has 1635 students and qualifies as a Medium (100-1999) school. The removal would have the same effects as listed above.
    * Thomas High is a charter school. The removal would have the same effects as listed above.
    
 
 ![image](https://user-images.githubusercontent.com/103979048/175188769-8f7c15ce-48b0-4ca2-821a-8a529dd49896.png)

    
## Summary
After the removal of the ninth grade scores at Thomas High School,  several of the more precise summaries were affected. For each of the summaries, the math score, math passing percentage, reading passing percentage, and overall passing percentage deflated down fractions of a percent. In addition, the average reading score increased. While the omission of results did cause change, the result was small enough that many of the less precise summaries were not affected at all. Therefore, even with the problematic data the insights gained from the original reports still hold largely true. Thomas High School still performed second best in the district, small and medium schools still on average perform better than large schools, schools that spend less per student still perform better than those that spend more, and charter schools still outperform district schools. The cheating reflects poorly on Thomas High School but it does not skew the data trends at large.
