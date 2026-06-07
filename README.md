# University-app-
In this repository, work has been done on a group project, where a resource for the university is being developed: students and teachers.
My role as a data analyst in the project:

* An exploratory data analysis was conducted, where the following tables were analyzed: groups, courses, semester, teacher , course_offerings, grades, lessons. Checked for duplicates, missing values, and invalid data. Data overview and unique values. Also, scholarship lists and grade distribution charts were created, classes by month. Each table is described.

*  Classroom and teacher conflicts were eliminated. Conflict where one teacher is in two different classrooms at the same time. Conflict where two teachers are in one classroom at the same time. And a conflict where two groups are in one classroom. It is important to note that in the latter case, only practical classes are considered, because according to the logic of lectures and seminars, classes are held in several groups at the same time. Conflicts were eliminated using the drop_duplicates method, saving only the first record.

* An analysis of three A\B tests was conducted. Among them: Optimization of the number of courses per group, Adding a student progress block on the main page, Updating the teacher profile page.
A dashboard was created.
