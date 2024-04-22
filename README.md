# Java-Notes
Java was originally developed by Sun microsystems which was initiated by James Gosling and released in 1995.
It is currently mantained by Oracle Coporatiom.
It was designed to be platform independent meaning Java programs can run on any device that has a Java Virtual Machine installed.

Basic syntax rules in Java

Java programs are organized into classes and every program must atleast have one class.
Statements in Java are ended with a semicolon
Java  is case sensitive, myVariable and myvariable are two different things.

Variables and Data types

In Java Variables are used to store and manipulate data
Each variable has a specific data type that determines the kind of data it can hold

Here are some common data types in java:

int: used to store whole numbers 
double: used to store decimal numbers
boolean: used to store true or false values
strings: used to store sequence of characters

Control Flow

Control flow refers to the order in which statements in a program are executed.
Some control flow statements include:

If statements: used to execute a block of code only if the a certain condition is true
For loop: used to execute a block of code repeatedly for a number of times
while loop: used to execute a block of code repeatedly as long as a certain condition is true

Object-Oriented Programming(OOP)

Java is an object-oriented progr amming language.
Which means it relies heavily on the concept of objects and classes.

Java supports the following principles of OOP

Encapsulation: the act of encapsuling data and methods within a class.
Inheritance: the ability to create new classes based on the existing ones.
Polymophism: the ability to use a single interfase to represent different objects.

Exeption Handling 

Exeption Handling are unexpected events that can occur during the execution of a program.
The try-catch-finally blocks are used to handle exeptions in Java

File Input and Output

File input and output (I/O) operators are useful when dealing with large sets of data
Or when retrieving and storing information from external sources.
Some common classes used for I/O operators in Java include File, Scanner and PrintWriter

Variables and datatypes

Variables are used to store and manipulate data.
A variable is like a container that that holds a value, which can be a number, text or any other type of data.
Before using a variable, it needs to be declared with a specific data type.

Data types

Java has eight Primitive data types which are:

Byte: is a data type that can range from -128 to 127.
It is used to store or save memory in large arrays where the memory savings are significant.

Short: s short data type can range from -32,768 to 32,767. 
It is used mainly to save memory in arrays or dealing with graphical data.

int: can store whole numbers ranging from -2,147,648,648 to 2,1,147,483,647.
It is the default type for whole numbers in Java.

long: can store larger data whole numbers ranging from -9,223,372,036,854,777,808 to 9,223,372,036,854,777,807.
It is often used when dealing with very large numbers.

Float: It is used to store fractional numbers ranging from 3.4e^-038 to 3.4e^+038.
It is mostly used for scientific calculations and situations that require large range of values.

Double: It can store fractional numbers with a larger range and precision than float
It can hold values from 1.7e^-308 to 1.7e^+308 and is the default choice for decimal values.

Char: is a data type that represents a single character
It can store any unicode character.

Boolean: represents true or false values.
It is commonly used for conditional statements and loops

Reference Data Types

These data types are created using predefined classes or user defined classes.
Some commonly used reference data types include the following:

String: which is a sequence of characters and is usedto store and manipulate text.
Arrays: is an unodred collection of elements of the same data type.It allows storing multiple values under a single variable name.
Classes: they define object's properties and behavior.

Declaring and Initializing Variaables

To use variable, it must be declared with a specific datatype.
Declaring a variable involves specifying the variables name name and datatype.
For example, you can use the following syntax to declare interger variable naamed count:
int count;

Variables can also be initialized at the time of declaration by assigning them a value.
For example, to declare and initialize an integer variable named score with a value 100:
int score= 100;

Variables can be assigned new values using the assignment operator(=) 
For example score= 85;

Variable naming Rules and conventins
The following Rules must be followed when naming variabesin Java:

Variable names must start with a letter, dollar sign or an undersore.
Variable names can consist of letters, digits, dollar signs and underscores.
Variable names are case sensitive.
Variable names should be descriptive but not excessively long.
Use a camel case for multi-word variable, starting with a lowercase letter(studentName, totalScore).

Types of Converions 

Java provudes automatic type conversion, also known as type casting to handle different data types interactions.
Type casting can occur in the following two ways:

Implicit Casting: occurs when a smaller data type is assigned to a larger data type.
For example:
int num=100
double decimal=num;

Explicit Casting: occurs when a larger data type is assigned to a smaller data type.
It requires manual casting, as it may result in data loss or overflow.
for example:
double decimal=3.14;
int num=(int) decimal;
