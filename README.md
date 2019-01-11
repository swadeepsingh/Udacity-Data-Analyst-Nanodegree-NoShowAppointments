# Project: No-Show Appointments Data Analysis

## Table of Contents

    Introduction
    Exploratory Data Analysis
    Conclusions

## Introduction

No-show appointments dataset is a collection of information from 100k medical appointments in Brazil and is focused on the question of whether or not patients show up for their appointment. The dataset capture the information about patient's age, gender, medical history (diabetes, hipertension, etc.), and lifestyle (alcoholism, etc.) with complete appointment details and has a final indicater that whether a patient showed up on the day of appointment or not. Each patient is allocated with a patientID.

![alt text](https://github.com/swadeepsingh/Udacity-Data-Analyst-Nanodegree-NoShowAppointments/blob/master/1.png?raw=true)

## Questions to be investigated:

    1. Does age play a role that whether or not patient show up for their appointment?

    2. How does patient's medical history, lifestyle, physical fitness affects appointments?

    3. Which neighborhoods have the highest number of no-shows?

    4. What is the trend of no-shows vs shows by patients that received SMS reminders?

    5. Does difference between schedule date and appointment date results in no-shows?

    6. Are patients failing to appear on specific days of the week?

    7. Which gender group generally don't show-up on appointment day ?


![alt text](https://github.com/swadeepsingh/Udacity-Data-Analyst-Nanodegree-NoShowAppointments/blob/master/2.png?raw=true)


## Conclusions

This exploratory analysis was able to correlate schedule day and appointment day, appointment sms reminders, neighborhood, and medical history.

### Findings:

### Q1. Does age play a role that whether or not patient show up for their appointment?

Age plays an important role for appointments, the Mean values for No-Show: 34 and Show: 37. The age group between 35 to 70 shows up for appointment.

Please see "Distribution of Show-Appointment" graph for constant growth & "Distribution of No-Show-Appointment" graph for decrease in same age segment.

### Q2. How does patient's medical history, lifestyle, physical fitness affects appointments?

The inference from above analysis shows that the alcoholism percentage for both show and no-show appointments are same. While the diabetic profile is almost same with ~1% difference and the hypertension profile has ~3.5% difference between show and no-show appointments.

### Q3. Which neighborhoods have the highest number of no-shows?

Top 5 no-show appointments neighborhood

    1. JARDIM CAMBURI   1465
    2. MARIA ORTIZ      1219
    3. ITARARÉ          923
    4. RESISTÊNCIA      906
    5. CENTRO           703

### Q4. What is the trend of no-shows vs shows by patients that received SMS reminders?

Patients who received an SMS had a no-show percentage of 27.6% and show percentage of 72.4%

### Q5. Does difference between schedule date and appointment date results in no-shows?

Patients who have scheduled the appointment on same day and appeared (show) are 41.7% and only 8% patients didn't appeared (no-show appointments) on same day

### Q6. Are patients failing to appear on specific days of the week?

Most no-shows appointments were on Tuesdays.

### Q7. Which gender group generally don't show-up on appointment day ?

65.4% of patients who didn't show up on appointment date were females.


![alt text](https://github.com/swadeepsingh/Udacity-Data-Analyst-Nanodegree-NoShowAppointments/blob/master/3.png?raw=true)


## Results:

1. Patients who has booked appointments more than 2 days ago are the one who didn't show-up on appointment day. 

2. Highest number of no-show appointments were in JARDIM CAMBURI (1465) neighborhood. 

3. 65.4% of patients who didn't show up on appointment date were females.

4. Patients who received an SMS had a no-show appointments percentage of ~ 27%

5. Most no-show appointment patients has "No-diabetes, No-hypertension, and No-alcoholism" & also the handicap level with disability level 0.


## Limitations:

1. Information regarding the appointment if given like the medical condition for which patient wants to counsult the doctor. 

2. It would be interesting to know why some patients received an SMS. If these patients had habit of not showing up in previous appointments it would explain the no-show percentage.
