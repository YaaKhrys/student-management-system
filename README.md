# 🖥️ Student Management System

A simple Python-based Student Management System developed as a capstone project for the RITA Africa Python Fundamentals Course. This application allows secure login, student record management (CRUD), report generation, and file-based data persistence.

## ✅ Features
- Authentication System: Secure login with user accounts stored in users.txt
- Student Data Management: Add, view, search, update, and delete student records
- Report Generation: Generate basic reports on total students and grade distribution
- Activity Logging: Tracks user logins, logouts, and actions in activity_log.txt
- File-Based Storage: Data is stored in text files (students.txt, users.txt) for persistence


## 💻 Technologies
- Python 3
- Jupyter Notebook
- File Handling (TXT)
- Datetime module (for logging timestamps)
- Getpass module (for hidden password entry)

## 🧠 Skills Leveraged
- File handling for data storage and retrieval
- Dictionaries, loops, and conditionals for program logic
- Functions for modular code organization
- Authentication and session logging for security
- Menu-driven interfaces for user-friendly navigation.


  ## 📂 Project Structure
  stuudent_management_system/
│── main.py                 # Main program (menu-driven interface)
│── users.txt               # Stores usernames and passwords
│── students.txt            # Stores student records
│── activity_log.txt        # Stores user activity logs



## ⚙️ How To Run
1. Clone this repository:
2. git clone https://github.com/yourusername/student-management-system.git
3. cd student-management-system
4. Run the program:
5. python main.py
6. If running for the first time, create an Admin account when prompted.


## 🛡️ Usage
- Login with a valid username and password.
- Use the menu to:
    o Add a new student
    o View all students
    o Search for a student by roll number
    o Update student details
    o Delete student records
    o Generate a student report
- Logout : when done (session activity will be logged).

Sample Report Output
Student Report
Total Students: 4
Grade A: 2 student(s)
Grade B: 1 student(s)
Grade C: 1 student(s)


## 🙌 Acknowledgements
This project was created as part of the RITA Africa Python Fundamentals Program. Special thanks to Ms. Josephine B. Nyenpandi, the RITA Team, and my colleagues.

## 👩‍💻 Author
Christabell Owusu
