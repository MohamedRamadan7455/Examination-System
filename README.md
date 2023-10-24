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

![Examination_System(2) 1](https://github.com/MohamedRamadan7455/Examination-System/assets/120788796/23f6eaf1-d3a1-4364-8701-d49b5d12ef6e)


# Mapping
]
![Mapping Final(1)(5) drawio](https://github.com/MohamedRamadan7455/Examination-System/assets/120788796/2b6de7dc-deaa-4668-b249-5804b32dc9e7)

#  Database Physical Schema

![data](https://github.com/MohamedRamadan7455/Examination-System/assets/120788796/9657b920-1c76-4c01-a229-e39635453ec2)

 
