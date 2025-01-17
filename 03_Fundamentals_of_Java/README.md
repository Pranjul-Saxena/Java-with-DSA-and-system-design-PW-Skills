# Introduction to Programming

Making a set of instructions that instruct a computer how to carry out a task is
the process of programming. There are numerous computer programming
languages available for use in programming.

# Category of Programming Languages:

## Machine Level Language :- Machine-level language is the lowest-level programming language, directly understood by a computer's CPU without translation.
  ### Key Characteristics
  - **Binary Format**: Instructions are represented in binary (0s and 1s).
  - **Hardware-Specific**: Each CPU has its unique instruction set.
  - **No Abstraction**: Directly manipulates hardware (e.g., registers, memory, I/O devices).
  - **Efficient but Complex**: High execution speed but challenging to write, read, and debug.
  ### Advantages
  - **Fast Execution**: Direct communication with the CPU ensures minimal overhead.
  - **Precise Control**: Allows fine-grained control over hardware.
  
  ### Disadvantages
  - **Difficult to Program**: Writing code in binary is error-prone and time-consuming.
  - **Not Portable**: Code is specific to the CPU architecture.
  - **Hard to Debug and Maintain**: Lack of abstraction makes troubleshooting challenging.

## Assembly language :- Assembly language is a low-level programming language that provides a symbolic representation of machine code, making it easier to program than machine-level language.

### Key Characteristics
- **Symbolic Instructions**: Uses mnemonics (e.g., `MOV`, `ADD`) instead of binary code.
- **Hardware-Specific**: Tied to a specific CPU architecture.
- **Low-Level**: Provides direct hardware control but is slightly more abstract than machine code.

### Advantages
- **Readable**: Easier to understand and write than machine code.
- **Efficient**: Offers control over hardware with minimal overhead.
- **Fast Execution**: Translated directly into machine code by an assembler.

### Disadvantages
- **Complex**: Still challenging to write compared to high-level languages.
- **Not Portable**: Code written for one processor cannot run on another without modification.
- **Difficult Debugging**: Errors can be hard to trace and fix.

### Use Cases
- System programming (e.g., operating systems, device drivers).
- Embedded systems.
- Performance optimization in critical applications.

## High-level languages :- High-level programming languages are designed to be user-friendly and abstract away the complexities of hardware, making them easier to learn and use.

### Key Characteristics
- **Human-Readable**: Uses natural language-like syntax (e.g., `if`, `while`, `print`).
- **Abstracted from Hardware**: Does not require direct interaction with the CPU or memory.
- **Portable**: Code can run on multiple platforms with little or no modification.

### Advantages
- **Ease of Use**: Simplifies coding, debugging, and maintenance.
- **Productivity**: Faster development time compared to low-level languages.
- **Portability**: Independent of hardware and operating systems.
- **Rich Libraries**: Provides extensive built-in libraries and frameworks for rapid development.

### Disadvantages
- **Less Control**: Limited access to low-level hardware features.
- **Performance Overhead**: May be slower than low-level languages due to abstraction.
- **Dependency**: Requires compilers or interpreters to translate code into machine language.

### Examples
- **General Purpose**: Python, Java, C++, PHP.
- **Web Development**: JavaScript, Ruby.
- **Scientific Computing**: MATLAB, R.

### Use Cases
- Application development (web, mobile, desktop).
- Scientific research and data analysis.
- Game development.
- Artificial intelligence and machine learning.


# Why do we need Programming?

● Not just for academics, but for the real world as well, all programming is done.

● Due to programmes developed by computer programming, you can conduct
online banking and purchase your ticket while travelling by train or aeroplane.
It's true that your washing machine has a few different kinds of computer
programmes. Programming makes it possible for all of these things and many
more.

# Introduction to Java

Writing, compiling, and debugging programmes are simple with Java since it is a
class-based, object-oriented programming language. It facilitates the
development of reusable code and modular programmes, which *James Gosling*
invented in *1995* and eventually sold to Oracle Corporation.

● Java is an object-oriented programming language developed by Sun Microsystems, and it was released in
1995h
● James Gosling initially developed Java in Sun Microsystems (which was later merged with Oracle
Corporation)h
● Java is a set of features of C and C++. It has obtained its format from C, and OOP features from C++h
● Java programs are platform independent which means they can be run on any operating system with any
processor as long as the Java interpreter is available on that systemh
● Java code that runs on one platform does not need to be recompiled to run on another platformi it's called
write once, run anywhere(WORA)h
● Java Virtual Machine (JVM) executes Java code, but it has been written in platform-specific languages
such as C/C++/ASM, etc. JVM is not written in Java and hence cannot be platform independent, and Java
interpreter is a part of JVMh


# Basic features of Java

● Simple
● Object-Oriented
● Portable
● Platform independent
● Robust
● Distributed
● Dynamic

