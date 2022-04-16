# School District Score Analysis

## Overview
The initial purpose of this challenge was to assist Maria in evaluating the data for school standardized test scores throughout the district. Upon discovering evidence of academic dishonesty at one of the schools withing the district, Maria has asked that we remove the math and reading scores at Thomas High School for 9th graders and evaluate the data once again to find the adjusted scores. 

## Changes By 7 District Metrics
### High and Low Performance
Strangely, even though my code was functional and appeared to correctly address scores following the removal of 9th grader score results, I was unable to detect any differences in multiple different areas. Namely High and Low Performance had ultimately no change in data values, despite it being the area where I expected the greatest change.

The values pictured below are from the second run of the code through the adjusted input, which should have been lacking 9th grade scores, alas the results are still identical to the previous results, so an error in merging or removing the data must be present earlier in the code.

![Capture.png](https://github.com/RyanJL18/School_District_Analysis/blob/main/Capture.PNG)
--
### Math and Reading Scores by Grade
It can be assumed, that with the assistance of academic dishonesty that the math and reading scores for Thomas High School 9th graders would have been higher than they should have been. In this portion, my inclusion of the ".head()" function prevented me from being able to make a 1 to 1 comparisson of these results. However, given that the previous data seemed to be skewed due to an error within the code, I am assuming that not much changed between these scores or else that change would have also been present elsewhere in the results.

### Scores by School Spending
This was the section that I experienced the most change in the data between the two runs of the code. Even with this change, I am unable to make any distinct observations or conclusions based on the change. This is in part to multiple different spending categories changing, which is something that should not be possible as Thomas High School should still fall into the same or only one spending category.

### Scores by School Size
This category was far too broad to really exhibit any real changes based upon the given data.

### Scores by School Type
Again, as expected this category was far too broad to display any real changes in the results, but whether that was due to an error in code or exactly what should have happened, the world may never know.



## Sumarize four changes 
I am going to take this opportunity to summarize the lack of changes due to an error within the code, and explain potential changes that could have been expected having had the proper results.
- Currently the changes between the original scores and the final scores (having removed the 9th graders scores) are not showing any substantial changes across the board. This would only make sense if the average was much closer to that of the other scores received from Thomas High School. Although the scores were very good initially, operating under the assumption that academic dishonesty had occured, the scores should be lower that what we originally received.
- The math and reading scores would have been the perfect place to identify the initial changes in results based on the change in input. The changes would have lowered scores and given us a more precise idea of what we could have expected from students in the 9th grade in this high school.
- This change in scores would have had a drastic change in the overall rankings of high schools, possibly knocking Thomas High School from their place in the top 5 overall scores in math and reading. 
- As we move the microscope further out and begin looking at scores based on school size and finally school type, we can assume that these changes in scores would not have as big of a change. This is due to just how big the data sets are when we are looking at the scores through those parameters, similarly this is why when we zoom in on categories like specific math and reading scores or rankings based on high school, we (should) see very drastic changes.
