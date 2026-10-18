# Student Management System (Project 1)

## Overview
A web-based Student Management System designed to streamline student data management, course tracking, and record updates efficiently.

## Problem Statement
Educational institutions need an organized, accessible, and error-free system to manage student records without relying purely on manual paperwork or complex, fragmented spreadsheets.

## Objectives
- Provide a secure login authentication layer for administrators.
- Implement full CRUD (Create, Read, Update, Delete) operations for student records.
- Enable real-time search functionality to quickly locate student data.
- Utilize local storage as a lightweight database solution.

## Target Users
- School administrators, registrars, and instructors evaluating system workflows.

## Technologies Used
- **HTML5 & CSS3**: Custom Dark Theme UI for accessible user experience.
- **JavaScript (ES6+)**: Handles dynamic manipulation and core system logic.
- **HTML5 LocalStorage**: Serves as the client-side database mechanism.

## Database Design & Storage
This application utilizes **Browser LocalStorage** as a persistent database across sessions.
- **Storage Key:** `sms_students`
- **Data Structure (JSON Array of Objects):**
  ```json
  [
    {
      "id": "2021007",
      "name": "Majorie Buendia",
      "course": "BSIT",
      "year": "4th Year"
    }
  ]

SOURCE CODE:

view-source:https://buendiamajoriecsa.github.io/studentmanagementsystem/
