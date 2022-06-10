# School_District_Analysis

## Overview:

This analysis is for finding out any academic dishonesty in reading and math grades for Thomas High School ninth graders. Data is used from two given csv files - schools_complete.csv & students_complete.csv and merged in to a common dataframe with analysis performed for all grades of reading and math scores and then another analysis performed with cleaned data by removing math and reading scores for ninth graders of Thomas High School and then comparing the metrics from both analyses. This report highlights any observed changes between the two analyses. These analyses also contain results of the district summary, school summary, top 5 & bottom 5 performing schools (based on the overall passing rate), average math & reading score for each grade level from each school, scores by school spending per student, scores by school size & scores by school type.



## Resources:

  - Source files: "schools_complete.csv" & "students_complete.csv"



## Results:

The following list contains images comparing the results from both analysis on each of the below listed meterics.


### District Summary

There is a drop in the percentages of students passing math, passing reading and passing overall in the cleaned data. 

   **District summary with original data**
  
   ![District_Summary_DF_Old](https://user-images.githubusercontent.com/104603128/173120939-558a1772-54a7-454f-aa49-9abfdd1dc922.png)


   **District summary with cleaned data**       
   
   ![District_Summary_DF_New](https://user-images.githubusercontent.com/104603128/173120964-7385be66-3c55-4ecc-90c8-7a3af1bd53fe.png)


### School Summary

For Thomas High School there is a sharp drop in the percentages of students passing math, passing reading and passing overall in the cleaned data.

   **School summary with original data**

   ![School_Summary_Old](https://user-images.githubusercontent.com/104603128/173121037-01950c86-506e-4d9f-b25f-1675238e9193.png)
   
   
   **School summary with cleaned data**
   
   ![School_Summary_New](https://user-images.githubusercontent.com/104603128/173121065-83c768b7-516f-4842-ae17-589f8f93f7fd.png)
   

### Performance of Thomas High School relative to other schools

Thomas High School remains at the second position in the list of top five schools, although a drop is seen in the percentage of students passing math, passing reading and passing overall in the cleaned data.

   **Top 5 schools based on original data**
   
   ![Top 5 schools on overall passing rate_Old](https://user-images.githubusercontent.com/104603128/173121199-2737aea0-e0af-4f03-9335-946318ed4a6e.png)
   
   
   **Top 5 schools based on cleaned data**
   
   ![Top 5 schools on overall passing rate](https://user-images.githubusercontent.com/104603128/173121264-3209e722-0b90-4713-b846-2c5058d56058.png)
    
    
### Affect of replacing ninth grade scores

Following figures show the values for each of the following metrics after replacing ninth grade scores.

   - Math & Reading scores
   The math & reading scores remain unchanged for each of the schools except for the 9th grade of Thomas High School, in which values have been removed.
    
   **Math Scores from original data**
   
   ![Math_Scores_By_Grade_Old](https://user-images.githubusercontent.com/104603128/173121606-a666c39a-d5b3-40d4-b6ae-60fd73f6e4db.png)


   **Math Scores from cleaned data**

   ![Math_Scores_By_Grade_New](https://user-images.githubusercontent.com/104603128/173121639-de896924-8dd9-4d8f-945a-98cf9b5d7cd1.png)
   
   
   **Reading Scores from original data**
   
   ![Reading_Scores_By_Grade_Old](https://user-images.githubusercontent.com/104603128/173121668-deb81a64-1a6f-485e-9ceb-ddb1422f70f8.png)


   **Reading Scores from cleaned data**
   
   ![Reading_Scores_By_Grade_New](https://user-images.githubusercontent.com/104603128/173121705-b6a608d4-0af3-4f3a-b10d-33d07e8ddb95.png)
    
    
   -Scores by school spending
   
   There are no significant changes in the scores based on school spending.
    
   **Scores by School spending based on original data**
   
   ![Scores_By_School_Spending_Old](https://user-images.githubusercontent.com/104603128/173121759-4ea92cd6-8b66-4d3d-a655-29b7a32bb3a7.png)

   
   **Scores by School spending based on cleaned data**
   
   ![Scores_By_School_Spending_New](https://user-images.githubusercontent.com/104603128/173121782-9ddb4325-0122-486d-89cb-96ef1d2a430a.png)

    
   -Scores by School size
   
   No significant changes are seen in the scores based on school size.
    
   **Scores by School size based on original data**
   
   ![Scores_By_School_Size_Old](https://user-images.githubusercontent.com/104603128/173121805-248e2747-83c7-4646-807e-88634b4ff77c.png)
   
   
   **Scores by School size based on cleaned data**
   
   ![Scores_By_School_Size_New](https://user-images.githubusercontent.com/104603128/173121841-b76c1617-6273-4bcf-b65e-fe36d80a57e2.png)


   -Scores by School type
   
   No significant changes are seen in the scores baed on school type.
    
   **Scores by School type based on original data**
   
   ![Scores_By_School_Type_Old](https://user-images.githubusercontent.com/104603128/173121884-0e6ddc31-240e-4a60-915d-9362db5602a6.png)
   
   
   **Scores by School type based on cleaned data**
   
   ![Scores_By_School_Type_New](https://user-images.githubusercontent.com/104603128/173121935-7e7d264f-c196-4cc9-96bb-f22535cd9e21.png)



### Summary

In the analysis on the cleaned data, changes are seen on the metrics in district summary and school summary as mentioned above. However, these are not significant enough to affect the ranking of Thomas High School relative to other schools. The changes observed on the cleaned data are summarised below.

    - District summary shows sharp drop in some metrics.
    - School summary shows sharp drop in some metrics.
    - Performance of Thomas high shool relative to other school remains unchanged despite minute drop in some metrics.
    - Replacing ninth grade scores doesn't show any significant impact on the scores based on various categories.

The performance for students of grades 10th, 11th & 12th for Thomas High School in the cleaned data shows consistency with the original data of all 4 grades.


    
     
