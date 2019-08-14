## Problem Statement
The SAT is one of two standardized tests used in college admissions, the other being the ACT. The participation rates across states for the two exams vary wildly. My goal was to identify why certain states have low SAT participation rates and make reccomendations to improve those rates in a specific state.

## Executive Summary

### Contents:
- [2017 Data Import & Cleaning](#Data-Import-and-Cleaning)
- [2018 Data Import and Cleaning](#2018-Data-Import-and-Cleaning)
- [Exploratory Data Analysis](#Exploratory-Data-Analysis)
- [Data Visualization](#Visualize-the-data)
- [Descriptive and Inferential Statistics](#Descriptive-and-Inferential-Statistics)
- [Outside Research](#Outside-Research)
- [Conclusions and Recommendations](#Conclusions-and-Recommendations)

**Data Dictionary**
|Feature|Type|Dataset|Description|
|---|---|---|---|
|state|object|both|The state that the row of data correponds to|
|act_participation_17|int|ACT|The percentage of high school graudates who took the ACT in 2017|
|act_participation_18|int|ACT|The percentage of high school graudates who took the ACT in 2017|
|act_english_17|float|ACT|The average score on the ACT English section|
|act_math_17|float|ACT|The average score on the ACT Math section|
|act_reading_17|float|ACT|The average score on the ACT Reading section|
|act_science_17|float|ACT|The average score on the ACT Science section|
|act_composite_17|float|ACT|The average overall score on the ACT in 2017|
|act_composite_18|float|ACT|The average overall score on the ACT in 2018|
|sat_participation_17|int|SAT|The percentage of high school graudates who took the SAT in 2017|
|sat_rw_17|int|SAT|The average Evidence-Based Reading and Writing score on the SAT in 2017|
|sat_math_17|int|SAT|The average math score on the SAT in 2017|
|sat_total_17|int|SAT|The average total score on the SAT in 2017|
|sat_participation_18|int|SAT|The percentage of high school graudates who took the SAT in 2018|
|sat_rw_18|int|SAT|The average Evidence-Based Reading and Writing score on the SAT in 2018|
|sat_math_18|int|SAT|The average math score on the SAT in 2018|
|sat_total_18|int|SAT|The average total score on the SAT in 2018|

### Conclusion

It definitely appears that states seem to favor one test or the other but not both. Many states are at 100% participation and some of this seems to be due to legistlation either offering a version of these tests for free and/or manadating the test as one of the statewide tests required for high shoolers. There is an interesting correlation that many of the states with the lowest participation for the test in question had higher than average scores. This can probably be partially explained by students taking these test when they're not required and thus only taking them because they feel they need them to get into a college which would likely be a higher scoring subset than the full population.

If I was a college board employee, I'd reccomend targeting a state like Kansas for incresing participation. Kansas is a state with low SAT participation (4% in 2017 and 2018) and high but not total ACT participation (73% in 2017 and 71% in 2018). The lack of 100% participation indicates that there probably isn't legislation in place to mandate the taking of the ACT. I'd reccomend that the college board identify what education meausres/outcomes the decision making bodies in Kansas are in favor of and identify how the SAT can help improve those outcomes and try to get legislation passed that uses the SAT as one of the statewide assessments for high schoolers. Some additional data that would be helpful would be info on why past Kansas students preferred the ACT over the SAT and if there have been prior legislative attempts regarding this and the outcomes of those attempts.
