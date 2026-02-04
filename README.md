# studentinformation
Student registration and information portal using PHP and MySQL
# studentinformation
Student registration and information portal using PHP & MySQL

This web-based application system is a Student Registration System for university students as well as administrators. It allows students to register for semesters in various courses, view and edit their details, and enables admins to manage all student records efficiently. By replacing manual paperwork, this system maximizes work efficiency while remaining easy to understand and use.

The system contains a relational database with:
- List of courses with their maximum limits
- Student details
- Hostel details

---

## **Running this project locally**

1. Install the latest version of **XAMPP** on your PC.
2. Run **Apache** and **MySQL** from the XAMPP control panel. Fix any port conflicts if they arise.
3. Paste the `studentinformation-master` folder under `xampp/htdocs/`.
4. Open `localhost/phpMyAdmin` and create a new database named `student`.
   - Default user: `root`
   - Password: *(leave empty)*
5. Import the provided `.sql` file into the database. Ensure there are no errors.
6. Open [http://localhost/studentinformation-master](http://localhost/studentinformation-master) in your browser.
7. Example login credentials:
   - **Student:** enrolmentid - `GH1234`, password - `12345678`
   - **Admin:** username - `0000`, password - `amu_reg`

---

## **Features & Improvements**

- Fixed styling bugs in the UI
- Improved student details form
- Admin login table added in the database (not hardcoded)
- Student photo added in generated PDFs
- Image details stored in a database table for mapping
- Admin can filter student lists by year, class, division, gender, caste, category, religion, and age
- Export and print student lists

---

## **System Overview**

**Actors:**  
- **Student:** Registers, views, and updates personal and academic information.  
- **Admin:** Manages student registrations, updates, and course data.

**Database:**  
- Relational tables for courses, students, hostel details, and images

**Technology Stack:**  
- PHP  
- MySQL  
- HTML/CSS  
- Bootstrap

---

### Screenshots / Interfaces

*(Add your screenshots in the `/images` folder and link here)*

- Student registration form
- Student update form
- Admin dashboard
- Search student functionality
- Export & print options

---

### ER Diagram

*(Add ER diagram image here if available)*

---

## **Notes**

- Make sure Apache and MySQL are running before using the system.
- This system is designed for **Windows OS**
- 
# Student Information System

Student registration and information portal using PHP and MySQL.

This web-based application system is designed for students of the university as well as the administrator. Students can register for semesters and courses, view and edit their details. Admin can view, edit, add, and remove students, as well as manage courses efficiently.

The system contains a relational database with:
- List of courses with maximum limit
- Student details
- Hostel details

---

## Features

- Student registration and login
- Admin login to manage students
- Upload student photo
- View and edit student information
- Generate PDF confirmation of registration
- Search students by year, course, gender, category, religion, and age
- Export student list to Excel

---

## Installation

1. Install the latest version of **XAMPP** on your PC.
2. Start **Apache** and **MySQL** from XAMPP Control Panel.
3. Paste the `studentinformation-master` folder into `xampp/htdocs`.
4. Open **localhost/phpMyAdmin**, create a new database named `student`.
5. Import the provided `.sql` file into the database.
6. Open the project in your browser: [http://localhost/studentinformation-master](http://localhost/studentinformation-master)
7. Use example credentials:
   - **Student:**  
     - Enrollment ID: `GH1234`  
     - Password: `12345678`
   - **Admin:**  
     - Username: `0000`  
     - Password: `amu_reg`

---

## Screenshots

**Home Page / Student Registration**  
![Home Page](images/1.png)

**Student Details Form**  
![Student Form](images/4.png)

**Student Confirmation PDF**  
![Confirmation PDF](images/5.png)

**Student Login Page**  
![Student Login](images/7.jpg)

**Student Dashboard / Details**  
![Student Dashboard](images/8.png)

**Admin Dashboard**  
![Admin Page](images/9.png)

**Student List and Search**  
![Student List](images/10.png)

**View/Edit Student Details**  
![Edit Student](images/11.png)

**Admin Add Student Form**  
![Admin Add](images/12.png)

**ER Diagram**  
![ER Diagram](images/13.png)

> Replace `images/*.png` and `images/*.jpg` with your actual screenshots in the `images/` folder.

---

## Database Structure

- **Student Table:** `student_details`
- **Courses Table:** `course`
- **Hostel Table:** `hostel_details`
- **Admin Table:** `admin` (for admin login)

---

## Improvements / Custom Features

1. Styling bugs removed
2. Improved student details form
3. Admin login stored in database
4. Student photo added in PDF confirmation
5. Image mapping table for better organization
6. Admin can generate year/class/division/gender/caste/category/religion/age-wise student lists
7. Print and export options for admins

---

## Author

Bhagyashree N  
Email: bhagyashree3598@gmail.com




