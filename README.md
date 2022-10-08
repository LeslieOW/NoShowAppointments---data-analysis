# NoShowAppointments - Data-Analysis

This was my first project in **Udacity Data Analyst NanoDegree** course where I performed data wrangling and exploratoty data analysis on the data to obtain meaningful insights.

## Introduction
This dataset collects information from **100k medical appointments in Brazil** and is focused on the question of whether or not patients show up for their appointment. A number of characteristics about the patient are included in each row. Some of the questions I will be investigating include;

1.What factors are important for us to know in order to predict whether a patient will show up for their scheduled appointment?

2.Is the age likely to affect a patient's showing up for a scheduled appointment?

3.Which gender is more likely not to show up for their scheduled appointment?

4.Do patients suffering from hypertension likely to whow up for their appointments?

Be careful about the encoding of the last column: it says ‘No’ if the patient showed up to their appointment, and ‘Yes’ if they did not show up.

## Conclusion
I obtained the following observations from the analysis i carried out;

-There are 13 independent variables and one dependent variable(no show)

-Patients in age brackets (10-20), (20-30),and (110-120) are more likely to miss their appointments. Children and patients in their 60s, 70s and 80 are more likely to show up for their appointments.

-There is no correlation between the gender of a patient and missing appointments. This is because the ratio of males and females missing appointments is relatilvely the same.

-Patients having hypertension are more likely to turn up for appointments but the rate is small.

Limitation:

Most of the data is categorical , therefore it is not easy to establish a strong correlation between the factors affecting no shows.

I used kaggle website(where the data was downloaded from) to get the description of the columns of the dataset.
