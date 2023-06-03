
# Database Systems Project

The university system cares about the attendence of the students in all lectures. Therefore, any student will be deregistered from any course, if this student did not attend more than 25% of the lectures in the semester. Thanks to our tutors who are tracking the attendence and persence of students by using excel based files. However, due to high demand and large number of students and lectures, it was mandatory to have better system to track the attendence. Thus, this project shall provide a solution which is user-friendly and easy to use rather using excel files.

## Information

Programming language: Java

Compiler: javac 1.8.0_301

Program: Attendance tracking systems

## Installing

- Download and install [Apache NetBeans IDE 13](https://netbeans.apache.org/download/nb13/nb13.html) if you do not already have it installed.
- Download and install [JDK FX](https://cdn.azul.com/zulu/bin/zulu18.32.13-ca-fx-jdk18.0.2.1-win_x64.zip) using zulu18.28.13 of JDK 18.0.
- Download the "Attendance tracking systems" project files and open them in NetBeans.
- Run the "attendease.sql" script in you PostgreSQL database to create the necessary tables and data.
- Add the required [jar files](https://drive.google.com/file/d/1fRQsZhwIvCiUFjyl6WswBDY4VmQNT-gP/view) for PostgreSQL and Apache POI .
- Build and run the project.

Alternatively, you can use IntelliJ IDEA Maven to build and run the project directly. Simply open the project in IntelliJ IDEA and follow the instructions for building and running Maven projects.

## Important notes

- The project is based on three roles: Admin of the database, Admin of the teacher, and Teacher. Each role has limited access to the database.
- Any account registered in the project must be verified by the Admin using the Admin console or by the database Admin.
- The project is designed to be simple to use, and all features and functionalities are clear and easy to understand.

## Java Packages
The "Attendance tracking systems" attendance tracking system is organized into the following Java packages:

### classes package
This package contains the following Java classes:

- **Attendance Class** : A class that represents attendance records for a student in a lecture.
- **Course Class** : A class that represents a course and its related information, such as course code and course name.
- **Lecture Class** : A class that represents a lecture and its related information, such as lecture date and time.
- **Section Class** : A class that represents a section of a course and its related information, such as section code and section name.
- **Student Class** : A class that represents a student and their related information, such as student ID and student name.
- **Student Attend Class** : A class that represents the attendance status of a student in a lecture.
- **Takes Class** : A class that represents the enrollment of a student in a course section.
- **User Class** : A class that represents a user and their related information, such as username and password.

### com.example.database package

This package contains the following Java classes:

- **Login Controller** : A class that provides the functionality for the Login interface.
- **Admin Controller** : A class that provides the functionality for the Admin interface.



## Participants
*This is a pair project (a team of 2 students) who are as follows:*

  - **Abdullah Ahmed Muhaisen** - *120201347*
  - **Hasan Younis Sammour** -    *120201047*



## responsibilities and the timeline
We divided the project into sections, taking into account the strengths and weaknesses

of each of us, and the division was as follows:

- **Book and User Classes:** Written by Hasan Sammour in (18/12/2022).

- **GUI Handeling:** Written by Abdullah Muhisen (Between 20/12/2022 and 24/12/2022)

- **Other classes** TreeMap and HashMap are used to make the functions we need to
    handle with the Basic Operation that our system will handle with.

It was written in cooperation between the two students, as we were meeting
during the period from 18/12/2022 to 28/12/2022 to consult, put forward ideas,
and cover the weaknesses of each of us, either at the university or by communicating
on WhatsApp.

### Notes
* Some modifications and reforms were added to the codes during
  the exams period by the student Abdullah Muhaisen,
  to bring you the Program that is in your hands.


* We met again to discuss the amendments that were made during
  the exams period on Wednesday 11/1/2023 and two days later
  to bring you the Program that is in your hands.
  we started preparing the (README.md) file that you have now
  , and then handing over the project.