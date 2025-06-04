# File-handling-java

Company - Codtech IT Solutions
Name - Tanay Daata
Inter Id - CT04DL566
Domain - Java Programming
Duration - 4 Weeks
Mentor -  Mr. Muzammil Ahmed

# Java File Operations – Read, Write, Modify Text Files

## 📄 Project Overview

This project showcases how to perform essential file operations—**reading**, **writing**, and **modifying** text files using Java. It is aimed at beginners and intermediate Java programmers who want to understand and implement file handling in real-world applications. File handling is a fundamental part of any programming language and is widely used in a variety of applications, including data logging, file analysis, configuration management, and more.

The deliverable for this project is a fully functional **Java script** that demonstrates all the required file operations along with **clear documentation** for ease of understanding, learning, and extension.


## ✅ Features

* **Read from a file**: Opens a `.txt` file and displays its content.
* **Write to a file**: Creates or overwrites a `.txt` file with user-supplied content.
* **Append to a file**: Adds content to an existing file without removing old content.
* **Modify specific content**: Updates specific lines or words within the file.
* **User-friendly structure**: Modular functions for better readability and maintenance.
* **Clear documentation**: Every method is explained using comments for clarity.

## 🔧 Technologies Used

* **Java SE 8+**
* **Java I/O Package (`java.io`)**
* **BufferedReader**, **FileReader**, **FileWriter**
* **Exception handling with `try-catch-finally` blocks**

---

## 🚀 How to Run

1. **Clone the Repository**

   ```bash
   git clone https://github.com/yourusername/JavaFileOperations.git
   cd JavaFileOperations
   ```

2. **Compile the Java File**

   ```bash
   javac src/FileHandler.java
   ```

3. **Run the Program**

   ```bash
   java src.FileHandler
   ```

4. **Follow On-screen Prompts**

   * Choose from options like Read, Write, Modify.
   * Enter the file path or use the sample provided.

---

## 🧠 Use Cases

* **Learning Project**: Ideal for students learning Java file I/O.
* **Log Creation**: Modify and update logs or record application data.
* **Data Processing**: Read raw data from text files, process it, and save results.
* **Configuration Editors**: Build on this to create basic text-based configuration editors.

---

## 📌 Code Snippet Example

```java
BufferedReader reader = new BufferedReader(new FileReader("sample.txt"));
String line;
while ((line = reader.readLine()) != null) {
    System.out.println(line);
}
reader.close();


## 📘 Documentation

Each method in the script is clearly commented to explain:

* Purpose of the method
* Input/Output behavior
* Edge cases handled (e.g., file not found, empty files, etc.)

There is also a helpful menu-based system in the console interface that guides users through operations with meaningful messages and prompts.


## ⚠️ Error Handling

* Handles common errors like:

  * File not found
  * Empty files
  * Permission issues
* Ensures all readers and writers are properly closed using `finally` or try-with-resources



---

