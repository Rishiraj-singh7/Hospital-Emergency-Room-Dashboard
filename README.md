Emergency Room - Patient Satisfaction Report in PowerBI
Project Overview
This project analyzes patient satisfaction data from an Emergency Room of a hospital, covering the period from August 2019 to October 2020. We're dedicated to enhancing operational efficiency while delivering top-notch care. Here are some insights to highlight areas for improvement in resource allocation and patient experience.

Data Description
Column Name	Data Type	Description
date	DATETIME	Date and time of the patient's visit.
patient_id	VARCHAR	Unique identifier for each patient.
patient_gender	CHAR	Gender of the patient ('M' or 'F').
patient_age	INT	Age of the patient.
patient_sat_score	INT	Patient satisfaction score (1 to 10).
patient_first_initial	CHAR	First initial of the patient's first name.
patient_last_name	VARCHAR	Last name of the patient.
patient_race	VARCHAR	Race or ethnicity of the patient.
patient_admin_flag	BOOLEAN	Admission status (TRUE if admitted, FALSE otherwise).
patient_waittime	INT	Waiting time (in minutes).
department_referral	VARCHAR	Department referred to, if applicable.
Data Cleaning and Transformations
Using Power Query, the following measures and calculated columns were created:

Measures:
Admission rate (%)

Total Patients

Average Satisfaction Score

Average Waittime (in minutes)

Calculated Columns:
Time of Day

Time Slot

Date Hierarchy

Age Group

Age_Bucket

Insights
Total Visits: 9,216 patient visits.

Overall Average Satisfaction Score: 4.99 out of 10.

Admission Rate: 50% of patients were admitted for further medical attention.

Average Waiting Time: 35 minutes before seeing a practitioner.

Late Night Visits: 34% of visits occurred between 11 PM and 6 AM.

Evening Visits: 16% of visits occurred between 6 PM and 10 PM.

Satisfaction by Gender: Male patients (5.03), Female patients (4.96).

Low Satisfaction Departments: Renal for male patients (4.5), Physiotherapy for female patients (5.29).

Walk-in and Renal Department satisfaction: Walk-in patients (5.4), Renal department patients (5.3).

Uniform Satisfaction Across Age Groups

View the PowerBI file here.

Recommendations
1. Reduce Waiting Times
Streamline Processes: Optimize triage and allocate resources efficiently.

Fast-Track Lanes: Implement for less severe cases.

Technology: Use appointment scheduling apps to manage patient flow effectively.

2. Improve Late-Night Services
Adequate Staffing: Ensure sufficient manpower during late-night hours (11 PM - 6 AM).

Maintain Cleanliness: Keep the facility clean for enhanced patient satisfaction.

Provide Timely Care: Even during off-peak hours, ensure patients receive timely care.

3. Department-Specific Interventions
Male Patients - Renal Department: Address dissatisfaction, average score of 4.5.

Female Patients - Physiotherapy Department: Enhance communication and personalized care, average score of 5.29.
