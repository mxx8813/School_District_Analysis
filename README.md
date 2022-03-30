# School District Analysis

## Overview

The team recently completed a school district analysis of math & reading test scores results. The School Board however found that that there might be evidence of reading & math grades alterations for Thomas High School nighth graders.  As a result, we have been asked to eliminate this group's test scoress removed from the analysis and examine the impact it has on various levels while the investigation is ongoing.

## Process

We will begin the analysis using the existing summaries previously prepared as a baseline and adapt the script using numpy to convert all test grades for Thomas High School 9th graders to "NaN".  This group will then be eliminated from total counts when we re-analyze the results for district and school levels.

Finally, we will simply rerun the script to generate the revised summaries, which excludes THS 9th grades entirely, and provide the school district the insights on the impact.

## Results

### Impact on the school results and impact on school rankings:

The impact of excluding the 9th grader's test scores is significantly higher than it is on the district level.  As such, Thomas High School's percentage passing rates (math, reading, and overall) were much lower ranging from 65%-69% when the 9th grade test scores were included.  After we eliminated 9th graders' test scores, the percentages drastically increased to 90%-97%.  This could be an indiciation that the 9th graders were actually negatively impacted by grade alterations.

<img width="844" alt="School Level" src="https://user-images.githubusercontent.com/100495799/160875339-f25424b6-b30d-432c-8806-eee3f25d92f8.png">

Previously, Thomas High School did not make either the Top 5 Schools nor the Bottom 5 Schools out of a total of 15 schools.  This analysis impacts the ranking of top schools.  Thomas High School landed as the #2 top school in the district.

<img width="1032" alt="Ranking" src="https://user-images.githubusercontent.com/100495799/160878816-8a48e7f9-f9d0-481e-ac59-5750d94a7b0c.png">

### Impact on the district level results:

There is a total of 15 schools in the school district, with a total of 39,170 students in the high school population (9-12th grades).  Once we excluded the 461 Thomas High School 9th graders from the analysis, the district level % passing rates shifted downwards - though only nomimally.

<img width="1037" alt="District Level" src="https://user-images.githubusercontent.com/100495799/160874692-5f6cc88e-ef3a-4b43-a059-73da3c38f17d.png">

Similarly, because the Thomas High 9th grade population only make up 1% of the population, the effects on the folliwng following metrics are also minimal.

**Scores by school spending**

<img width="836" alt="Spend" src="https://user-images.githubusercontent.com/100495799/160946338-333c51bb-1d3f-4605-bbec-5e9d4eadb423.png">


**Scores by school size**

<img width="880" alt="School Size" src="https://user-images.githubusercontent.com/100495799/160946352-142ddd37-1c85-45c0-97bc-d6e98da8ea5d.png">


**Scores by school type**

<img width="821" alt="School Type" src="https://user-images.githubusercontent.com/100495799/160946365-374f5d61-67a8-4e14-940b-3f6989170757.png">

