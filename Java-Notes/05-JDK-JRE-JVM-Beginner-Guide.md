# JDK, JRE, and JVM: A Beginner's Guide

Welcome to another guide in my Java Learning space! Today, we will explore three foundational concepts that every Java developer must understand: **JDK**, **JRE**, and **JVM**.

---
## 1. Introduction to JDK, JRE and JVM💻:

⁑JDK, JRE, and JVM are important parts of the Java development and execution process. Each has a different role in creating and running Java programs.

⁑JVM-It is the execution engine of Java.

⁑JRE-The software package that provides an environment to run java programs.

⁑JDK-The complete software development environment used to develop and run java applications.

## 2. What is JDK📌?

⁑JDK stands for Java Development Kit.

⁑It provides the tools required to develop, compile, and run Java programs. It includes the Java compiler and other development tools.

⁑JDK used to build and compile the program.

⁑Role: It contains everything needed for java development,including compilers,debuggers, and the runtime environment.

⁑Key tool: javac (java compiler) which converts .java files to .class files.

## 3. What is JRE📌?

⁑JRE stands for Java Runtime Environment.

⁑It provides the environment and libraries needed to run Java applications. In the traditional Java setup, JRE includes the JVM.

⁑Role: It contains the JVM along with core class libraries (like java.util,java.io) and supporting files.

## 4. What is JVM📌?

⁑JVM stands for Java Virtual Machine.

⁑It executes Java bytecode and helps Java programs run on different operating systems when a compatible JVM is available.

⁑Role: It reads the compiled bytecode (.class file) and translates it into machine code so the operating system can execute it.

## 5. Difference Between JDK, JRE and JVM📝:
   
   JDK	                           JRE	                             JVM
⁑Develops Java programs	⁑Provides the runtime environment  	⁑Executes bytecode
⁑Includes development 	⁑Includes runtime libraries         ⁑Runs compiled Java code
  tools                  and traditionally the JVM	
⁑Mainly for developers	⁑For running Java applications	    ⁑Acts as the execution engine

## 6.Java Source Code and Bytecode💭:

->Source Code: The Java code written by a programmer. It is saved with the .java extension.
Example: HelloJava.java

->Bytecode: The intermediate code produced by the Java compiler. It is saved with the .class extension.
Example: HelloJava.class

## 7. How Java Program Executes🤔:

->A Java program follows these steps:
⁑Write the Java source code.
⁑Compile the code using the Java compiler
⁑Generate the bytecode.
⁑Execute the bytecode using the JVM.
⁑Display the output.

## 8. Java Compilation Process📋:

First, create a file named HelloJava.java.

class HelloJava {

         public static void main(String[] args) {

            System.out.println("Welcome to Java!"); 

       }

 }

Compile the program:
      javac HelloJava.java
      This generates HelloJava.class if compilation succeeds.

Run the program:
     java HelloJava
     
Output:
    Welcome to Java!
    
The javac command compiles the source code, and the java command starts the program using the JVM.

## 9. Simple Architecture Diagram📊:

Java Source Code (.java)
          |
          v
Java Compiler (javac)
          |
          v
   Bytecode (.class)
          |
          v
         JVM
          |
          v
  Program Execution
          |
          v
        Output
---

**Note:** Understanding these three concepts is essential before entering into Java Programming!   


                                                    
                                             
