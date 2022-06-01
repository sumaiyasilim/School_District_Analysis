# School District Analysis
## Overview of the School District Analysis
The purpose of this anaylsis was to ensure that whatever grade would skew the results would be removed as there has been signs of academic dishonesty within the ninth grade math and reading scores. In order to do this, the ninth grade math and reading scores would be replaced with NaN.
## Results
#### How is the district summary affected?

<img width="311" alt="module_district_summary" src="https://user-images.githubusercontent.com/64383146/171332139-96af4e4a-c9a2-4585-8110-4d53327de0d7.png">  <img width="315" alt="challenge_district_summary" src="https://user-images.githubusercontent.com/64383146/171323488-9753a23e-8424-48fd-94b2-eda68467dd5b.png">

(left is module, right is challenge)

- "% Passing Math" decreased by 0.2%
- "% Passing Reading" decreased by 0.1%
- "% Overall Passing" decreased by 0.3%

#### How is the school summary affected?

<img width="326" alt="module_school_summary" src="https://user-images.githubusercontent.com/64383146/171323557-36d53c2a-caf2-4d27-a614-023c4efddf0b.png">  <img width="374" alt="challenge_school_summary" src="https://user-images.githubusercontent.com/64383146/171323587-11b9e7ba-e248-406f-abbc-824e68ff612a.png">

(left is module, right is challenge)

- "Average Math Score" decreased by 0.1
- "Average Reading Score" increased by 0.05
- "% Passing Math" decreased by 0.09%
- "% Passing Reading" decreased by 0.3%
- "% Overall Passing" decreased by 0.3%

#### How does replacing the ninth grade math and reading scores affect Thomas High School’s performance relative to the other schools?

<img width="400" alt="module_top_5" src="https://user-images.githubusercontent.com/64383146/171323642-9e39ea3a-746d-48c2-a500-d266faf42c53.png">  <img width="401" alt="challenge_top_5" src="https://user-images.githubusercontent.com/64383146/171323669-ecbe58ca-ed54-4bb4-935e-a360fadd0fda.png">

(left is module, right is challenge)


When getting the top schools based on “% Overall Passing”, in both the module and the challenge, Thomas High School was able to maintain the second position even without the ninth graders math and reading scores.
                                                                                                                                                  
#### How does replacing the ninth-grade scores affect the following:
                                                                                                                                                  
-	Math and reading scores by grade
                                                                                                                                                  
<img width="155" alt="summary_reading_scores" src="https://user-images.githubusercontent.com/64383146/171325879-f3c7d2a7-5235-472f-b6ef-919cc9be7036.png">  <img width="156" alt="challenge_reading_scores" src="https://user-images.githubusercontent.com/64383146/171325930-07363e3f-bf75-48cf-97f0-d96240f2327f.png">

(left is module, right is challenge)

Replacing the ninth-grade scores does not affect the math and reading scores of the other grades. The photos above are the reading scores by grade. As it can be seen, the only thing that’s different between these two photos is that in the Thomas High School the 9th grade section is “nan”.

-	Scores by school spending

<img width="312" alt="module_scores_by_school_spending" src="https://user-images.githubusercontent.com/64383146/171328012-93ca7866-c9b5-414a-8510-614f535fe33b.png">  <img width="401" alt="challenge_scores_by_school_spending" src="https://user-images.githubusercontent.com/64383146/171328052-f0fe41d9-7559-49f3-9743-02f0d4301e7d.png">

(left is module, right is challenge)


When the chart is formatted the way it is in the instructions, then there is no change. When the chart is formatted to 2 decimal places, this is where we would be able to see a slight difference, ranging from 0.02 – 0.08 in the “$631-645” row in all categories.

-	Scores by school size

<img width="312" alt="module_scores_school_size" src="https://user-images.githubusercontent.com/64383146/171329690-ca3a6447-47d4-4579-b362-296e8a1c79b9.png">  <img width="310" alt="challenge_scores_school_size" src="https://user-images.githubusercontent.com/64383146/171329710-eba099b7-41c3-455e-8b20-f3d0d8c47b7e.png">

(left is module, right is challenge)

The same applies to this chart, where the difference can only be seen before the chart is formatted. The “Medium (1000-1999)” bin changes slightly between the module and the challenge.

-	Scores by school type

<img width="361" alt="module_scores_school_type" src="https://user-images.githubusercontent.com/64383146/171329954-62c2db7d-0ee5-4605-afcf-45197e8c8ad6.png">  <img width="359" alt="challenge_school_type" src="https://user-images.githubusercontent.com/64383146/171329981-f6a54589-808f-4c0f-b683-e49324a6163b.png">

(left is module, right is challenge)

The same applies to this chart, where the difference can only be seen before the chart is formatted. The “Charter” row is where there is a slight difference in numbers compared to the module.
## Summary
The changes in the updated school district analysis after the math and reading scores for the ninth grade at Thomas High School were replaced with NaNs are:
-	The district summary having “% Passing Math”, “% Passing Reading’, and “% Overall Passing” decrease between 0.1% to 0.3%

-	The school summary having “Average Math Score”, “% Passing Math”, “% Passing Reading”, and “% Overall Passing” all decrease by 0.1 to 0.3

- The scores by spending chart has a slight change in the "$631-645" row

- The scores by school size chart has a slight change in the "Medium (1000-1999)" bin
- The scores by school type chart has a slight change in the "Charter" row
