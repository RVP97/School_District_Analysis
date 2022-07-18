# School District Analysis

## Overview

The purpose of this project is to analyze the school district data and perform and analysis based on several different metrics. The analysis has to be redone since it is suspected that the 9th grade students from the _Thomas High School_ have committed academic dishonesty. The key performance metrics for each school are: math and reading scores. Each school's data points include: budget, school type, and total number of students .From the resulting analysis, the district will be able to determine budget necessities and allocate the correct amount into each school.

## Results

- ### How is the district summary affected?

  - The effect that the modification has on the district summary is negligible. It is imperative to note that even though the metric values changed, when rounding them to the nearest decimal, the values remained the same. The only value that changed after rounding was the average math score that went from **78.9** to **79**, which cannot be considered a significant change.
  
  Original Analysis
  ![image](https://user-images.githubusercontent.com/85131345/179582133-12744857-b54f-43c5-b2e6-2f3ec7e3c7b4.png)
  
  Updated Analysis
  ![image](https://user-images.githubusercontent.com/85131345/179582337-3d44263d-79e9-41d0-b067-3a9bfe70aebf.png) 


- ### How is the school summary affected?

  - The only change happened on the values from _Thomas High School_. Since the only difference from this analysis from the past one was that the Thomas High School students from the 9th grade were not included in the analysis, the school summary was affected only in one row. On the other hand, the results from that high school were dramatically different.
    - The overall passing grade went from **90.1%** to **65.1%**
    - The percentage of students who passed reading went from **97.3%** to **69.7%** .
    - The percentage of students who passed math went from **93.3%** to **66.9%**.
    - As for the actual point-based scores, there was no significant difference. Math scores went from **83.42** to **83.35** while reading scores went slightly up from **83.84** to **83.89**
    
    Original Analysis
    ![image](https://user-images.githubusercontent.com/85131345/179583332-49456cbb-45b4-4342-89fb-0897145bcc70.png)
    
    Updated Analysis
    ![image](https://user-images.githubusercontent.com/85131345/179583447-b39d9305-bb4c-4d50-9042-feaab723e630.png)


- ### How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?

  - It had no effect whatsoever in the school rankings sorted by overall passing percentage. _Thomas High School_ was second in this list and remained in the same position after filtering out the students.
  
  Original Analysis
  ![image](https://user-images.githubusercontent.com/85131345/179585759-c65d5a74-e44b-4b2a-af6b-be2215d3a0c9.png)


  
  Updated Analysis
  ![image](https://user-images.githubusercontent.com/85131345/179584467-01b779f6-1a7e-4da6-b805-755cea90effa.png)


- ### How does replacing the ninth-grade scores affect the following

  - #### Math and reading scores by grade

    - This did not have a big effect. Now; however, we do not have any information regarding the 9th grade students from _Thomas High School_. It is easy to see from the following images that no other value was affected by this.
    - As for the average grade for 9th graders in reading, it decreased from **82.51** to **82.43**. While math average score decreased from **80.35** to **80.12**.
    
    Original Analysis <br>
    ![image](https://user-images.githubusercontent.com/85131345/179588190-503ab597-a484-44ab-9932-e39a11414668.png)
    
    Updated Analysis <br>
    ![image](https://user-images.githubusercontent.com/85131345/179587478-5dbc2918-17ae-403f-87da-e80173ff1cc8.png)


  - #### Scores by school spending

    - Schools spending scores suffered changes only in the range from **$631** to **$645**. There was no change elsewhere because only data from one school in this category was modified.
    - While there was a change, it was completely insignificant in the bigger scale since the difference can only be seen before rounding, meaning that there was no important change.
    - The following images will provide a visual representation which will be easier to see:
    
    Original Analysis
    ![image](https://user-images.githubusercontent.com/85131345/179589544-387c7072-87e3-4cc0-bf8d-c6d62318c174.png)
  
    Updated Analysis
    ![image](https://user-images.githubusercontent.com/85131345/179590074-08a5a0e1-63da-4918-b543-3048448de50d.png)

  - #### Scores by school size

    - Since Thomas High School is a medium sized school, only that category's results were affected; however, after rounding, that difference disappears.
    - This is due to the fact that such a small number of students could not have had a big impact on the averages, especially since those scores reassembled the average.
    - Since there is no change, only one image will be displayed.
    
    ![image](https://user-images.githubusercontent.com/85131345/179592825-4495d5b2-01d4-41d6-a662-1c270ff53e51.png)
    

  - #### Scores by school type

    - Just as for the other categories, the scores by school type had a negligible impact before rounding and no impact whatsoever when rounding. The rationale is the same as for the scores by school size; such a small number of students will not have a major impact.
    - Since there is no change, only one image will be displayed.
    
    ![image](https://user-images.githubusercontent.com/85131345/179593128-841692a6-1e39-4bcf-829a-ffce36ca2dbd.png)


## Summary

- The most important takeaway from this new project is that the removed data had a negligible impact on most performed calculations. When analyzing the scores by school type, school size, and expenditure per student, the key metric averages where almost identical.
- The big impact can be seen when analyzing the results just from _Thomas High School_. When done so, there are substantial differences from the results obtained in the previous analysis.
- This could be expected since such a small amount of data points could not have had a big impact in the overall metrics, especially since almost none of them were anomalies.
