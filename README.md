# School_District_Analysis
Analysis of school district data such as school budgets and student performance, to uncover trends and draw conclusions.


## Overview of the school district analysis
Maria is the Chief Data Scientist for a City School District and she is responsible for analyzing information for a variety of sources and different formats. She has been tasked to prepare all standardized testing data for analysis reporting and presenting an insight on performance trends and patterns. These insights are used to take strategic decisions at the School district level.

Maria has asked us for help to analyze data on Student funding and student's standardized test scores. We will be given access to every student's math and reading scores as well as various information on schools they attend. Our task is to aggregate that data and showcase trends in school performance. this analysis will help School Board in making decisions regarding the school budget and priorities.


## Challenge Overview
After we provided an analysis as per Maria's requirements. The School Board had notified Maria and her Supervisor that the file shows evidence of academic dishonesty; specifically, reading and math grades for Thomas High School ninth-graders appear to have been altered. 
Although the school board does not know the full extent of academic dishonesty, they want to uphold state-testing standards and have turned to Maria for help. 
She has asked us to replace the math and reading scores for Thomas High School with NaNs while keeping the rest of the data intact. Once you’ve replaced the math and reading scores, Maria would like you to repeat the school district analysis that you did in this module and write up a report to describe how these changes affected the overall analysis.


## Challenge Results

### Affect on District Summary
- After altering reading and math grades for Thomas High School ninth-graders there was a small decline in overall Scores as you can see below in the images.
We replaced the 9th-grade reading and math scores with NAN and run an analysis accordingly.
#### Old District Summary 
![image](https://user-images.githubusercontent.com/78935551/112738583-78a6bb00-8f3a-11eb-8ef2-2033a57397df.png)

#### New District Summary 
![image](https://user-images.githubusercontent.com/78935551/112738588-88260400-8f3a-11eb-8fd5-ebcdcebbcfa3.png)



### Affect on School Summary
- There was a slight decline in the scores when we analyzed School Summary. As shown in the image below.

#### Old School Summary
![image](https://user-images.githubusercontent.com/78935551/112739044-e3f28c00-8f3e-11eb-8301-e8c045a4d7c4.png)

#### New School Summary 
![image](https://user-images.githubusercontent.com/78935551/112739058-04bae180-8f3f-11eb-989c-573b965fa483.png)

#### How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
- Thomas High School was still in the top 5 performing Schools, holding second place as earlier. Replacing 9th graders scores with NAN didn't affect the school performance

#### How does replacing the ninth-grade scores affect the following : 

#### Math and reading scores by grade 
- There was no effect on the 10th to 12th grades. 9th-grade scores showed as NAN.
#### Math Scores
![image](https://user-images.githubusercontent.com/78935551/112741257-2c677500-8f52-11eb-9918-041b15a68993.png)

#### Reading Scores
![image](https://user-images.githubusercontent.com/78935551/112741271-42753580-8f52-11eb-9f07-8e4b19f38b6b.png)

#### Scores by school spending
 - We didn't notice any changes in the scores by school spending analysis. 

![image](https://user-images.githubusercontent.com/78935551/112741302-91bb6600-8f52-11eb-81e6-ec6c330f8557.png)

#### Scores by school size
- There was no changes to the Scores by School Size as well.
![image](https://user-images.githubusercontent.com/78935551/112741325-c29b9b00-8f52-11eb-8f02-47566ed10ec5.png)


#### Scores by school type

#### Old Summary 

#### New Suumary 
![image](https://user-images.githubusercontent.com/78935551/112741347-f7a7ed80-8f52-11eb-9674-8ceb715b7d9f.png)




