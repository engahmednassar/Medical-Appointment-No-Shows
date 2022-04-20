
# Medical Appointments No-Shows
![](https://storage.googleapis.com/kaggle-datasets-images/792/1472/8853c0b4591bba14e29305fcaa29f2f9/dataset-cover.jpg)

## Overview
This dataset `No-Show Appointments` collects information from 100k medical appointments in Brazil and is focused on the question of whether or not patients show up for their appointment. A number of characteristics about the patient are included in each row.

● *`ScheduledDay`* tells us on what day the patient set up their appointment.

● *`Neighborhood`* indicates the location of the hospital.

● *`Scholarship`* indicates whether or not the patient is enrolled in Brasilian welfare program Bolsa Família.

● Be careful about the encoding of the last column `no_show`: it says ‘No’ if the patient showed up to their appointment, and ‘Yes’ if they did not show up.

We will analyze and explore the No-Show Appointments dataset to work throw it and we tring to answer this questions by exploring the dataset and also the connections among variables. And after that, come up with possible conclusions as to why so many patients do not show up to their appointment.

## Source of dataset
Data was gathered from [kaggle’s Medical Appointment](https://www.kaggle.com/datasets/joniarroba/noshowappointments) No Show dataset.
## Details
I have looked into the dataset and managed a few problems like unifying names, removing wrong data. I have also investigated most of independent variables in the dataset and made a few observations comparing them to each other as well as to the dependent one *`no_show`*. As this was only an exploratory analysis, many potential correlations may remain uncovered. The data should be investigated further with more advanced statistical analysis to potentially reveal new insights and correlations.

For details see analysis documentation Jupyter Notebook or HTML.

## Tools
Python, libraries: numpy, pandas, matplotlib, seaborn, warnings
Jupyter Lab