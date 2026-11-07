# DJIHS Enrollment System ![App Showcase](DJIHS_showcase.gif)

## Short Description
Role-based school enrollment web system for Don Jose Integrated High School. It helps school staff handle enrollment, student records, section assignment, document tracking, and reporting from one internal portal.

## What It Is
This project is a browser-based enrollment management system with separate dashboards for six school roles: Admin, Adviser, Key Teacher, ICT Coordinator, Registrar, and Subject Teacher. Based on the repo structure and login flow, it is designed for internal staff use rather than public student self-registration.

## Who It's For
- Primary users: school staff responsible for enrollment processing, student record management, sectioning, academic-year setup, and account administration
- Main persona: registrar or ICT coordinator who needs to review applications, manage student data, and coordinate school-year operations across multiple staff roles

## Tech Stack
- PHP
- MySQL via PDO
- HTML
- Vanilla JavaScript
- Tailwind CSS via CDN
- PhpSpreadsheet (`phpoffice/phpspreadsheet`) for Excel import and export
- XAMPP-style local environment (`localhost`, MySQL `root`, empty password in database config)

## Key Features
- Role-based login with automatic dashboard routing based on the user account role
- Enrollment submission, pending review, approval, and rejection workflows
- Student management with search, detail views, status tracking, and dashboard statistics
- Academic year, section, and strand management for school organization
- User account management with activation, deactivation, reset, and password change support
- Bulk student import from CSV or Excel using provided templates
- Document checklist tracking, audit logging, analytics, metrics export, database backup, and SF1 export

## Feature Notes
### Enrollment Management
- Submit new enrollments
- View pending enrollments
- Approve or reject applications
- Prevent duplicate enrollment by LRN and academic year
- Support multiple enrollment types such as regular, transferee, repeater, ALS, and balik-aral

### Student Management
- List and search students
- View student details and latest enrollment info
- Track section assignments
- Show dashboard statistics and counts by grade level

### Operations and Reporting
- Track required documents per enrollment
- Create audit log entries for key changes
- Export SF1 using an Excel template
- Export analytics and metrics
- Create MySQL backups from the backend

## Reflection / Challenges
- This project was built for a Software Engineer course in Mapua Malayan Colleges Laguna.
- Motivation: create one system that centralizes enrollment-related tasks for school staff.
- Challenge: the project experienced scope creep, with many additional features being added over time.
- Lesson learned: define scope earlier, protect core requirements, and plan role-based features with tighter boundaries so the team can deliver a more stable system.
