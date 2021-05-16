# School District Analysis

## Overview of School District Analysis
I was tasked with analyzing data from 15 schools in the district and putting it into a readable dataframe. After the initial data frames were completed,
additional analysis was done specifically looking at Thomas High School (THS). I was tasked with removing the 9th grade math and reading scores at THS and
determing how it affected the data frames that were originally created. After this was done, I looked at how the district summary, school summary, THS performance, math and reading scores by sgrade, scores by school spending, scores by school size, and scores by school type were affected.

## Results

- How is the district summary affected?
Attached is the original district summary, before 9th grade scores were removed from Thomas High School. The only changes that were noted with the edited data
is a change in the % Passing Math, % Passing Reading, and % Overall Passing (after editing, -0.2%, -0.3%, -0.1%).
![District Analysis Before](https://github.com/swlim314/School_District_Analysis_Week_4/blob/c5ca8edb8799b4a37925aecfacf729847339714b/Resources/District%20Analysis%20Before.png)

Attached below is the updated data after 9th grade data was removed from THS.
![District Analysis After](https://github.com/swlim314/School_District_Analysis_Week_4/blob/c5ca8edb8799b4a37925aecfacf729847339714b/Resources/District%20Analysis%20After.png)

- How is the school summary affected?
The school summary shows that for THS, the overall change in the % Passing Math, % Passing Reading, and % Overall Passing from the original to the 9th grade removed was very signficant, with an almost 30% drop in each of the categories. However, after the 10th-12th grade data was reincorporated and taken into account, the % Passing Math, % Passing Reading, and % Overall Passing ended up being less thant 1% different than the original data. This seems to have been due to the updated calculation with 9th grade scores counted as NaN negatively impacting the overall grades. With the 10-12th grade data being used as the only numbers for the final evaluation, the passing percentages ended up being relatively similar.
**School Analysis Before**
![School Analysis Before](https://github.com/swlim314/School_District_Analysis_Week_4/blob/f14f0b70c01b7951e1bca39056acf9b6649b7461/Resources/School%20Analysis%20Before.png)

**School Analysis after 9th grade data was removed**
![School Analysis Middle](https://github.com/swlim314/School_District_Analysis_Week_4/blob/f14f0b70c01b7951e1bca39056acf9b6649b7461/Resources/School%20Analysis%20middle.png)


**School Analysis taking into account 10th through 12th grade**
![School Analysis After](https://github.com/swlim314/School_District_Analysis_Week_4/blob/f14f0b70c01b7951e1bca39056acf9b6649b7461/Resources/School%20Analysis%20After.png)

- How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
  Replacing the ninth graders math and reading scores affects THS's performance relative to the other schools an insignificant amount (<1%). Shown below are the before and
  after of replacing the ninth graders scores as NaN.
 ![Top School Before](https://github.com/swlim314/School_District_Analysis_Week_4/blob/61f345eff8584a66f65403d53aa96c38ab45e5a5/Resources/Top%20Schools%20Before.png) 
 ![Top School After](https://github.com/swlim314/School_District_Analysis_Week_4/blob/61f345eff8584a66f65403d53aa96c38ab45e5a5/Resources/Top%20Schools%20After.png)
 
- How does replacing the ninth-grade scores affect the following:
 - Math and reading scores by grade
 
  Replacing the ninth graders' math and reading scores, without taking into account refactoring leaves us unable to compare relative performance. The Ninth graders scores for
  THS show up as NaN, compared to the other values that are shown for the 14 other schools. 
  
 - Scores by school spending
 
   There were no noticeable changes to scores by school spending. The percentages stayed the same because they were rounded to the nearest percent.
   
 - Scores by school size
 
   Similar to above, there were no noticeable changes to scores by school size.
   
 - Scores by school type
 - 
   Finally, looking at school type, there were no changes that were noticeable.
 
## Summary
Some of the changes after refactoring the math and reading scores are the addition of NaN to the scores when looking at THS in comparison to other high schools. Additionally,
when solely removed the 9th grade scores without recalculating the remaining passing rates for 10th through 12th grades, THS took a hit in math, reading, and overall passing
scores, at almost a 30% difference. 
