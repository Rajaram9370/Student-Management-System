# Student Management System

A Web-based Student Management System built using Python and Django. This system provides distinct portals for Admins (HOD), Staff (Teachers), and Students, allowing easy management of courses, subjects, attendance, results, feedback, and leave applications.

## Features

### A. Admin Users Can:
1. See overall summary charts of students' performance, staff performance, courses, subjects, leaves, etc.
2. Manage Staff (Add, Update, and Delete)
3. Manage Students (Add, Update, and Delete)
4. Manage Courses (Add, Update, and Delete)
5. Manage Subjects (Add, Update, and Delete)
6. Manage Sessions (Add, Update, and Delete)
7. View Student Attendance records
8. Review and reply to student/staff feedback
9. Approve or reject leave applications

### B. Staff/Teachers Can:
1. View overall student performance charts, subjects, and leave statuses.
2. Take and update student attendance.
3. Add and update students' exam results.
4. Apply for leaves.
5. Send feedback to the Admin.

### C. Students Can:
1. View attendance percentages and overall charts.
2. View exam results.
3. Apply for leaves.
4. Send feedback to the Admin.

## Installation & Setup

1. **Clone the repository:**
   ```bash
   git clone <your-repository-url>
   cd django-student-management-system
   ```

2. **Create and Activate a Virtual Environment:**
   * **Windows:**
     ```bash
     python -m venv venv
     venv\Scripts\activate
     ```
   * **macOS/Linux:**
     ```bash
     python3 -m venv venv
     source venv/bin/activate
     ```

3. **Install Requirements:**
   ```bash
   pip install -r requirements.txt
   ```

4. **Run the Development Server:**
   ```bash
   python manage.py runserver
   ```
   Open `http://127.0.0.1:8000/` in your browser.

## Login Credentials

To test the system, you can use the following default credentials:

* **Admin:**
  * **Email:** admin@gmail.com
  * **Password:** admin
* **Staff:**
  * **Email:** staff@gmail.com
  * **Password:** staff
* **Student:**
  * **Email:** student@gmail.com
  * **Password:** student
