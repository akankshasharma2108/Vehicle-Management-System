# Vehicle Management System

## 1. Project Overview

The **Vehicle Management System** is a Java-based console application developed to manage vehicle parking activities in a simple and organized manner.

The system allows users to register vehicles, park and remove vehicles, display parking slots, view vehicle details, maintain parking history, and view parking statistics.

The project demonstrates core Java concepts including **Object-Oriented Programming, classes and objects, ArrayList, methods, loops, conditional statements, exception handling, and file handling**.

## 2. Features

The system provides the following features:

1. **Register Vehicle** – Register a vehicle with the required vehicle details.
2. **Park Vehicle** – Park a registered vehicle in an available parking slot.
3. **Remove Vehicle** – Remove a parked vehicle from the parking slot.
4. **Display Parking Slots** – View the current status of parking slots.
5. **Vehicle Details** – View the details of a registered vehicle.
6. **Parking History** – View previously recorded parking activities.
7. **Parking Statistics** – View total, occupied, and available parking slots.
8. **Exit** – Safely exit the application.

## 3. Project Structure

```text
Vehicle_Management/
│
├── vehicle_management/
│   ├── Main.java
│   ├── ParkingManager.java
│   ├── ParkingRecord.java
│   ├── ParkingSlot.java
│   ├── ParkingSystem.java
│   └── Vehicle.java
│
├── .gitignore
│
├── Daigrams&Test
│   ├── test
│   │   └── Test Screenshots
│   │
│   └── diagrams
│       └── Project Diagrams
│
├── README.md
├── Statement.md
└── test_results.txt
```

### File and Folder Description

* **`vehicle_management/`** – Contains all 6 Java source files of the project.
* **`.gitignore`** – Contains files and folders that should not be tracked by Git.
* **`test/`** – Contains screenshots/evidence of the performed tests.
* **`diagrams/`** – Contains diagrams used in the project report.
* **`README.md`** – Provides project information, features, setup, and testing instructions.
* **`Statement.md`** – Contains the problem statement, project scope, target users, and high-level features.
* **`test_results.txt`** – Contains the detailed test cases, inputs, expected results, actual results, and status.

## 4. Technologies / Tools Used

* **Programming Language:** Java
* **Concepts:** Object-Oriented Programming, Classes & Objects, ArrayList, Methods, Loops, Conditional Statements, Exception Handling, File Handling
* **IDE:** Visual Studio Code
* **JDK:** JDK 17 or above
* **Version Control:** Git & GitHub

## 5. Installation & Run

### Prerequisites

Install **JDK 17 or above** on your system.

Check the Java installation using:

```bash
java --version
javac --version
```

### Steps to Run

1. Clone or download the project repository.
2. Open the repository in **Visual Studio Code**.
3. Open the `vehicle_management` folder.
4. Open the terminal inside the `vehicle_management` folder.
5. Compile the Java files:

```bash
javac *.java
```

6. Run the main program:

```bash
java Main
```

7. Select the required option from the menu displayed in the terminal.

## 6. Instructions for Testing

The application can be tested using all the available menu options:

### Test 1 – Register Vehicle

Enter valid vehicle details and verify that the vehicle is registered successfully.

### Test 2 – Park Vehicle

Enter a registered vehicle and verify that it is assigned to an available parking slot.

### Test 3 – Remove Vehicle

Enter a parked vehicle and verify that it is removed and the parking slot becomes available.

### Test 4 – Display Parking Slots

Check whether the system correctly displays occupied and available parking slots.

### Test 5 – Vehicle Details

Enter a registered vehicle number and verify that the correct vehicle details are displayed.

### Test 6 – Parking History

Check whether previous parking and removal activities are recorded and displayed correctly.

### Test 7 – Parking Statistics

Verify the total number of parking slots, occupied slots, and available slots.

### Test 8 – Exit

Select the Exit option and verify that the application terminates safely.

Detailed test cases and their results are available in **`test_results.txt`**, while screenshots of the testing process are available in the **`test`** folder.

## 7. Expected Result

The system should successfully perform all vehicle and parking management operations. Vehicle records should be maintained correctly, parking slots should be updated according to vehicle activity, parking history should be recorded, and parking statistics should be displayed accurately.