![image](https://github.com/user-attachments/assets/9fafd897-761b-4a51-9f85-864e3f265f46).

![image](https://github.com/user-attachments/assets/672ba084-7d7a-43aa-91e6-989fa2c4a491)



# Main method

![image](https://github.com/user-attachments/assets/943cc510-37f6-469c-b0f1-c6d7dc46e2db)
![image](https://github.com/user-attachments/assets/2e4d3dce-e2fd-43b1-8eac-89f7d190e61b)


public static void main(String[] args):


The main () is the starting point for JVM to start execution of a Java program. Without the main () method, JVM
will not execute the program. The syntax of the main () method is: public: It is an access specifier. We should
use a public keyword before the main () method so that JVM can identify the execution point of the program.

public: An access specifier, that is. Before calling the main() method, we need to use the public keyword to let
the JVM know where the programme is actually being executed. Before the main() method, if we use private,
protected, and default, the JVM won't be able to see it.

static: You can make a method static by using the keyword static. We should call the main() method without
creating an object. Static methods are the method which is invoked without creating the objects, so we do not
need any object to call the main() method.

void: In Java, every method has the return type. Void keyword acknowledges the compiler that the main()
method does not return any value.

main(): It is a default signature which is predefined in the JVM. It is called by JVM to execute a program line by
line and end the execution after completion of this method. We can also overload the main() method.

String args[]: The main() method also accepts some data from the user. It accepts a group of strings, which is
called a string array. It is used to hold the command line arguments in the form of string values.

main(String args[])
Here, agrs[] is the array name, and it is of String type. It means that it can store a group of strings. Remember,
this array can also store a group of numbers but in the form of string only. Values passed to the main() method
are called arguments. These arguments are stored into an args[] array, so the name args[] is generally used
for it.
![image](https://github.com/user-attachments/assets/8f9a8bd9-8c8c-4d00-b070-d2be44c432e2)
![image](https://github.com/user-attachments/assets/ecff0dd8-d759-4cad-8d7e-a6859d424f5d)
![image](https://github.com/user-attachments/assets/eb7f9be2-068f-4e40-8a97-f9f54d26ba14)




# Classes and Objects (Basics)

Java is an object-oriented programming language.

![image](https://github.com/user-attachments/assets/f5d1ae76-d4c9-44a1-89e8-b905664cd1b5)
![image](https://github.com/user-attachments/assets/8877d7ce-7f9d-4d3a-a554-de7e305481b8)


The classes and objects in Java, along with their characteristics and methods, are
the foundation of everything. For instance, an automobile is an object in the actual
world. The car contains characteristics like weight and colour, as well as functions
like drive and brake.

Class:
A class is a collection of objects that have similar traits, behaviours, and attributes.

Object:
An object is an entity with state and behaviour.




# Statically typed vs Dynamically typed

Statically typed: Programming languages are referred to as "Static typed" if the
memory of the variable is provided at the time of compilation.

For instance, C, C++, and Java

Dynamically typed: Programming languages are said to as "dynamically typed"
if the memory for the variable is provided at the time of execution.

Like Python, PHP, and JavaScript



# Variables

● A variable is the name of a memory-allocated reserved area. It may be thought of as
the name of a memory location, in other words.

● While the Java programme is running, the value is held in a container.

● To identify the storage location, each variable needs to have a special name.

● A data type is assigned to a variable (we will learn about it after this topic).




# Syntax for Declaring a Variable:

Type variable_name = value;

The name of a variable is variable_name. The variable can be initialised by
supplying an equal sign and a value (initialization i.e. assigning an initial value, is
optional). However, a Java uninitialized local variable is never given a default
value by the compiler.



# Naming Conventions for variables in Java

Variable names should not begin with a number.For example
int 2 var; // 2 var is an invalid variable.

White Spaces are not permitted in variable names. For example,
int cricket score; // invalid variables.
There is a gap/whitespace between cricket and score.

A java keyword (reserved word) cannot be used as a variable name. For
example, int float; is an invalid expression as float is a predefined
keyword(we will learn about them) in java.




# Naming Conventions for variables in Java

As per the latest coding practices, for variable names with more than one word
the first word has all lowercase letters and the first letter of subsequent words are
capitalised. For example, cricketScore, codePracticeProgram etc. This type of
format is called camelcase.

While creating variables, it's preferable to give them meaningful names like-
‘age’, ‘earning’, ‘value’ etc. for instance, makes much more sense than variable
names like a, e, and v.

We use all lowercase letters when creating a one-word variable name. It's
preferable(and in practice) to use physics rather than PHYSICS or pHYSICS.




# Data Types:

There are two types of data types in Java:

1. Primitive data types: The primitive data types include boolean, char, byte,
short, int, long, float and double.

2. Non-primitive data types: The non-primitive data types include classes,
Strings, Interfaces, and Arrays.




# Primitive data types

A primitive type is predefined by the language and is named by a reserved keyword.
1. boolean
2. byte
3. short
4. int
5. long
6. double
7. float
8. char




Once we have mastered the primitives and are well informed in the Java programming
principles, we will discuss the slightly more complex non-primitive data types.


# Identifiers

An identifier is a name given to a package, class, interface, method, or variable. All identifiers
must have different names.

In Java, there are a few points to remember while dealing with identifiers :
Rule 1 − All identifiers should begin with a letter (A to Z or a to z), $ and _ and must be
unique.
Rule 2 − After the first character/letter, identifiers can have any combination of characters.
Rule 3 − A keyword cannot be used as an identifier.
Rule 4 − The identifiers are case-sensitive.
Rule 5 – Whitespaces are not permitted.
Examples of legal identifiers: rank, $name, _rate, __2_mark.
Examples of illegal identifiers: 102pqr, -name.

