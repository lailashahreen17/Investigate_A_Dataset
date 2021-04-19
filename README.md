# Project: Explore Medical Appointment No Shows Dataset and Fact Finding

In this project,I explored a dataset related to patients' medical appointment show up history in Brazil. The dataset here sourced from Kaggle includes data about patient's physical condition, personal information, location and scheduled medical appointments' details. The main goal of this project is to identify the reasons behind not showing up after making an appointment.

# Questions
The questions I focused on to answer through my data analysis process are stated below. The type of my questions could be categorized in three main factors. Health condition, personal information and medical benefit such as recipient of scholarship from Brasilian welfare program.


1. What is the gender profile of all the patients?
2. What is the distribution of gender in No-show up category?
3. What is the age distribution among all patients?
4. Does any age category have higher 'No -show' tendency over others?
5. How does a dibetes patient respond to an appointmnt?
6. How does a hypertension patient respond to an appointment?
7. How does a patient with alcohol addiction respond to an appointment?
8. Does gender play any role in any of these health condition?
9. Which hospital location gets less 'No-show' response?
10. Does text reminder help in getting less 'No-show' response?
11. Does scholarship play any part in showing up on scheduled appointment day?
12. How being handicap does impact on not-showing up on appoinement day?

Before exploring the dataset, I accumulated all the neccessary packages and also included the % matplotlib inline command line so that my visualization are plotted inline with the notebook.

# Python Packages
1. Numpy
2. Matplotlib
3. Pandas

# Conclusins

After analyzing 9 variables with regard to No-show response, the following findings are worth to highlight. The findings are tentative and based on what dataset we have.

1. Number of patients who did not show up are mostly within first two age groups i.e from age of 0 to 39 . Patients above age of 40 are more likely to show up at appoinment day.
2. Number of female patients are higher than male patients. 65% to 35%. No significant difference in proportion is visible between female and male patients who did/did NOT show up. So there is no clear impact of gender in case of not visiting on appointment day even after scheduling for that.
3. Only 7 % of all patients have diabetes. Most of the patients who do not have diabetes, have higher record of attending the hospital on thier appointment day. Although the difference is small, but diabetic patient seems less caring in regard to hospital visit.
4. 80 % of total patient do not have hypertension and they are less likely to show up on appointment day.
5. Only 3% patients have alcohol addiction problem.Among two groups the ratio of show and no-show trend is similar.
6. Patients who received a text reminder has less percentage(32%) in total patient count.Patients who did not receive a text reminder showed up more. So, a text reminder did not really impact on their decision of showing up in this case.
7. Only 10 % patient got enrolled in scholarship and among them the no-show portion is higher.
8. Only 0 and 1 category handicap patients have the lion share on show -no show proportions.
9. Hypertension and diabetes are more common in female patients(21% and 7%) .
10. Male patients have more alcohol related issue 5% where as only 1.7% female patient falls into alcoholism.
11. Jardim Camburi is the hospital location where most of the patient did not show up even after making an appoinment compared to total number of appointments made at that location.
12. Top five No-show places(where patients did not visit on appointment day) are JARDIM CAMBURI,MARIA ORTIZ,ITARARÉ,RESISTÊNCIA and CENTRO.
13. Top five show-up places(where patients did visit on appointment day) are AEROPORTO,ILHA DO FRADE,ILHAS OCEÂNICAS DE TRINDADE,ILHA DO BOI and PONTAL DE CAMBURI.
