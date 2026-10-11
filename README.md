# AUT Student Transcript System

Automated transcript generator for a fictional student database (100 students).
Search for a student or click a name, and the tool builds the full academic transcript automatically — no manual work per student.

## Features
- 100 fictional students (ID, name, university email, faculty, program, major, group, enrollment date, status)
- 10 courses per student across two semesters: course code, title, final score, letter grade, ECTS credits
- Automatic GPA: semester GPA, cumulative GPA, total credits earned
- Search by name, ID, major, group or faculty; sorting by name / GPA / group
- Transcript in a professional academic format (AUT / ASU style)
- English / Russian transcript toggle
- Add, edit and delete students, courses and semesters (saved in the browser's localStorage)
- Analytics: average GPA by major, top-5 students, Dean's List (GPA ≥ 3.5)

## Grading scale
A ≥ 93 (4.0), A- ≥ 90 (3.7), B+ ≥ 87 (3.3), B ≥ 83 (3.0), B- ≥ 80 (2.7), C+ ≥ 76 (2.3), C ≥ 70 (2.0), D ≥ 60 (1.0), F < 60.

## Run
Open `index.html` in a browser. No build step or dependencies.

## Data
`data/academic_records_exact_style_20_students.xlsx` is the source for the first 20 students. All data is fictional.
