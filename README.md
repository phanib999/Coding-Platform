# Coding-Platform

This project is a comprehensive Online Coding Platform designed to facilitate coding exercises and assessments for educational institutions. It features two main user roles: Admin and Student.

Admin Functionality:
Course Management: Admins can create and manage courses, each containing multiple exams.
Exam Management: Within each course, admins can add and manage exams.
Question Management: Exams consist of coding questions that admins can post, including details such as problem description, difficulty level, and test cases.
Submission Tracking: Admins can view students' submissions, including results for each test case.

Student Functionality:
Exam Participation: Students can view and participate in exams assigned to their courses.
Question Solving: Students solve coding questions within the exam, write and test their code in an embedded IDE, and submit their solutions.
Real-Time Feedback: Submissions are evaluated in real-time against predefined test cases, providing immediate feedback.
This platform streamlines the process of creating, managing, and evaluating coding assessments, making it ideal for educational settings.


Technologies Used:
Frontend: React with Ant Design for a responsive and modern user interface.
Backend: Node.js and Express.js for handling server-side logic and API requests.
Database: MongoDB for storing data related to users, courses, exams, questions, and submissions.
Code Evaluation: Integration with Judge0 API for executing and evaluating code submissions in real-time.
