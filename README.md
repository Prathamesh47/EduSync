# 📘 Substitution Management System

A web application designed to streamline lecture substitutions for teachers requiring urgent leave. This system helps educational institutions effectively manage teacher absences by dynamically reassigning lectures to available teachers based on their timetable and free time slots, ensuring no classes are left unattended.

## 🎯 Project Overview

The Substitution Management System addresses the problem of unplanned teacher absences, helping institutions avoid free periods and make full use of teaching time. By analyzing each teacher's timetable, the system finds suitable replacements for vacant slots, fostering efficient use of time and resources.

- **Purpose**: To automate substitution assignments, reducing administrative overhead.
- **Key Outcome**: Minimizes disruption in lecture schedules and improves time utilization for both teachers and students.

## 🚀 Features

- **Teacher Leave Management**:
  - Teachers can log in to request urgent leave directly through the platform.
  
- **Dynamic Substitution Allocation**:
  - The system dynamically finds and assigns available teachers based on their timetables and free time slots.
  - Ensures optimal use of time by avoiding unnecessary free periods.

- **Timetable Integration**:
  - Imports and stores the timetable of all teachers.
  - Cross-references schedules to identify suitable substitutes in real-time.

- **User-Friendly Interface**:
  - Simple interface with clear options for requesting leave and viewing substitution assignments.
  
## 🛠️ Technology Stack

- **Frontend**: HTML, CSS, and JavaScript for a responsive and interactive user experience.
- **Backend**: Node.js for server-side handling and processing substitution assignments.
- **Database**: (Optional - if used) Could use a database like MongoDB or SQLite to store teacher timetables and leave records.

## 📂 Project Structure

```plaintext
📦 project-root
├── 📁 public
│   ├── 📄 index.html
│   ├── 📄 styles.css
│   └── 📄 script.js
├── 📁 src
│   ├── 📄 app.js
│   ├── 📁 controllers
│   │   └── 📄 substitutionController.js
│   ├── 📁 models
│   │   └── 📄 timetableModel.js
│   └── 📁 routes
│       └── 📄 apiRoutes.js
├── 📄 README.md
└── 📄 package.json
