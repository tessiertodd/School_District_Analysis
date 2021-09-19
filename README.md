# Schol_District_Analysis

## Project Overview
Analysis on school district performance using Jupyter Notebook with Python, Pandas Library and Numpy library.

The School Board would like to understand various performance metrics of the different school districts and schools.  You first work with Maria (our contact) provied the initial analysis based on data collected from many students and schools across districts.

While the School Board is pleased with the insight that we have provided in our work with Maria, it has been identified that there appears to be an anomalie in the data that has been in the math and reading scores of the grade nine students at Thomas High School. In order to ensure these results do not skew the analysis, the Boad has asked us to again work with Maria to remove the impact of these results by changing all the grade 9 Thomas High School math and reading scores to Nan (which is a null value).

The School Board will like to understand the impact of changing all the grade 9 math and reading scores at Thomas High School so we will now review how this change impacted various parts of the analysis relative to when it was ran including the scores that were removed.

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
- The change of adding Nan to all grade 9 and Thomas High School math and reading scores did not have an impact on the district analysis.

### Impact on the School Summary & Thomas High School Relative Performance
***Top Schools - Original***
![Table for Top Schools Original](https://github.com/tessiertodd/School_District_Analysis/blob/main/Resources/School%20Summary%20Top%20Original.png)
***Top Schools - Updated***
![Table for Top Schools New](https://github.com/tessiertodd/School_District_Analysis/blob/main/Resources/School%20Summary%20Top%20New.png)
-  The ranking of the top schools including Thomas High School was not affected by the update.
- While the average math, reading and overall scores at Thomas High School were impacted with the update, the changes were not enough to change its relative ranking versus other schools. The changes only reduced any of the scores by 0.1% at most.

***Bottom Schools - Original***
![Table for Bottom Schools Original](https://github.com/tessiertodd/School_District_Analysis/blob/main/Resources/School%20Summary%20Bottom%20Original.png)
***Bottom Schools - Updated***
![Table for Bottom Schools New](https://github.com/tessiertodd/School_District_Analysis/blob/main/Resources/School%20Summary%20Bottom%20New.png)
-   The ranking of the bottom schools was not affected by the update.

### Impact on Math and Reading Scores by Grade

***Math Scores - Original***
![Table with math scores original](https://github.com/tessiertodd/School_District_Analysis/blob/main/Resources/Math%20Scores%20by%20Grade%20Original.png)

***Math Scores - Updated***
![Table with math scores new](https://github.com/tessiertodd/School_District_Analysis/blob/main/Resources/Math%20Scores%20by%20Grade%20New.png)

***Reading Scores - Original***
![Table with reading scores original](https://github.com/tessiertodd/School_District_Analysis/blob/main/Resources/Reading%20Scores%20by%20Grade%20Original.png)

***Reading Scores - Updated***
![Table with reading scores updated](https://github.com/tessiertodd/School_District_Analysis/blob/main/Resources/Reading%20Scores%20by%20Grade%20New.png)

- The only score that is impacted on this DataFrame is that the grade 9 students have Nan instead of a grade for both math and reading.  If we ran a sum or mean of the DataFrame, we would see a difference betweed the orignal and updated.

## Impact on Scores by School Spending
***Original***
![Table on score by spending original](https://github.com/tessiertodd/School_District_Analysis/blob/main/Resources/Scores%20by%20Student%20Spending%20Original.png)
***Updated***
![Table on score by spending updated](https://github.com/tessiertodd/School_District_Analysis/blob/main/Resources/Scores%20by%20Student%20Spending%20New.png)
- There was no change in the scores by school spending groups.

## Impact on Scores by School Size
***Original***
![Table for scores by school size original](https://github.com/tessiertodd/School_District_Analysis/blob/main/Resources/Score%20by%20School%20Size%20Original.png)
***Updated***
![Table for scores by school size updated](https://github.com/tessiertodd/School_District_Analysis/blob/main/Resources/Score%20by%20School%20Size%20New.png)
- SOMETHING WRONG WITH READING.. WHY DIFFERENT??

## Impact on Scores by School Type
***Original***
![Table for scores by school original](https://github.com/tessiertodd/School_District_Analysis/blob/main/Resources/Scores%20by%20School%20Type%20Original.png)

***Updated***
![Table for scores by school updated](https://github.com/tessiertodd/School_District_Analysis/blob/main/Resources/Scores%20by%20School%20Type%20New.png)
- The change did not impact the scores by school type.

## Project Learning
I have learnt that...

## Summary
