# HR-Analytics

HR analytics is revolutionising the way human resources departments operate, leading to higher efficiency and better results overall. Human resources has been using analytics for years. However, the collection, processing and analysis of data has been largely manual, and given the nature of human resources dynamics and HR KPIs, the approach has been constraining HR. 

Therefore, it is surprising that HR departments woke up to the utility of machine learning so late in the game. This Janata Hack presents an opportunity to try predictive analytics in HR Domain, so gear up for another fun filled weekend



A training institute which conducts training for analytics/ data science wants to expand their business to manpower recruitment (data science only) as well. 
 
Company gets large number of signups for their trainings. Now, company wants to connect these enrollees with their clients who are looking to hire employees working in the same domain. Before that, it is important to know which of these candidates are really looking for a new employment. They have student information related to demographics, education, experience and features related to training as well.
 
To understand the factors that lead a person to look for a job change, the agency wants you to design a model that uses the current credentials/demographics/experience to predict the probability of an enrollee to look for a new job.

Data Dictionary 
Variable

Description

enrollee_id

Unique ID for enrollee

city

City code

city_development_index

Developement index of the city (scaled)

gender

Gender

relevent_experience

Relevent experience

enrolled_university

Type of University course enrolled if any

education_level

Education level

major_discipline

Major discipline

experience

Total experience in years

company_size

No of employees in current employer's company

company_type

Type of current employer

last_new_job

Difference in years between previous job and current job

training_hours

training hours completed

target

0 – Not looking for job change, 1 – Looking for a job change




Evaluation Metric
The evaluation metric for this competition is AUC-ROC score.



Public and Private split
Note that the test data is further randomly divided into Public (40%) and Private (60%) data. Your initial responses will be checked and scored on the Public data.
