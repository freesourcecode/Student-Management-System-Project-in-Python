# Student Management System Project in Python with Source Code

A **Student Management System Project in Python** is another name for a Student Information System (SIS).

These systems help faculty members talk to each other about students and coordinate their schedules.

This system makes it easier for both parents and administrative staff to keep track of information.

## About Student Management System Python Project

This Student Management System Python Project is developed using Python programming language. The project report contains a Python script (MainStudent.py).

This is a simple console-based system that’s very clean to recognize and use.

Talking student management system in Python consists of basic features that encompass Adding students, viewing college students, searching for college students, and getting rid of the student.

In this mini undertaking, there may be no such login device. In this manner, he/she can use all the available functions without problems with no restrictions.

Before we proceed further, let’s first watch the video here.

To start creating a Student Management System using Python, make sure you have PyCharm IDE installed on your computer.

## How to Create Student Management System Project in Python?

1. **Create a Project Name**

First step open the PyCharm IDE click “File” select “New Project” and then create a project name after that click the “create” button.

<img width="780" height="464" alt="image" src="https://github.com/user-attachments/assets/63ece268-2fff-4d66-b98a-78ea5b752b3e" />


2. **Create a Python File**
The second step after creating a project name, “right” click the project name and the click “New” after that choose “Python File“.

<img width="1366" height="804" alt="image" src="https://github.com/user-attachments/assets/882ab3d3-9483-472b-8f0a-04c953178d8a" />

3. **Name the Python File**

The third step after choosing Python File name the file “Student Management System” and then click “Enter”.Name the Python File in Student Management System

<img width="1366" height="728" alt="image" src="https://github.com/user-attachments/assets/724e58ff-fa81-4467-ab8b-2fff953f8264" />

4. **The actual code**

Now you can start coding, you are free to copy the code that being provided below.

## Student Management System Project Code Explanation

1. **Main Module**
This module displayed the main module of the system that can control all the modules of the system.

You are free to copy and paste this code on your Python File.

```
global studentlist
studentlist = ["jason yap", "Jake ramos", "James Pascual", "Jester Paglinga"]

def studentmanagement():

print("\n++++++ Welcome to Evanz College Student Management System ++++++\n")
print("[Choice 1: Showing the List of Student]")
print("[Choice 2: Add New Student]")
print("]Choice 3: Searching Student]")
print("[Choice 4: Deleting a Student]\n")

try:
x = int(input("Enter a choice: "))
except ValueError:
exit("\nHy! This is not a Number")
else:
print("\n")
```

2. **Student List**

This module is to View the List of Students.

```
if(x==1):
print("Student List\n")
for students in studentlist:
print("++ {} ++".format(students))
```

In the code above, which is for the view of all the student lists in the table

3. **Add New Student**

This module is for adding a new student.

```
elif(x==2):
studentnew = input("Enter New Student: ")
if(studentnew in studentlist):
print("\nThis Student {} Already In The Table".format(studentnew))
else:
studentlist.append(studentnew)
print("\n++ New Student {} Added Successfully ++\n".format(studentnew))
for students in studentlist:
print("++ {} ++".format(students))
```

In the code above, which is for adding a new student to the table.

4. **Search Student**

This module is for searching a student’s name.

```
elif(x==3):
studentsearching = input("Choose Student Name To Search: ")
if(studentsearching in studentlist):
print("\n++ There is a Record Found of this Student {} ++".format(studentsearching))
else:
print("\n++ There is No Record Found Of this Student {} ++".format(studentsearching))
```
In the code above, which is for searching for the name of the student in the table.

5. **Delete Student**

This module is for deleting a student’s name.

```
elif(x==4):
studentdelete = input("Choose a Student Name To Delete: ")
if(studentdelete in studentlist):
studentlist.remove(studentdelete)
for students in studentlist:
print("++ {} ++".format(students))
else:
print("\n++ There is No Record Found of This Student {} ++".format(studentdelete))
```

In the code above, which is to delete a student’s name in the table.

### 📌 Here's the full documentation for the [Student Management System Project in Python](https://itsourcecode.com/free-projects/python-projects/student-management-system-project-in-python-with-source-code/)

## Related Articles:

* **[Student Management System in PHP](https://itsourcecode.com/free-projects/php-project/student-management-system-in-php-with-source-code/)**
* **[Student Management System in Django](https://itsourcecode.com/free-projects/python-projects/student-management-system-project-in-django-with-source-code/)**
* **[Student Management System Project in Android](https://itsourcecode.com/android-projects/student-management-system-project-in-android-source-code/)**
* **[Student Information Management System in PHP](https://itsourcecode.com/free-projects/php-project/st-columban-student-information-management-system/)**


