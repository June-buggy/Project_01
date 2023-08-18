# Project_01

## Overview
In this project, we worked collaboratively to find and analyze a dataset related to mental health in the tech industry. The primary goal of this project was to explore various aspects of mental health working in the tech field. We analyzed survey data to identify trends, correlations, and insights that shed light on the state of mental health in the tech industry.

## Project Focus: Mental Health in Tech
The tech industry is known for long hours at desks and high-pressure work environments. Our analysis sought to uncover patterns and trends that might indicate a connection between mental health and work-related factors impacting employees and their company, with the goal of understanding how and why these interactions occur.

## Questions we are answering:

### What are the factors affecting Mental Health Resource-Seeking?

1. Does resource seeking change by geographical location? - Kevin
- a. What, if any, is the correlation between company size and employees seeking mental health resources? - Kevin
     - Methodology: 
        - Used Geopandas and plotly to create a chloropleth map 
        - Removed non- US responses (did not plot international respondents)
        - Created dataframes with Pandas to plot chloropleth map and calculate statistics
     - Key Findings: 
        - A higher percentage of tech workers from the East of the US have sought treatment for their mental health issues
        - Tech workers from the west may see a potential lack of resources or social acceptance
        - Workers from larger companies tend to seek mental health resources more often, possibly because larger companies may have more financial resources to offer their workers mental health resources

- b. Breakdown of mental health resource seeking by gender - June
- c. Who seeks mental health resources more often: remote or in-person employees? - June
     - Methodology: 
        - Cleaned, transformed, and visualized data using Pandas and Matplotlib libraries
     - Key Findings:
        - Mood disorders and Anxiety disorders were by far the most commonly reported mental health disorders among respondents
        - The majority of mental health seekers were Male(69.9%), versus Female(26.6%), Non-Binary(1.9%), and Genderqueer(1.6%)- this was skewed due to a predominantly male tech industry
        - Genderqueer and Non-Binary respondents were far more likely than binary-gendered groups to have a past or current mental health disorder
        - More than 50% of all employees across all companies sought mental health resources if they were offered
        - Hybrid workers accounted for a stark plurality of MHR-seekers, followed by In-Person workers
        - Coupled with the majority disorders, there is likely an exacerbating effect of switching between office and home locations, or environmental conditions in the office.  This is a fascinating data point worth further investigation.

2. How Does Autonomy Affect Mental Health? - Maxiel
- d. Does self-employment positively affect mental health status?
     - Methodology:
        - Cleaned, transformed, and visualized data using Pandas and Matplotlib libraries
     - Key Findings:
        - The vast majority of respondents believed that disclosing their mental health status would have negative effects on their employment or client relationships
        - Overall, self-employed respondents were less comfortable with disclosing their mental health to coworkers than respondents employed by larger tech companies

3. Productivity/ company seriousness/ how does mental health interfere with work?
- e. Do the employees of companies with more supportive mental health policies have better health outcomes? How many companies offer mental health resources? - Oliver 
     - Methodology:
        - Cleaned, transformed, and visualized data using Pandas and Matplotlib libraries
        - Used Chi-squared test and summary statistics to analyze data
     - Key Findings:
        - There is a statistically significant association between employer-provided mental health benefits and mental health outcomes, and it is unlikely to have occurred by random chance.
        - The chi squared test indicated that companies providing mental health resources have more negative mental health outcomes, which is counterintuitive.

- f. Of companies that offer MHR, what is the utilization rate? In other words, what % of employees use offered MHR? - Jordan
     - Methodology: 
        - Cleaned, transformed, and visualized data using Pandas and Matplotlib libraries
     - Key Findings:
        - Out of respondents who had mental health resources/benefits at their disposal, 60.5% used those resources
        - Out of respondents who did not have mental health benefits, only 46.3% sought help or looked for other resources 
        
- g. How does social perception of mental health affect utilization rate? - Brendan
     - Methodology:
        - Cleaned, transformed, and visualized data using Pandas and Matplotlib libraries
     - Key Findings:
        - More than 84% of respondents (37.2% maybe, 47.1% yes) believed that revealing a mental health issue would harm their career
        - There was much more uncertainty with regards to co-workers: respondents were largely unusure how their coworkers would respond if they revealed a mental health issue
