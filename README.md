# School District Analysis

## Overview

The purpose of this project is to analyze the school district data and perform and analysis based on several different metrics. The analysis has to be redone since it is suspected that the 9th grade students from the _Thomas High School_ have committed academic dishonesty. The key performance metrics for each school are: math and reading scores. Each school's data points include: budget, school type, and total number of students .From the resulting analysis, the district will be able to determine budget necessities and allocate the correct amount into each school.

## Results

- ### How is the district summary affected?

  - The effect that the modification has on the district summary is negligible. It is imperative to note that even though the metric values changed, when rounding them to the nearest decimal, the values remained the same. The only value that changed after rounding was the average math score that went from **78.9** to **79**, which cannot be considered a significant change.

- ### How is the school summary affected?

  - The only change happened on the values from _Thomas High School_. Since the only difference from this analysis from the past one was that the Thomas High School students from the 9th grade were not included in the analysis, the school summary was affected only in one row. On the other hand, the results from that high school were dramatically different.
    - The overall passing grade went from **65.1%** to **90.1%**
    - The percentage of students who passed reading went from **69.7%** to **97.3%**.
    - The percentage of students who passed math went from **66.9%** to **93.3%**.
    - As for the actual point-based scores, there was no significant difference. Math scores went from **83.35** to **83.42** while reading scores went slightly down from **83.89** to **83.85**

- ### How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?

  - It had no effect whatsoever in the school rankings sorted by overall passing percentage. _Thomas High School_ was second in this list and remained in the same position after filtering out the students.

- ### How does replacing the ninth-grade scores affect the following

  - #### Math and reading scores by grade

    - This did not have a big effect. Now; however, we do not have any information regarding the 9th grade students from _Thomas High School_. It is easy to see from the following images that no other value was affected by this.
    - As for the average grade for 9th graders in reading, it decreased from **82.51** to **82.43**. While math average score decreased from **80.35** to **80.12**.

  - #### Scores by school spending

    - Schools spending scores suffered changes only in the range from $631 to $645. There was no change elsewhere because only data from one school in this category was modified.
    - While there was a change, it was completely insignificant in the bigger scale since the difference can only be seen before rounding, meaning that there was no important change.
    - The following images will provide a visual representation which will be easier to see:

  - #### Scores by school size

    - Since Thomas High School is a medium sized school, only that category's results were affected; however, after rounding, that difference disappears.
    - This is due to the fact that such a small number of students could not have had a big impact on the averages, especially since those scores reassembled the average.

  - #### Scores by school type

    - Just as for the other categories, the scores by school type had a negligible impact before rounding and no impact whatsoever when rounding. The rationale is the same as for the scores by school size; such a small number of students will not have a major impact.

## Summary

- The most important takeaway from this new project is that the removed data had a negligible impact on most performed calculations. When analyzing the scores by school type, school size, and expenditure per student, the key metric averages where almost identical.
- The big impact can be seen when analyzing the results just from _Thomas High School_. When done so, there are substantial differences from the results obtained in the previous analysis.
- This could be expected since such a small amount of data points could not have had a big impact in the overall metrics, especially since almost none of them were anomalies.
