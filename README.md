Student Management System (SMS)

📌 Project Overview

The Student Management System (SMS) is a lightweight, console-based Java application designed to digitize the management of student records. Built entirely using Core Java, this project demonstrates the practical application of Object-Oriented Programming (OOP) principles and File Handling for data persistence.

Instead of a complex database setup, this system uses a local text file (student-data.txt) to store data in a persistent CSV-like format, making it portable and easy to deploy without external dependencies.

✨ Features
This application covers the complete CRUD (Create, Read, Update, Delete) lifecycle for student records:
🔐 Secure Login: Simple authentication mechanism protecting the dashboard.
📝 Create Student: Add new student records (ID, Name, Address, Age, Class).
👀 Read All Students: View the complete roster of students stored in the system.
🔍 Search Student: Find specific student details using their unique Student ID.
✏️ Update Data: Modify existing student details (Name, Address, etc.).
🗑️ Delete Records: Remove specific student data or reset the entire database file.
💾 Data Persistence: Automatically saves all changes to student-data.txt.


🛠️ Technologies & Tools Used
Language: Java (JDK 1.8 or higher)
Concepts: Core Java (Loops, Exception Handling), OOP (Encapsulation, Interfaces), Java I/O (File Handling).
IDE/Editor: VS Code / Eclipse / IntelliJ IDEA

🚀 Steps to Install & Run
Prerequisites
Ensure you have Java Development Kit (JDK) installed. Verify by running:

java -version


1. Compilation
This project uses a package structure (service and repository). You must compile all files from the root directory.

Open your terminal in the main project folder and run:

mkdir out
javac -d out ApplicationMain.java service/*.java repository/*.java


2. Execution
Run the compiled application using the classpath flag:

java -cp out ApplicationMain


3. Login Credentials
Use the following default credentials to access the system:

Username: admin
Password: root


🧪 Instructions for Testing
Follow these steps to verify the project functionalities:

1) Login: Launch the app and enter the credentials (admin / root).
   
 2)Add a Student: Select Option 1. Enter a unique ID (e.g., 101), Name, and other details.

 3)Verify Addition: Select Option 2 to "Read All Students". Confirm your new entry appears.

 4)Test Persistence: Close the application completely. Run it again. Select Option 2 to ensure the data is still there.
 
 5)Modify Data: Select Option 4 (Update). Enter the ID 101 and provide new details.

 6)Delete: Select Option 5 to remove the student or delete the file.

