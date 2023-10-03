# java-getting-started
Welcome to our Java programming repository! Here, you'll find everything you need to start coding in Java. 
## 📚Prerequisites
![Windows](https://img.shields.io/badge/Windows-0078D6?style=for-the-badge&logo=windows&logoColor=white)
## Installing Java Development Kit (JDK) on Windows
1. **Download JDK**: Visit the official Oracle website to download the latest version of JDK for Windows.

   - Oracle JDK: [Download Oracle JDK](https://www.oracle.com/java/technologies/javase-downloads.html)

2. **Install JDK**: Run the downloaded installer and follow the installation instructions. Ensure that the installation directory is added to your system's PATH environment variable during installation.

3. **Verify Installation**: Open a Command Prompt and run the following command to verify that Java is installed:
   ```batch
   java -version
   ```
## Java Bytecode 

Java code is compiled into bytecode, which is a platform-independent format. This bytecode can be executed on any platform with a compatible Java Virtual Machine (JVM). The use of bytecode makes Java applications cross-platform.

Keep in mind that when distributing your Java application, you only need to distribute the JAR file and not the source code. Users can run your application as long as they have the appropriate JVM installed.
   * This image explains the process of compilation

<p align="center">
  <img src="https://github.com/YassinMk/java-getting-started/assets/122708120/abd0488c-e8f8-413b-8403-dbc19bee8a3e" alt="compilation" height="500" width="500"/>
</p>

## How to compile Java Code in CLI
1. **Write Your Java Code:** Create your Java source code files with a `.java` extension using a text editor or an Integrated Development Environment (IDE) like [Eclipse](https://www.eclipse.org/) or [IntelliJ IDEA](https://www.jetbrains.com/idea/). For example, let's say you have a file named `MyProgram.java`.

2. **Open a Terminal/Command Prompt:** Open a terminal or command prompt window on your computer.

3. **Navigate to the Directory:** Use the `cd` command to navigate to the directory where your Java source file is located. For example:
   ```bash
   cd /path/to/your/java/project
   ```
4. **Compile the Java code:** To compile your Java code, use the javac command followed by the name of your Java source file (without the .java extension).
   For example:
      ```bash
      javac MyProgram.java
      ```
   This command will generate a compiled bytecode file named MyProgram.class in the same directory.
5. **Run the Compiled Program:** After successfully compiling your code, you can run the program using the java command, followed by the class name (without the .class           extension).
   For example:
   ```bash
   java MyProgram
   ```
## JAR files : 
JAR stands for Java Archive and refers to the packaged output from building/compiling a Java application – it ends with the .jar extension. A JAR file is essentially a ZIP file that contains compiled Java class files and other metadata, including a manifest file that specifies information about the package

### Creating JAR Files in CLI
1. **Navigate to the directory**: Make sure you are in the directory containing your compiled **.class** files.
   
2. **Create the JAR File**: Use the jar command to create a JAR file. For example, to create a JAR file named MyProgram.jar:
   ```bash
   jar cvf MyProgram.jar *.class
   ```
3.**Run the JAR File**: You can run your application from the JAR file using the java command:
 ```bash
  java -jar MyProgram.jar
  ```
## Creating your own program JAVA with IDE :

[![Watch the tutorial](https://github.com/YassinMk/java-getting-started/assets/122708120/7c626cf9-ec3e-42a3-8ece-b21df7f40cf1)](https://www.youtube.com/watch?v=45hB5TkFMnU&ab_channel=ProgrammingKnowledge2)

---
Click on the image above or [here](https://www.youtube.com/watch?v=45hB5TkFMnU&ab_channel=ProgrammingKnowledge2) to watch the video and follow along as you create your Java programs.




