# exp2.2
Java Assignment – Parts A, B, and C
🧩 Overview

This project demonstrates three core Java concepts through separate parts:

Part A: Basic Input Handling and Summation

Part B: Object Serialization and Deserialization

Part C: File Handling with Employee Records

Each part is designed as a standalone program with its own main() method.

⚙️ Requirements

Java JDK 8 or above

Any text editor or IDE (e.g., IntelliJ IDEA, Eclipse, VS Code)

Command-line or terminal for compilation and execution

📂 Project Structure
├── PartA.java
├── PartB.java
├── PartC.java
├── student.dat
├── employees.txt
└── README.md

🧮 Part A – Sum of Integers
📖 Description

Reads a list of integers from the user, stores them in a list, and prints the total sum.

🧠 Concepts Used

Input using Scanner

String splitting and parsing

List and loop-based aggregation

▶️ How to Run
javac PartA.java
java PartA

🧾 Example

Input:

Enter integers separated by space:
10 20 30 40


Output:

Sum of integers: 100

🧍‍♂️ Part B – Object Serialization
📖 Description

Demonstrates Java serialization and deserialization using a Student class.

🧠 Concepts Used

Serializable interface

ObjectOutputStream and ObjectInputStream

Reading/writing objects to files

▶️ How to Run
javac PartB.java
java PartB

🧾 Example Output
Deserialized Student: ID: 1, Name: Sujal, Grade: 8.9


A binary file named student.dat is created to store the serialized object.

🧾 Part C – Employee File Management System
📖 Description

Implements a simple menu-driven system for managing employee records using text file storage.

🧠 Concepts Used

File I/O (BufferedReader, BufferedWriter)

Menu-driven loop using Scanner

Data persistence in a text file

▶️ How to Run
javac PartC.java
java PartC

🧾 Menu Options
1. Add Employee
2. Display Employees
3. Exit

🧩 Example Interaction
1. Add Employee
Enter ID: 101
Enter Name: Riya
Enter Designation: Developer
Enter Salary: 60000
Employee added successfully.

2. Display Employees
Employee Records:
101,Riya,Developer,60000.0

💾 File Outputs

student.dat → Binary file storing serialized Student object

employees.txt → Text file storing employee records in CSV format

🧹 Notes

Ensure all .java files are in the same directory.

Run each part separately since all have independent main() methods.

Use Ctrl + C to terminate input if stuck (for some terminals).

👨‍💻 Author

Geetika Srivastava
Java Programming Assignment – Web Applications Using Servlets and JSP (Part A, B & C)
