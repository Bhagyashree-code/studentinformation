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

### Screenshots / Interfaces (Placeholders)

**System Environment Use Case:**  
![System Environment](images/1.png)

**Context Diagram:**  
![Context Diagram](images/2.png)

**Sign-up / Home Page:**  
![Sign-up](images/3.png)

**Registration Form:**  
![Registration Form](images/4.png)

**Confirmation PDF:**  
![Confirmation PDF](images/5.png)

**Student Login Page:**  
![Student Login](images/7.jpg)

**Student Dashboard:**  
![Student Dashboard](images/8.png)

**Admin Dashboard:**  
![Admin Dashboard](images/9.png)

**Search & View Student:**  
![Search Student](images/10.png)
![Edit Student](images/11.png)

**Admin Add Student:**  
![Admin Add Student](images/12.png)

**ER Diagram:**  
![ER Diagram](images/13.png)

> *Note: Images not included yet. Add screenshots in the `images/` folder later.*

---

## **Notes**

- Make sure Apache and MySQL are running before using the system.
- This system is designed for **Windows OS**.

---

**Thanks!**
