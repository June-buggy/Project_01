# Project 1


Question:  
    How does Social Perception of Mental Health Affect Utilization Rate?

Description: 
    In this analysis, by taking the responses of questions regarding social perception of mental health from those who are offered mental health resources, we attempt to see if their is a connection between how those who utilize their resources view mental health, from a social perspective, compared to those who do not utilize their resources.
    

Steps:

-The first step of our analysis was to import all necessary dependencies such as pandas, pathlib, matplot, and numpy.
    
-Then we read in the csv file, found on: https://rutvirtdatapt-6cw2087.slack.com/files/U05CUGL7EKG/F05LXS4391Q/mental-heath-in-tech-2016_20161114.csv 

-Next, to complete the analysis, we needed to select specific columns of data from the csv, in order to create a cleaned dataframe: 

        (Columns referring to who qualifies as being offered mental health resources)
     -Does your employer provide mental health benefits as part of healthcare coverage?
     -Do you have medical coverage (private insurance or state-provided) which includes treatment of  mental health issues?
     -Do you currently have a mental health disorder?
     
         (Columns regarding Social Perception of Mental Health)
     -Do you feel that being identified as a person with a mental health issue would hurt your career?
     -Do you think that team members/co-workers would view you more negatively if they knew you suffered from a mental health issue?

-Columns chosen for addressing those who qualified at work for mental health resources were selected due to the process of how the utilization rate was calculated. Sticking to this would be important so that we could compare how the responses to our "perception questions" affected the utilization rates. 


-Due to the fact that the columns regarding the social perception of mental health had multiple responses that could be simplified to "No", "Yes", or "Maybe", we created two new columns in the dataframe to translate those responses to yes, no, or maybe. Therefore they would be easier to quantify.

-After that, because the responses collected could only be from those who qualify for mental health resources, they were broken into 4 groups:
       
       -Non-Self Employed workers who utilized resources
       -Non-Self Employed workers who did not utilize resources
       
       -Self Employed workers who utilized their resources
       -Self Employed workers who did not utilize their resources

-Using multiple conditional statements on columns of the dataframe, we were able to address those who qualified for resources and record the total of their responses.

-For the sake of organizing the data, we held the total value of responses in order of "No","Maybe","Yes".

-In addition, we created two sub-DataFrames based on the total value of responses for each "Social Perception" question. One for those who utilized their resources, and another for those who did not.
-This made it easier to put the total value of each response "no, maybe, yes" into a variable, so then later they could be used to help visualize the data.

-Using similar code for each, we were able to create four unique pie charts:
(Each with three sections for "No, Maybe, Yes" and the total of their responses set as percentages. Each pie chart represents an aspect of the utilization rate, whether their responses are based on the 39.5% who did not utilize their resources or the 60.5% who did.)

    -Responses to the first "social perception" question of those who utilized their resources
    
    -Responses to the first "social perception" question of those who did not utilize their resources
    
    -Responses to the second "social perception" question of those who utilized their resources
    
    -Responses to the second "social perception" question of those who did not utilize their resources



ANALYSIS:

    Before beginning the data analysis, it was assumed that those who utilized mental health resources would not think that being identified as someone with a mental issue would hurt their career or that co workers would not view them more negatively. However, the data suggests that more people who utilize resources do think that having a mental issue is a social burden. Whereas, more respondents said either "Yes"or "Maybe" to thinking mental issues could hurt their career and have them viewed more negatively. In addition, the response "No" was the least represented for people who utilized resources in both social perception questions. 
    
    As for those who did not utilize resources, it was assumed that they would be more opposed to seeking resources due to the negative social repercussions of mental issues. However, the data shows that those who did not utilize resources were more likely to respond with "No" than "Yes" to questions asking whether they felt a mental issue could hurt your career or is something people view more negatively. This appears to be the opposite of those who do utilize their mental health resources.
    
    Possible reasons for these adverse responses could be due to the fact that less data was available from those who did not utilize their resources, given they represented the 39.5%, where utilizers represented 60.5% of the sample. In addition, it could be possible that those who did not utilize mental health resources, did not because they felt they were in no need of them. 
    
    A limitation found in the data analysis was that the qualifications of those offered mental health resources included self employed workers. Although this was important to calculate the utilization rate, it made less data available to analyze further questions on the social perception of mental health. Therefore with the data given, it was much more difficult to come to any concrete conclusions. In addition, because the sample size was small, the percentages of responses for each question did not vary a significant amount. This is why no major findings were found throughout the data analysis, although for future reference, it could be more efficient to work with a larger sample size.    
        