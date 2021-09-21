# Schol_District_Analysis

## Project Overview
Analysis on school district performance using Jupyter Notebook with Python, Pandas Library and Numpy library.

The School Board would like to understand various performance metrics of the different school districts and schools.  We will first work with Maria (our contact) provide the initial analysis based on data collected from many students and schools across the school district.

While the School Board is pleased with the insight that we have provided in our work with Maria, it has been identified that there appears to be some anomalies in the data, in particular in the math and reading scores of the grade nine students at Thomas High School. In order to ensure these results do not skew the analysis, the Boad has asked us to again work with Maria to remove the impact of these results by changing all the grade 9 Thomas High School math and reading scores to Nan (which is a null value).

The School Board will like to understand the impact of changing all the grade 9 math and reading scores at Thomas High School to Nan - we will now review how this change impacted various parts of the analysis relative to when it was ran including the Thomas High School grade 9 scores.

## Resources
- Data Source: schools_complete.csv
- Data Source: students_complete.csv
- Sofware: Jupyter Notebook 6.3.0
- Library: Pandas
- Library: Numpy
- Language: Python 3.6.7

## Analysis Results

## Impact on District Analysis
***District Analysis - Original***

![Table_for_District_Analysis_Original](https://github.com/tessiertodd/School_District_Analysis/blob/main/Resources/District%20DataFrame%20Original.png)

***Top Schools - Updated***
![Table_for_District_Analysis_New](https://github.com/tessiertodd/School_District_Analysis/blob/main/Resources/District%20DataFrame%20Updated.png)
- The change of adding Nan to all grade 9 and Thomas High School math and reading scores did not have a large impact on the district analysis, with each metric decresing by less that 0.5 percentage point each (meaning scores changed by less than 0.5%).  It's important to consider there are only 461 students in grade 9 at Thomas High School, and given the total student count is 39,170, the grade 9 students only make up 1.2% of the total student count, so removing their math and reading scores can only impact the averages so much.

### Impact on the School Summary & Thomas High School Relative Performance
***Top Schools - Original***
![Table for Top Schools Original](https://github.com/tessiertodd/School_District_Analysis/blob/main/Resources/School%20Summary%20Top%20Original.png)

***Top Schools - Updated***
![Table for Top Schools New](https://github.com/tessiertodd/School_District_Analysis/blob/main/Resources/School%20Summary%20Top%20New.png)
-  The ranking of the top schools including Thomas High School was not affected by the update.
- While the average math, reading and overall scores at Thomas High School were impacted with the update, the changes were not enough to change its relative ranking versus other schools. The changes only had a small impact of less than a change of 1 percentage point on each metric.

***Bottom Schools - Original***
![Table for Bottom Schools Original](https://github.com/tessiertodd/School_District_Analysis/blob/main/Resources/School%20Summary%20Bottom%20Original.png)

***Bottom Schools - Updated***
![Table for Bottom Schools New](https://github.com/tessiertodd/School_District_Analysis/blob/main/Resources/School%20Summary%20Bottom%20New.png)
-   The ranking of the bottom schools was not affected by the update as the only metrics impacted where at Thomas High School as we are looking at each school's scores.


### Impact on Math and Reading Scores by Grade
***Math Scores - Original***

![Table with math scores original](https://github.com/tessiertodd/School_District_Analysis/blob/main/Resources/Math%20Scores%20by%20Grade%20Original.png)


***Math Scores - Updated***

![Table with math scores new](https://github.com/tessiertodd/School_District_Analysis/blob/main/Resources/Math%20Scores%20by%20Grade%20New.png)


***Reading Scores - Original***

![Table with reading scores original](https://github.com/tessiertodd/School_District_Analysis/blob/main/Resources/Reading%20Scores%20by%20Grade%20Original.png)


***Reading Scores - Updated***

![Table with reading scores updated](https://github.com/tessiertodd/School_District_Analysis/blob/main/Resources/Reading%20Scores%20by%20Grade%20New.png)

- The only score that is impacted on this DataFrame is that the grade 9 students at Thomas High School have Nan instead of a grade for both math and reading.  If we ran a sum or mean of the DataFrame, we would see a difference between the orignal and updated.

## Impact on Scores by School Spending
***Original***

![Table on score by spending original](https://github.com/tessiertodd/School_District_Analysis/blob/main/Resources/Scores%20by%20Student%20Spending%20Original.png)


***Updated***

![Table on score by spending updated](https://github.com/tessiertodd/School_District_Analysis/blob/main/Resources/Scores%20by%20Student%20Spending%20New.png)
- There was a slight change in the scores by school spending groups scores for the $630-644 per student grouping as this is where Thomas High School is grouped, however the change is small with each metric changing less than 0.1 percentage points (or change of less than 0.1%).


## Impact on Scores by School Size
***Original***

![Table for scores by school size original](https://github.com/tessiertodd/School_District_Analysis/blob/main/Resources/Score%20by%20School%20Size%20Original.png)


***Updated***

![Table for scores by school size updated](https://github.com/tessiertodd/School_District_Analysis/blob/main/Resources/Score%20by%20School%20Size%20New.png)
- The scores for the Medium (1000-2000) size schools changed slightly (less than 1 percentage point as we have seen with other calculations above).  They were impacted as Thomas High School included in this group as it has 1,635 students who attend (including the grade 9 students).


## Impact on Scores by School Type
***Original***

![Table for scores by school original](https://github.com/tessiertodd/School_District_Analysis/blob/main/Resources/Scores%20by%20School%20Type%20Original.png)


***Updated***

![Table for scores by school updated](https://github.com/tessiertodd/School_District_Analysis/blob/main/Resources/Scores%20by%20School%20Type%20New.png)
- Thomas High School is a Charter type school, so this is why we see changes to the scores for Charter (again less than change of 0.1% each metric), but no changes to District type school scores as Thomas High School not part of that group and no other school scores were affected.


## Summary
 - District Analysis - changes to all scores by less than 0.5 percentage points (or change by less than 0.5%) - no impact to school or student count.
 - Top School Ranking - no change to ranking, however Thomas High School scores did change, but by less than 1 percentage point (or changed by less than 1%) for each metric.
 - Scores by School Size - changes to Medium (1000-2000) grouping for all scores by less than 0.1 percentage points (or change by less than 0.1%).
 - Scores by School Type - chages to Charter type grouping for all scores by less than 0.1 percentage points (or change by less than 0.1%).
