## End-to-end Academic Management Tool for Attendance and CIE Marks Management

### Project Overview
The Attendance and CIE Marks Management System is a full-stack web application designed to manage and track student attendance, Continuous Internal Evaluation (CIE) marks, and academic performance. Built using Node.js, EJS, MongoDB, HTML, CSS, and Bootstrap, this system provides an easy-to-use platform for faculty, students, and college administrators to manage attendance and marks data efficiently.

## Features
### Faculty Features
- Daily Attendance Entry: Faculty members can enter the daily attendance of all courses they are handling. Attendance can be marked for any number of continuous hours during the day.
- Marks Entry: Faculty can input student marks manually for internal assessments or upload marks through CSV files.
- Attendance History: Faculty members can view and track historical attendance data for each student and course, helping them to manage performance over time.

### Student Features
- Attendance Tracking: Students can view their real-time attendance for all enrolled courses.
- Marks Viewing: Students can view their internal examination marks and academic performance.
- Download Reports: Students have the option to download their attendance and marks reports in PDF or CSV format, providing easy access for personal records or academic discussions.

### Admin Features
- College-Wide Management: Admins can manage the overall attendance and marks data for all departments in the college.
- Department-Specific Data: Admins can view, modify, and manage attendance and marks at the department level, ensuring oversight and accountability.
- Attendance and Marks History: Admins can access historical attendance and marks data, allowing for better tracking and decision-making.

## Tech Stack
#### Backend:
- Node.js: JavaScript runtime environment used for building the backend of the application.
- Express.js: Web framework for Node.js used to handle routing and middleware.

#### Frontend:
- EJS: Template engine to render dynamic content on the front end.
- HTML/CSS/Bootstrap: For designing a responsive and user-friendly interface.

#### Database:
- MongoDB: NoSQL database used to store and manage student, faculty, attendance, and marks data.

#### Other Libraries:
- Mongoose: ODM (Object Data Modeling) library for MongoDB and Node.js to interact with the database in a structured manner.
- PDF and CSV Export: Students can download reports in PDF and CSV formats using libraries such as pdfkit and json2csv.
