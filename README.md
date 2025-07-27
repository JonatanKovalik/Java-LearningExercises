# ☕ Java-LearningExercises - Exploring Java Fundamentals

[![License](https://img.shields.io/github/license/JonatanKovalik/Java-LearningExercises?style=flat)](https://github.com/JonatanKovalik/Java-LearningExercises/blob/main/LICENSE)
[![GitHub last commit](https://img.shields.io/github/last-commit/JonatanKovalik/Java-LearningExercises?style=flat)](https://github.com/JonatanKovalik/Java-LearningExercises/commits/main)
[![GitHub top language](https://img.shields.io/github/languages/top/JonatanKovalik/Java-LearningExercises?style=flat)](https://github.com/JonatanKovalik/Java-LearningExercises)

## 📜 Project Overview

This repository is a curated collection of various practice projects and small applications developed in Java. Each project focuses on demonstrating and reinforcing fundamental Java language features, core programming constructs, and key Object-Oriented Programming (OOP) concepts through hands-on exercises. The aim is to build a solid foundation in Java programming by tackling diverse challenges.

## ✨ Projects / Exercises Included

Here are the individual projects and exercises currently included in this repository:

### **1. `First project java` (Basic Java Console Application)**

* **Description:** This project (`First project java`) serves as an introductory demonstration of fundamental Java concepts in a simple command-line environment. It covers essential elements such as variable declaration (e.g., `byte`, `int`, `String`), the use of the `Random` class for generating numbers, basic conditional logic (`if-else` statements), and effective utilization of `ArrayList` for managing collections of data. The output is enhanced with ANSI color codes for improved readability in compatible terminals. The project also showcases how to implement pauses in program execution using `Thread.sleep()`, incorporating basic exception handling for `InterruptedException`.
* **Main File:** `First project java/[YourMainClassName].java` (e.g., `First project java/ConsoleDemo.java` or `First project java/Main.java` if you keep the original name and run it only from its directory)
* **Learning Focus:** Basic syntax, primitive data types, control flow, collections (`ArrayList`), console I/O, `Random` class, `Thread.sleep`, and fundamental exception handling.

### **2. `Project 1 - Game` (Java Swing GUI Application - Monkey Simulator)**

* **Description:** This project (`Project 1 - Game`) is a simple Graphical User Interface (GUI) application developed using Java Swing, designed as a "Monkey Simulator." It creates a window that displays a dynamic image and real-time text output. The core functionality involves simulating a "monkey" entity performing a sequence of random actions such as eating, sleeping, or making a voice, with varying pauses between actions. It effectively demonstrates the use of key Swing components like `JFrame` (the main window), `JLabel` (for displaying text and images), and `ImageIcon` (for loading images). The application utilizes `BorderLayout` for basic component arrangement and employs a `while(true)` loop within a separate thread (implicitly or explicitly, depending on `Monkey` implementation) to drive the continuous simulation.
* **Main File:** `Project 1 - Game/[YourMainClassName].java` (e.g., `Project 1 - Game/MonkeySimulator.java` or `Project 1 - Game/Main.java` if you keep the original name and run it only from its directory)
* **Dependencies:** This project requires a separate `Monkey` class (expected to be located at `Project 1 - Game/Monkey.java`) which encapsulates the monkey's behavior (e.g., `eat()`, `sleep()`, `Voice()`). It also relies on an image file (`MonkeysImage.jpg`) expected to be located in `Project 1 - Game/Image/`.
* **Learning Focus:** GUI development with Java Swing, `JFrame`, `JLabel`, `ImageIcon`, basic layout managers (`BorderLayout`), `Random` class for simulation logic, object-oriented design (using `Monkey` class as a model), and implementing simple simulation loops.

## 🛠️ Technologies Used

* **Language:** Java (Specify your JDK version, e.g., Java 17)
* **IDE:** [e.g., IntelliJ IDEA, Eclipse, Visual Studio Code]
* **Version Control:** Git, GitHub

## 🚀 How to Compile and Run

To compile and run any of these Java exercises, you will need a Java Development Kit (JDK) installed on your system.

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/JonatanKovalik/Java-LearningExercises.git](https://github.com/JonatanKovalik/Java-LearningExercises.git)
    ```
2.  **Navigate into the cloned repository's root directory:**
    ```bash
    cd Java-LearningExercises
    ```
3.  **Navigate to the specific project's directory you wish to run:**
    ```bash
    cd "[ProjectName]"
    ```
    * **For `First project java`:** `cd "First project java"` (השתמש בגרשיים בגלל רווח בשם)
    * **For `Project 1 - Game`:** `cd "Project 1 - Game"` (השתמש בגרשיים בגלל רווח בשם)

4.  **Compile the Java source files:**
    ```bash
    javac [YourMainClass].java [OtherDependentClasses].java
    ```
    * **Example for `First project java`:** `javac [YourMainClass].java` (e.g., `javac Main.java` if you keep the name, or `javac ConsoleDemo.java` if you change it)
    * **Example for `Project 1 - Game`:** `javac [YourMainClass].java Monkey.java` (e.g., `javac Main.java Monkey.java` or `javac MonkeySimulator.java Monkey.java`)

5.  **Run the compiled program:**
    ```bash
    java [YourMainClass]
    ```
    * **Example for `First project java`:** `java [YourMainClass]` (e.g., `java Main` or `java ConsoleDemo`)
    * **Example for `Project 1 - Game`:** `java [YourMainClass]` (e.g., `java Main` or `java MonkeySimulator`)

    *(**Note:** If you are using an Integrated Development Environment (IDE) like IntelliJ IDEA or Eclipse, you can typically import the entire `Java-LearningExercises` repository as a project and then run individual modules or main classes directly from within the IDE's interface, simplifying the compilation and execution steps.)*

## 🧠 Learning & Development

These exercises have been crucial in building my proficiency in Java. I've focused on understanding [mention specific learning, e.g., advanced object-oriented design, exception handling best practices, the Collections Framework, file I/O operations, basic multithreading concepts]. Each project provided a valuable opportunity to apply theoretical knowledge to practical coding challenges, refine my problem-solving skills, and improve my debugging capabilities.

## 📄 License

This project is open-sourced under the MIT License. See the [LICENSE](LICENSE) file for more details.

## 📧 Contact

Feel free to reach out if you have any questions, feedback, or collaboration ideas:
* Email: jonatan.kovalik@gmail.com
