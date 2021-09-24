# School District Analysis
- - - -
## Overview
Maria is a chief data scientist for a local school district. With myself being new to the team, she has tasked me to assist with gathering data to assist with her analysis utilizing Pandas and Jupyter Notebook. We also utilized a couple datasets containing raw data from our local school district. These datasets included data specific to the [schools within the district](https://github.com/KEGANCP/School_District_Analysis/blob/main/Resources/schools_complete.csv), as well as data pertaining to the [students who attended these schools](https://github.com/KEGANCP/School_District_Analysis/blob/main/Resources/students_complete.csv).

Upon consolidating data from these datasets with several different basis and criteria, the school district suspects some academic dishonesty. This finding now requires some modifications to our prior populated results. Our new objective is to provide analysis (which we will refer to below) with the absence of all scores from the 9th grade at Thomas High School removed from the data, which required some refactoring within our prior code to not allow the potential dishonesty to alter our findings.

## Results 

#### School District Summary
The below will show our data with all scores, and the second image shows with the prior mention 9th grades Thomas High School scores removed. Reviewing the data we can conclude:
* With 39,170 students involved, removing this limited amount of data didn't create a substantial skew.
* Marginal differences can be viewed within the *Average Math Scores*, *% Passing Math*, *% Passing Reading*, and *% Overall Passing*.


   ##### Total School District Summary
      
  ![This is an image](https://github.com/KEGANCP/School_District_Analysis/blob/main/Resources/District_Summary_total.png)

    #### School District Summary without Thomas High School 9th grade scores
       
  ![This is an image](https://github.com/KEGANCP/School_District_Analysis/blob/main/Resources/District_summary_w_o_THS.png)


### Per School Summary
The below images will show differences within our dataframes including all scores, compared to our dataframe with 9th grade scores from THS removed.
* The only data affected in this dataframe is that specific to Thomas High School
* Comparing THS scores you will notice another marginal difference within all the average score and passing percentage columns
* By removing the 9th grade scores, it has predominantly affected THS scores negatively.



    #### Total Per School Summary
      
  ![This is an image](https://github.com/KEGANCP/School_District_Analysis/blob/main/Resources/Per_school_summary_Total.png)

    #### Per School Summary without Thomas High School 9th grade scores
       
  ![This is an image](https://github.com/KEGANCP/School_District_Analysis/blob/main/Resources/Per_School_Summary_w_o_THS.png)


### Math & Reading scores by grade
The below will show the difference with total scores and with 9th grade data from THS removed for both math and reading scores.

   #### Math scores by grade
      
  ![This is an image](https://github.com/KEGANCP/School_District_Analysis/blob/main/Resources/math_scores_by_grade.png)

   #### Reading scores by grade
       
  ![This is an image](https://github.com/KEGANCP/School_District_Analysis/blob/main/Resources/reading_scores_by_grade.png)


### Summary by School Spending

   #### School Spending Summary Total
      
  ![This is an image](https://github.com/KEGANCP/School_District_Analysis/blob/main/Resources/school_spending_total.png)

   #### School Spending Summary with THS 9th grader scores removed
       
  ![This is an image](https://github.com/KEGANCP/School_District_Analysis/blob/main/Resources/school_spending_wo_THS.png)


### Summary by School Size

   #### School Size Summary Total
      
  ![This is an image](https://github.com/KEGANCP/School_District_Analysis/blob/main/Resources/school_size_total.png)

   #### School Size Summary with THS 9th grader scores removed
       
  ![This is an image](https://github.com/KEGANCP/School_District_Analysis/blob/main/Resources/school_size_wo_THS.png)
  
  
 ### Summary by School Type

   #### School Type Summary Total
      
  ![This is an image](https://github.com/KEGANCP/School_District_Analysis/blob/main/Resources/school_type_total.png)

   #### School Type Summary with THS 9th grader scores removed
       
  ![This is an image](https://github.com/KEGANCP/School_District_Analysis/blob/main/Resources/school_type_wo_THS.png)
  
- - - -
## Summary of Results
In regards to the restructure of our data by removing our 9th grade scores within Thomas High School due to potential academic dishonesty, we can conclude that the results are insubstantial, and only provide some very minimal differences in some of the data that we outlined above. Whilst running the data we were able to determine there were a total of 461 9th grade students attending THS, and this is too finite of a quantity to affect the mass of over 39 thousand students total in most of the data we were analyzing. The data we could see altered included the following:
* THS Average Reading score
* THS Average Math Score
* THS % Passing Math
* THS % Passing Reading
* THS % Overall Passing
