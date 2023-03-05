# Investigate-a-dataset
This is the first project on udacity data analytics nanodegree course. It's about investivagating a dataset as simple as possible. 
Project: NoShowAppointments Data Analysis
NoShowAppointments is a dataset which collects information from 100k medical appointments in Brazil and is focused on the question of whether or not patients show up for their appointment. We have such features like the patients and their appointments id, the scheduled and appointment day, their age, neighbourhood, if they have or not a scholarship , hypertension, diabetes, alcoholism. Also, if the patient showed up or not, and if they received a sms for the apppointments. The goal here is to know which of all these features impact the most on the patient showing up to their appointments or not.
First, i  did the data wrangling by loading my dataset, and then i tried to see if my data was correct or not. By correct, i mean if my dataset had missing values, duplicated values and so on. Then secondly, i  cleaned it to make it more efficient. Then i explored my dataset and try to answer three questions.


Questions :
QUESTION 1: Did the scholarship of patients helped in showing up to their appointments?
QUESTION 2: between children, women and men, who attended the most their appointments?
QUESTION 3: Did age impact appointments?


First, we found an age with a negative value. I removed to use a more correct dataset , because for me, it's surely an error . We saw that women are the most to not miss their appointment, then children and finally men. This can be explained by many others social life parameters. Also, having a scholarship or no dontt impact in the appointments. Only few peoples have scholarship, so it's understandable. Age also doesnt impact in the appointments, almost same mean age, oldest age and others parameters between those who showed up and not. We can do more with this dataset . For example, we can categorize the age as i did with the column category. So we could see clearly how ages impact on appointments, also associate it with another features. Also we can check it for each neighbourhood.


For a better analysis, if we could have the real distance between the neighbourhood and the hospital, it may helps us to understand more if the patients showed up or not
