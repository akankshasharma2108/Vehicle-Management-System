# Vehicle Management System

## 1. Project Overview

The **Vehicle Management System** is a Java-based console application developed to manage vehicle records in a simple and organized manner. It allows users to add, view, search, update, and delete vehicle information.

The project demonstrates core Java concepts such as **Object-Oriented Programming, ArrayList, methods, exception handling, and file handling**.

## 2. Features

* Add new vehicle details
* View all vehicles
* Search for a vehicle
* Update vehicle information
* Delete vehicle records
* Maintain vehicle history
* Handle invalid inputs
* Menu-driven console interface

## 3. Project Structure

```text
Vehicle_Management/
│
├── Main.java
├── Vehicle.java
├── VehicleManager.java
├── ParkingHistory.java
│
├── parking_history.txt
│
├── Flowchart.png
├── Class_Diagram.png
├── Use_Case_Diagram.png
│
├── Test_Results.pdf
├── Project_Report.pdf
├── Statement_File.pdf
│
├── README.md
└── .gitignore
```

### File Description

| File                   | Description                                    |
| ---------------------- | ---------------------------------------------- |
| `Main.java`            | Contains the main program and menu             |
| `Vehicle.java`         | Defines vehicle details and related methods    |
| `VehicleManager.java`  | Manages vehicle operations                     |
| `ParkingHistory.java`  | Handles vehicle history                        |
| `parking_history.txt`  | Stores vehicle history records                 |
| `Flowchart.png`        | Shows the program flow                         |
| `Class_Diagram.png`    | Represents the classes and their relationships |
| `Use_Case_Diagram.png` | Shows the interaction between user and system  |
| `Test_Results.pdf`     | Contains test cases and their results          |
| `Project_Report.pdf`   | Complete project documentation                 |
| `Statement_File.pdf`   | Project statement/document                     |
| `README.md`            | Project information and instructions           |
| `.gitignore`           | Specifies files ignored by Git                 |

## 4. Technologies / Tools Used

* **Programming Language:** Java
* **Concepts:** OOP, ArrayList, Methods, Exception Handling, File Handling
* **IDE:** Visual Studio Code
* **JDK:** 17 or above
* **Version Control:** Git & GitHub

## 5. Installation & Run

### Prerequisites

Install **JDK 17 or above**.

Check the installation using:

```bash
java --version
javac --version
```

### Steps to Run

1. Clone or download the repository.
2. Open the project folder in VS Code.
3. Open the terminal in the project folder.
4. Compile the Java files:

```bash
javac *.java
```

5. Run the main program:

```bash
java Main
```

6. Follow the options displayed in the console.

## 6. Testing Instructions

Test the following operations:

* Add a new vehicle with valid details.
* View all registered vehicles.
* Search for an existing vehicle.
* Search for a non-existing vehicle.
* Update vehicle details.
* Delete a vehicle.
* Check whether vehicle history is correctly stored in `parking_history.txt`.
* Enter invalid input and verify that the program handles it properly.

Detailed test cases and results are provided in **`Test_Results.pdf`**.

## 7. Project Documentation

The repository contains:

* **Diagrams** – Flowchart, Class Diagram, and Use Case Diagram
* **Test Results** – Test cases and their outputs
* **Project Report** – Complete project documentation
* **Statement File** – Required project statement/document

## 8. Expected Result

The system should successfully manage vehicle records through a simple console-based interface. Users should be able to perform all available vehicle operations, and the vehicle history should be stored correctly in the text file.
