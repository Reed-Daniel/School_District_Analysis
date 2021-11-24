# PyCity School District Analysis
## Project Overview
Following our analysis of the PyCity school district, it was determined by the school board that the provided student files contained falsified data specifically from the 9th grade class at Thomas High School. In an effort to maintain state-testing standards, the school board has requested that the analysis be repeated but this time replacing Thomas High School's 9th grade data with NaN values to determine how the falsified test grades affected key metrics for the school district.

# Results
### District Summary
- The number of schools, number of students, and the total budget for the district were unaffected by the refactored analysis
- The refactored district summary saw minor decreases in
    - Average math score (&#8595;.1%)
    - Percentage of passing math scores (&#8595;.2%)
    - passing reading scores (&#8595;.1%)
    - percentage of overall passing scores (&#8595;.3%)

#### **Original District Summary**
<img width="907" alt="OG_District_Analysis" src="https://user-images.githubusercontent.com/93271297/143157697-e4e404ea-7597-4de1-a22b-ce38884a8ac5.png">

#### **New District Summary**
<img width="905" alt="New_District_Analysis" src="https://user-images.githubusercontent.com/93271297/143158767-0a9a26e5-0977-4627-9019-57342dc23fb1.png">


### School Summary
- Thomas High School saw minor decreases in performance for
    - Average math score (&#8595;.06%)
    - Percentage of passing math scores (&#8595;.09%)
    - passing reading scores (&#8595;.29%)
    - percentage of overall passing scores (&#8595;.31%)
- Thomas High School saw a minor increase in performance for 
    - Average reading score ((&#8595;.03%)
- Although Thomas High School saw a decrease in performance, the top 5 school rankings remained unchanged.

#### **Original School Summary**
<img width="986" alt="OG_School_Summary" src="https://user-images.githubusercontent.com/93271297/143160822-65b3cf1d-4bc6-4081-b9a8-dd5d9f066f81.png">

#### **New School Summary**
<img width="981" alt="New_School_Summary" src="https://user-images.githubusercontent.com/93271297/143160831-38460bac-ef20-4ea9-a11d-a4413b1bad6f.png">


### The Effects of Replacing 9th Grader Scores for Thomas High School with NaNs
- **The NaN value for Thomas High School's 9th grader test scores pushes them to the bottom of the Grade ranking for the district as there are no test scores to be measured**
##### **Reading Scores** / **Math Scores**

<img width="225" alt="Reading_Scores_Grade" src="https://user-images.githubusercontent.com/93271297/143164400-764563fb-0c0e-443e-8456-5d6510e55c04.png">  <img width="225" alt="Math_Scores_Grade" src="https://user-images.githubusercontent.com/93271297/143164414-86c3ecfb-b615-4349-a88d-8c83447da498.png">


- **The percentage of passing reading scores for schools in the $630-644 spending bin saw a tiny decrease (&#8595;.1%)**
<img width="824" alt="New_Grade_BySpending" src="https://user-images.githubusercontent.com/93271297/143170589-f5c808bc-7dcc-4297-86cf-feb2162edf75.png">


- **The medium sized school's perentage of passing reading scores saw a tiny decrease (&#8595;.1%)**
<img width="763" alt="Grade_BySize" src="https://user-images.githubusercontent.com/93271297/143170818-44438200-ff4d-4b72-88a0-b9a2a0ef3492.png">


- **Charter school performance in the district was unaffected by the replacement of Thomas High School 9th grade data with NaNs**


# Summary
After replacing reading and math scores for the ninth grade at Thomas High School with NaNs we saw decreases, albeit infinitesmal, in the average math score as well as the passing percentages for math, reading, and overall. The greatest affect the NaNs had were on Thomas High School's performance in the high school rankings lowering their average math score and passing percentages and even increasing their average reading score ever so slightly. With that being said, neither were enough to have a significant effect on the top schools rankings for the district with Thomas High School remaining the 2nd ranked school.
