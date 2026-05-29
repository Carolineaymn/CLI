# Java Terminal Simulator

##  Overview
A custom, fully functional command-line interpreter built in Java. It simulates standard Unix/Linux terminal operations, allowing users to navigate the file system, manipulate files and directories, compress data, and redirect output streams.

##  Features
* **File System Navigation:** Navigate and view directories using `pwd`, `cd`, and `ls`.
* **File Manipulation:** Create, copy, read, and delete files or directories using `touch`, `cp` (with recursive `-r` support), `cat`, `mkdir`, `rmdir`, and `rm`.
* **Archiving:** Compress and extract files using `zip` and `unzip` commands, including recursive directory support and custom destination routing.
* **Text Processing:** Count lines, words, and characters with `wc`, or print text to the console using `echo`.
* **Output Redirection:** Route the output of any command directly into text files using `>` (overwrite) or `>>` (append).

##  Tech Stack
* **Language:** Java
* **Libraries:** Standard Java I/O and Utilities (`java.io`, `java.nio`, `java.util.zip`)

##  Installation & Setup
1. Clone the repository to your local machine.
2. Ensure you have the Java Development Kit (JDK) installed.
3. Navigate to the folder containing the source code.
4. Compile the application:
```bash
   javac Terminal.java
