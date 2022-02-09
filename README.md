# Clinic-Appointments-No-Shows

### Dataset Description
This dataset collects information from 100k medical appointments in Brazil and is focused on the question of whether or not patients show up for their appointment. A number of characteristics about the patient are included in each row. ● ‘ScheduledDay’ tells us on what day the patient set up their appointment. ● ‘Neighborhood’ indicates the location of the hospital. ● ‘Scholarship’ indicates whether or not the patient is enrolled in Brasilian welfare program Bolsa Família. ● Be careful about the encoding of the last column: it says ‘No’ if the patient showed up to their appointment, and ‘Yes’ if they did not show up.

The original problem description and data set can be found here: https://www.kaggle.com/joniarroba/noshowappointments/home

This project was completed as part of Udacity's Data Analyst Nanodegree certification.


### Question(s) for Analysis

Q1: Are there relation between gender and no show appointments?

Q2:Are there relation between ages and no show appointments?

Q3: Which neighborhoods have the top 10 of no-shows appointments?

Q4: what is the relation between scheduled day and no show appointments?

Q5: Are there relation between SMS received and no show appointments?

### Statistical Analysis Scope
     Data Wrangling
     Exploratory Data Analysis
     Data visualizations

Tools
Python, libraries: numpy, pandas, matplotlib, seaborn
Jupyter Lab

### Conclusions
I looked into the dataset and fixed a few problems like removing wrong data, correct wrong names and changing datatype for some variables. I also checked most of independent variables in the dataset and made a few observations compare them to the dependent one (no_show).

### The most important findings are:
I found ages , nieghbourhood and scheduled day have effect in show or no show appointments and I observed Gender and SMS received don't have same effect like other factors.
The number of female approximately twice the number of male
The highest ages show in appointment between 41-65 ages
There are 81 nieghbourhoods and the highest nieghbourhood in no show appointments (JARDIM CAMBURI)
There aren't data on saturday so it's vacation
There are many patient didn't receive SMS

### Limitation
The data set includes mistakes like age with negtive value and the data type of appointment day and scheduled day.The number of show for patients didn't receive SMS more than who received SMS. That's mean the SMS had no effect in reducing the number of no-show. *The number of female approximately twice the number of male so i can't depends on this factor