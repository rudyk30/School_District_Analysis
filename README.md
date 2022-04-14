# Overview of Analysis
The purpose of this analysis was to investigate if the alleged academic dishonestly in Thomas High Schools ninth grade class impacted our original analysis we created for the Shool District. We did this by replacing the math and reading scores for 9th graders at Thomas High School and repeating our original analysis.

## Results 

* How is the district summary affected? 

    * Prior to replacing the scores for ninth graders, the below code snapshot was the school district summary. See below:

        ![Summary_Prior](https://user-images.githubusercontent.com/101602688/163306586-21a616f8-fd0e-47c3-a55b-458bbccf1102.png)


    * After we replaced the ninth grade school data from Thomas High School in our analysis, the district summary changed slightly. 

        ![Summary_After](https://user-images.githubusercontent.com/101602688/163306632-81f315f9-1680-4250-8c4b-65fdc683f4e6.png)


    * From the images, we can observe there was a very slight decrease in Avg Math Score, the Avg Reading Score remained unchanged, and little to know difference in % Passing Math, Reading and overall passing.

* How is the school summary affected?

    * Before Thomas High School was replaced in the analysis, it was a top performing school for the district boasting a 90.95% passing rate which was second amongst all schools. 

        ![School_Summary_Before](https://user-images.githubusercontent.com/101602688/163306673-f07b4ed3-759a-4e14-a1b3-a4b542f42e5c.png)


    * After removing 9th grade scores at Thomas High School, it fell from being a top performing school as their % overall passing rate dropped from 90.95% to 86%. 

        ![Summary_After](https://user-images.githubusercontent.com/101602688/163306695-da147d42-55c8-46b5-acd0-9d99d2012c8c.png)


* How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?

    * Overall, from analyzing the data shown above we see there was a signifcant impact in Thomas High School's performance relative to other schools. This is shown by their drop from being a top performing school to a bottom 10 performing school in the district. 

* How does replacing the ninth-grade scores affect the following:

    * Math and reading scores by grade

        * Overall, the math and reading scores changed very minimally for the overall school district after removing 9th graders at Thomas High School from the analysis
        * From reviewing the district summary data frame, we see a very small decrease in Avg Math score and the rest of the data remained largely the same. 

       

    * Scores by school spending

        * Thomas High School was in $630-644 spending range. The average passing rate for that spending range is now 62%. Prior to removing Thomas High School, the passing rate was 63%. Thus, we can observe a very minimal change in scores by school spending. 

         ![Spending_Before](https://user-images.githubusercontent.com/101602688/163306736-5688ba95-f2aa-44fe-82b3-57ae0e401c09.png)


         ![Spending_after](https://user-images.githubusercontent.com/101602688/163306772-ad58ac77-4084-4771-ac28-79333a00736a.png)


    * Scores by school size

        * After removing Thomas High School's ninth grade scores, scores by school size changed very minimally. The % Overall Passing remained at 89.88%,90%, and 58% for Small, Medium and Large schools respectively

    * Scores by school type

        * Similar to the scores by school size, removing Thomas High School minimally impacts Scores by School type. 


         ![School_Type_Before](https://user-images.githubusercontent.com/101602688/163306853-79d261ce-2cfe-4e93-bc7e-7bbd1eca8f40.png)


         ![School_Type_After](https://user-images.githubusercontent.com/101602688/163306881-58d31f67-5e59-458e-a159-7a60016dab67.png)


* Summarize four changes in the updated school district analysis after reading and math scores for the ninth grade at Thomas High School have been replaced with NaNs.

    * After removing Thomas High School, the % passing math went down slightly for charter schools, the % passing rate went down for the $630-644 spending bucket, the % reading score and % passing rate went down for charter schools 
