# Java-Expense-Tracker
“Desktop-based Java Expense Tracker with charts and CSV storage."

## Project Overview
Smart Expense Tracker is a desktop-based Java application designed to help users manage their daily expenses efficiently. Users can add, delete, and categorize expenses, and visualize spending patterns using interactive bar charts. This project demonstrates **Java Swing GUI, object-oriented programming, file handling, and data visualization** skills.

---

## Features
- Add new expenses with **name, amount, and category**.
- Delete selected expenses.
- Categorize expenses: **Food, Travel, Bills, Entertainment, Others**.
- Interactive **bar chart** for expenses per category using **JFreeChart**.
- Persistent storage using **CSV file**; data is retained after closing the application.
- User-friendly interface with **table view** of all expenses.

---

## Tech Stack
- **Programming Language:** Java  
- **GUI Framework:** Java Swing  
- **Chart Library:** JFreeChart  
- **Data Storage:** CSV file  
- **Concepts Used:** OOP, Event Handling, File I/O, Collections, Data Visualization  

---

## Installation & Running the Application
1. Make sure **Java JDK** is installed on your system.  
2. Download the **JFreeChart JARs** and put them in a `lib` folder inside your project.  
3. Open terminal/command prompt in the project folder.  
4. Compile the Java files:
```bash
javac -cp lib/jfreechart-x.x.x.jar;lib/jcommon-x.x.x.jar *.java
