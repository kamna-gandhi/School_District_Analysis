# Overview of the Project

## Purpose

The purpose of the analysis was to help Maria analyze student funding and student test scores. In order to help the school board make budget allocation decisions, school performance in math and reading was compared among the schools based on the amount of funding allocated to each school.Later, it was discovered that scores may be innaccurate for Thomas High School due to academic dishonesty, so data was re-analyzed to see if there were changes to the previous data.

## Results

### How is district summary affected?

#### Before re-analysis:
![Original](https://github.com/kamna-gandhi/School_District_Analysis/blob/main/Resources/Original_SchoolDistrictSummary.png)

#### After re-analysis:
![Reanalysis](https://github.com/kamna-gandhi/School_District_Analysis/blob/main/Resources/Reanalysis_SchoolDistrictSummary.png
)

As shown in the above dataframes, there wasn't a significant change in the district summary in the re-analysis when data from Thomas High School was omitted. The average math score, the % of students passing math and the % of students passing reading slightly decreased in the re-analysis. 

### How is the school summary affected?

Though Thomas High School's overall passing percentage decreased from 90.94% to 90.63% in the re-analysis, it still ranked second for overall % passing.

### Affect on reading and math scores by grade level
* Replacing 9th grader scores with NaN has no affect on the scores of other grades at other schools and THS. However, it affects reading and math scores for 9th graders at THS because NaN replaces score values for those who plagarized to 0, which slightly lowered the % of students that passed in the 9th grade.

### Affect on scores by school spending

#### Before re-analysis:
![OG](https://github.com/kamna-gandhi/School_District_Analysis/blob/main/Resources/OG_SpendingRanges.png)


#### After re-analysis:
![reanalysis](https://github.com/kamna-gandhi/School_District_Analysis/blob/main/Resources/Reanalysis_SpendingRanges.png)

* Since THS, falls into the $631-$645 per student spending range as shown in the dataframes above, the overall passing percentage, the average math and reading scores, the percentage passing math and reading all decrease slightly for this spending range. Otherwise, the affect on scores for other spending ranges reamain the same. 

### Affect on scores by school size
* Scores for medium sized schools decreased and followed similar trends to affect on scores by school spending because THS is a medium sized school.

### Affect on scores by school type
* Since THS is a chartered school, the average score values and passing percentages for chartered schools follow similar trends to discussed above. 

## Summary

Overall, only slight changes were seen for the categories that THS fell under. Otherwise, analysis for other schools and grades remain unaltered. 
