# Medical Appointment No-Show Analysis

## Dataset Overview
This dataset tracks medical appointments from Brazil, focusing on whether patients keep their appointments. It contains 100,000 records detailing various factors influencing appointment attendance, including patient demographics, medical history, and appointment logistics.

## Column Details
1. **PatientId**: Unique identifier for each patient.
2. **AppointmentID**: Unique identifier for each appointment.
3. **Gender**: Gender of the patient (Male/Female).
4. **AppointmentDay**: Scheduled date for the patient’s doctor visit.
5. **ScheduledDay**: Date when the appointment was booked.
6. **Age**: Patient's age.
7. **Neighbourhood**: Location of the medical facility.
8. **Scholarship**: Boolean indicating if the patient is enrolled in the Bolsa Família welfare program.
9. **Hypertension**: Diagnosis of hypertension (True/False).
10. **Diabetes**: Diagnosis of diabetes (True/False).
11. **Alcoholism**: History of alcoholism (True/False).
12. **Handicap**: Disability status (True/False).
13. **SMS_received**: Number of reminder messages sent to the patient.
14. **No-show**: Attendance status (True = Did not attend, False = Attended).

---

## Exploratory Data Analysis (EDA)

### Q1: Gender Comparison in Attendance
Analysis of the dataset revealed that nearly half of the patients are female, who demonstrate a wider age distribution. The overall attendance rate is 79.8%, indicating that women are more likely to attend appointments than men. However, the higher attendance could be influenced by the greater number of women in the dataset.

### Q2: Impact of SMS Reminders
The role of SMS reminders showed that 67.8% of patients who did not receive an SMS reminder still attended their appointments. There is a positive correlation between the number of days before the appointment and attendance, suggesting that patients are more likely to show up when appointments are scheduled within a shorter timeframe (0 to 30 days). Gender does not significantly impact this relationship.

### Q3: Bolsa Família Program Influence
Having a scholarship through the Bolsa Família program appears to have minimal effect on appointment attendance. However, a significant portion of patients benefiting from the program is observed across various age groups, indicating the program's broader community impact.

### Q4: Influence of Medical Conditions
The majority of patients do not have chronic diseases, although some younger patients do exhibit these conditions. While chronic diseases may affect attendance, the influence does not appear to be strongly gender-dependent, indicating that other factors might be more significant in attendance rates for patients with chronic conditions.

---

## Conclusion
The analysis provides insights into factors influencing appointment attendance among patients in Brazil. While gender, SMS reminders, scholarship status, and chronic health conditions play a role, the dataset suggests that factors beyond these may also contribute significantly to no-show rates. This analysis serves as a foundation for further research and targeted interventions aimed at reducing appointment no-shows in healthcare settings.
