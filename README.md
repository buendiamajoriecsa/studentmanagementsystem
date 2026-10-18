# Student Management System

## 1. Project Title
**Student Management System**

## 2. Project Overview
The **Student Management System** is a lightweight, responsive web application designed to simplify and streamline the process of managing student records. Hosted directly on GitHub Pages, it provides an accessible interface for administrators and educators to store, search, and manage student information efficiently.

## 3. Problem Statement
Educational institutions often struggle with manual, paper-based student record tracking or overly complex legacy databases that require expensive setup and maintenance. These traditional methods can lead to data redundancy, difficulties in searching for student records, and higher chances of data entry errors.

## 4. Objectives
* To digitize student record tracking using a web-based interface.
* To provide quick search and filtering capabilities for student profiles.
* To reduce data entry errors and simplify record organization.
* To deploy a lightweight, zero-cost, and easily accessible application via GitHub Pages.

## 5. Target Users
* **School Administrators / Staff:** For efficient record keeping, search, and updates.
* **Instructors / Teachers:** To view student details and class lists quickly.
* **Students:** To view basic academic profile information.

## 6. Technologies Used
* **Frontend:** HTML5, CSS3
* **Hosting & Deployment:** GitHub Pages
* **Storage / Handling:** Client-side local storage / JavaScript record handling

## 7. System Features
* **Authentication:** Secure login interface for system users.
* **Student Record Search & Filter:** Quick search bar to locate specific student profiles by ID or Name.
* **Record Management:** Add, view, edit, and organize basic student information.
* **Responsive Layout:** Clean user interface optimized for desktop and mobile viewing.

## 8. System Architecture
The application runs as a static web application hosted on **GitHub Pages**. User requests are handled on the client-side browser, ensuring fast loading times and smooth interaction without the need for complex server configurations.

## 9. Database Design
The current implementation utilizes structured client-side JSON/data objects with the following schema:

| Field Name     | Data Type | Description                      |
| -------------- | --------- | -------------------------------- |
| `student_id`   | String    | Unique identification number     |
| `full_name`    | String    | Complete name of the student     |
| `course`       | String    | Academic program / course enrolled|
| `year_level`   | String    | Current academic year level      |
| `email`        | String    | Contact email address            |
| `status`       | String    | Enrollment status (Active/Inactive)|

## 10. Screenshots
*(Add your project screenshots here)*
```markdown
![Login Screen](assets/login-preview.png)
![Dashboard Overview](assets/dashboard-preview.png)
