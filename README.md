# Election Analysis

## Project Overview

The purpose of this project was to evaluate the data of 39,169 students in order to provide analysis correlating math and reading test scores against various school factors. This project looked to find any correlation between test scores against a multitude of factors including: 

-School size
-Budget allocation per student
-District vs. Charter schools 

It was also found during the analysis that some irregularaties existed in the testing data of the 9th grade class of Thomas High School. Thustly the data specifically for 9th graders at Thomas High School was removed from consideration. 


## Resources

    -Data Source: schools_complete.csv & students_complete.csv
    -Software: Jupyter Notebooks 

## Analysis Results

Once the erroneous test data for T.H.S. 9th graders was removed, the following changes to our data summaries were observed: 

How is the district summary affected?
    There was a reduction across the board in passing math, reading, and overall passing. The observed differences were all reductions, however they were small in size. Passing math was reduced by .2%~, passing reading was reduced by .15%~ and overall passing saw a reduction of 0.32%~
How is the school summary affected?
    The only impacted sections of the school summary were specific to THS. THS overall math score went down slightly, and their reading score went up slightly. Howveer, the % passing math and reading both went down slightly. Lastly the overall passing % was reduced by .31%~ 
How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
    The effect on the overall data was very small. THS remained in the second top performing school position. However Griffin High School is now extremely close to passing THS for that position. 
How does replacing the ninth-grade scores affect the following:
    Math and reading scores by grade
        Since this summary is done at the per school level, there is no impact to other schools, only to the 9th grade level of THS as it will now display 'NaN'
    Scores by school spending
        For the spending rnage $630-644, where THS falls, the % passing reading and % overall passing were both reduced by .1%, no other impact was observed. 
    Scores by school size
        There was no impact observed. 
    Scores by school type
        There was no impact observed. 

## Summary

While there was an impact to the summary tables for the data based upon removing these students, the impact was quite small. When you consider the sample size (n=39,169) and the reduction from removing the THS 9th graders (461) it makes sense that a very small impact was seen in the overall data. 

Where the changes were most easily noticed was where they were likely to appear, within sub 1% changes to school specific data for THS. When the data for THS was combined with other schools into larger summaries it was simply too large of a sample set, and too small of a change to see a large impact. 

