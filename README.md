# School_District_Analysis
## Overview of Project
Analysis on performance of School Districts was performed using Jupyter Notebook with Python, Pandas and Numpy libraries.
School Board was provided with initial analysis based on our work by Maria; and they were somehow convinced on some anomalies in the data, in particular in the math and reading scores of the grade nine students at Thomas High School (THS). So, the Board asked to re-do the school district analysis with Maria after nullifying math and reading scores of all 9th graders from THS and share a detailsed report on the impact on different metrics analyzed earlier.

## Analysis Results

### District Analysis Impact
The change of removing math & reading scores for all 9th graders of THS did not have a large impact on the district analysis, with each metric decresing by less that 0.5%. It's important to consider there were only 461 students in grade 9 at Thomas High School, and given the total student count is 39,170, the grade 9 students only make up 1.2% of the total student count, so removing their math and reading scores can only have a very limited impact.

### School Ranking- Top & Bottom
The ranking of the **top schools** including THS was **NOT** affected by the update.
While the average math, reading and overall scores at THS were impacted with the update, the changes were not significant enough to have an impact on its relative ranking versus other schools. 
The ranking of the **bottom schools** was **NOT** affected by the update as the only metrics impacted where at Thomas High School as we are looking at each school's scores.

### Impact on Math & Reading Scores by Grade
The only score that were affected on this DataFrame were of the grade 9 students at THS that had Nan/Null value instead of a grade for both math and reading.

### Impact on Scores by School Size:
The scores for the Medium (1000-2000) size schools changed very slightly. They were impacted as THS was part of this group as it had total of 1,635 students who attended.

### Impact on Scores by School Spending
There was again a very miniscule change noticed in the scores by school spending for $630-644 grouping as this is where Thomas High School was grouped.

### Impact on Scores by School Type
Thomas High School was of the type 'Charter', so this is where a very insignificant change to the scores was seen. (again less than change of 0.1%), but no changes were observed  to 'District' type schools.

## Summary
**District** Analysis - The scores had changed by less than 0.5% percentage points 

**School Ranking** - No change to rankings, however Thomas High School scores did change.

**Scores by School Size** - Very slight changes to **Medium** (1000-2000) grouping for all scores by less than 0.1%.

**Scores by School Type** - Very low level change to **Charter** type grouping for all scores by less than 0.1%
**Scores by School Spending** - very unnoticable changes to **$630-644** grouping
