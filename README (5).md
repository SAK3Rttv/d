
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

- **Attendance Class**
- **Course Class**
- **Lecture Class**
- **Section Class**
- **Student Class**
- **Student Attend Class**
- **Takes Class**
- **User Class**

### com.example.database package

This package contains the following Java classes:

- **Login Controller**
- **Register Controller**
- **Admin Controller**
- **User Controller**
- **Authorization Controller**
- **View Lecture Controller**
- **Add Course Controller**
- **Add Section Controller**
- **Add Student Controller**
- **Add lecture Controller**
- **View lecture Controller**
- **Register lecture Controller**
- **Register attendece Controller**

## Participants
*This is a pair project (a team of 3 students) who are as follows:*

  - **Abdullah Ahmed Muhaisen** - *120201347*
  - **Hasan Younis Sammour** -    *120201047*


## responsibilities and the timeline
We divided the project into sections, taking into account the strengths and weaknesses

of each of us, and the division was as follows:

- **Datebase SQL:** Written by M and A.

- **Java and GUI Handeling:** Written by Abdullah Muhisen.