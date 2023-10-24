# Examination-System

# Summary
Fully automated examination system to perform online exams by ITI instructors and students , starting from making the ERD according to the business case then making the database then analyzing the existing data, and creating dashboards and reports that have clear insights.

 # Tools:
ERD .

SQL server.

SSIS.

SSRS.

Red Gate Data Generator.

Power BI.

# ERD
The team had a good perspective on the examination system and we agreed that the system should include several entities which are the following: Students, Instructors, Departments, Exams, Questions, Courses.

These entities have specific relations according to the following rules:

1) Each student enrolls in TRack and branch and intake , studies many courses, and takes many exams.

2) Each instructor works in many Tracks and teaches many courses.

3) Each Track is managed by one instructor and has many courses.

4) Each course has many topics and has many exams, and many questions.

5) Each Student can take many exams two trials per course, and each exam has many questions.

 <img src="images/allbikes-1539286251.jpg"

