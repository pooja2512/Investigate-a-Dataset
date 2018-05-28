# DAND_term1_project_Investigate_Dataset
This data set contains information about 10,000 movies collected from The Movie Database (TMDb), including user ratings and revenue,cast,release year.


# No-show-apppointment
This dataset collects information from 100k medical appointments in Brazil and is focused on the question of whether or not patients show up for their appointment. A number of characteristics about the patient are included in each row.

## Overview
This dataset collects information from 100k medical appointments in Brazil and is focused on the question of whether or not patients show up for their appointment. A number of characteristics about the patient are included in each row.

Key indicators were:
- ScheduledDay tells us on what day the patient set up their appointment.
- Neighborhood indicates the location of the hospital.
- Age = How old is the patient.
- Hipertension = True or False
- Diabetes= True or False
- Alcoholism = True or False
- Handcap = True or False
- SMS_received = 1 or more messages sent to the patient.
- No-show = True or False.
- Scholarship indicates whether or not the patient is enrolled in Brasilian welfare program Bolsa Família.
- ‘Bolsa Família’ It is a social welfare program of the Brazilian government, part of the Fome Zero network of federal assistance       programs.Bolsa Família provides financial aid to poor Brazilian families

The project involved data assessment and cleaning, performing EDA and drawing conclusions from the data.

### Statistical Analysis
- Examinations of central tendencies and spread
- Data visualization
- Conditional Probability & Bayes Rule
- Logistic Regression

## Technologies Used
- Python, Numpy, Pandas, Matplotlib, scikit-learn
- Jupyter Notebook

## Key Findings
- Hypertension is observed more followed by diabetes,Alcoholism,Handicap.
- Senior people (age above 50) are most likely suffering from hypertension and child are most likely handicap.
- More number of female are suffering from Hypertension and diabetes whereas male are more likely to suffering from alcoholism.
- Irrespective of gender 80% of people visit to their scheduled appointments & that's a good sign It shows people do care about their health issues.
- What factors are important for us to know in order to predict if a patient will show up for their scheduled appointment?
   Disease,age group,SMS,scholarship,month,weekday are the top paramenters in predicting if patient will show up on the scheduled           appointment.
