 # Java Basics – Definitions, Syntax, and Examples

## 1. What is Java?

**Definition:**
Java is a high-level, object-oriented, platform-independent programming language developed by **James Gosling** at **Sun Microsystems** in 1995.

### Features of Java

* Simple
* Object-Oriented
* Platform Independent
* Secure
* Robust
* Multithreaded
* Portable

### Example:

```java
public class HelloWorld {
    public static void main(String[] args) {
        System.out.println("Hello, Java!");
    }
}
```

---

# 2. Structure of a Java Program

### Definition

Every Java program consists of:

* Class
* Main Method
* Statements

### Syntax

```java
public class ClassName {
    public static void main(String[] args) {
        // statements
    }
}
```

### Example

```java
public class Test {
    public static void main(String[] args) {
        System.out.println("Welcome to Java");
    }
}
```

---

# 3. Variables

### Definition

A variable is a memory location used to store data.

### Syntax

```java
datatype variableName = value;
```

### Example

```java
int age = 20;
String name = "Suresh";
double salary = 25000.50;
```

---

# 4. Data Types

### Definition

Data types specify the type of data that a variable can store.

## A) Primitive Data Types

| Data Type | Size    | Example           |
| --------- | ------- | ----------------- |
| byte      | 1 byte  | byte a = 10;      |
| short     | 2 bytes | short b = 100;    |
| int       | 4 bytes | int c = 1000;     |
| long      | 8 bytes | long d = 100000L; |
| float     | 4 bytes | float e = 12.5f;  |
| double    | 8 bytes | double f = 25.75; |
| char      | 2 bytes | char g = 'A';     |
| boolean   | 1 bit   | boolean h = true; |

### Example

```java
int marks = 95;
char grade = 'A';
boolean result = true;
```

---

# 5. Keywords

### Definition

Keywords are reserved words that have predefined meanings in Java.

### Examples

```java
class
public
static
void
if
else
while
for
return
```

### Example

```java
public class Demo {
}
```

---

# 6. Identifiers

### Definition

Identifiers are names given to variables, methods, classes, and objects.

### Rules

* Cannot start with a number.
* Cannot contain spaces.
* Cannot use keywords.
* Can contain letters, digits, _ and $.

### Example

```java
int studentAge;
String studentName;
```

---

# 7. Constants

### Definition

A constant is a variable whose value cannot be changed.

### Syntax

```java
final datatype CONSTANT_NAME = value;
```

### Example

```java
final double PI = 3.14159;
```

---

# 8. Operators

### Definition

Operators are symbols used to perform operations.

### Syntax

```java
operand operator operand
```

### Example

```java
int sum = 10 + 20;
```

### Types

* Arithmetic
* Relational
* Logical
* Assignment
* Bitwise
* Increment/Decrement
* Ternary

---

# 9. Input and Output

## Output

### Definition

Used to display data on the screen.

### Syntax

```java
System.out.println("Message");
```

### Example

```java
System.out.println("Hello Java");
```

---

## Input

### Definition

Used to accept data from the user.

### Syntax

```java
Scanner sc = new Scanner(System.in);
datatype variable = sc.nextDatatype();
```

### Example

```java
import java.util.Scanner;

public class InputDemo {
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);

        System.out.print("Enter Age: ");
        int age = sc.nextInt();

        System.out.println("Age = " + age);
    }
}
```

---

# 10. Conditional Statements

## if Statement

### Definition

Executes a block if a condition is true.

### Syntax

```java
if(condition) {
    statements;
}
```

### Example

```java
if(age >= 18) {
    System.out.println("Eligible");
}
```

---

## if-else Statement

### Syntax

```java
if(condition) {
    statements;
}
else {
    statements;
}
```

### Example

```java
if(age >= 18) {
    System.out.println("Major");
}
else {
    System.out.println("Minor");
}
```

---

## else-if Ladder

### Syntax

```java
if(condition1) {
}
else if(condition2) {
}
else {
}
```

### Example

```java
int marks = 85;

if(marks >= 90)
    System.out.println("A");
else if(marks >= 75)
    System.out.println("B");
else
    System.out.println("C");
```

---

# 11. Switch Statement

### Definition

Selects one block among many.

### Syntax

```java
switch(expression) {
    case value:
        statements;
        break;

    default:
        statements;
}
```

### Example

```java
int day = 2;

switch(day) {
    case 1:
        System.out.println("Monday");
        break;

    case 2:
        System.out.println("Tuesday");
        break;

    default:
        System.out.println("Invalid");
}
```

---

# 12. Loops

## for Loop

### Definition

Used when the number of iterations is known.

### Syntax

```java
for(initialization; condition; increment) {
    statements;
}
```

### Example

```java
for(int i = 1; i <= 5; i++) {
    System.out.println(i);
}
```

---

## while Loop

### Definition

Executes while the condition is true.

### Syntax

```java
while(condition) {
    statements;
}
```

### Example

```java
int i = 1;

while(i <= 5) {
    System.out.println(i);
    i++;
}
```

---

## do-while Loop

### Definition

Executes at least once.

### Syntax

```java
do {
    statements;
} while(condition);
```

### Example

```java
int i = 1;

do {
    System.out.println(i);
    i++;
} while(i <= 5);
```

---

# 13. Arrays

### Definition

An array stores multiple values of the same data type.

### Syntax

```java
datatype[] arrayName = new datatype[size];
```

### Example

```java
int[] numbers = {10,20,30,40,50};

for(int i = 0; i < numbers.length; i++) {
    System.out.println(numbers[i]);
}
```

---

# 14. Methods

### Definition

A method is a block of code that performs a specific task.

### Syntax

```java
returnType methodName(parameters) {
    statements;
}
```

### Example

```java
public static int add(int a, int b) {
    return a + b;
}
```

Usage:

```java
int result = add(10,20);
System.out.println(result);
```

---

# 15. Object and Class

## Class

### Definition

A class is a blueprint for creating objects.

### Syntax

```java
class ClassName {
    variables;
    methods;
}
```

---

## Object

### Definition

An object is an instance of a class.

### Syntax

```java
ClassName objectName = new ClassName();
```

### Example

```java
class Student {
    String name = "Suresh";
}

public class Test {
    public static void main(String[] args) {
        Student s = new Student();
        System.out.println(s.name);
    }
}
```

---

# 16. Constructor

### Definition

A constructor initializes an object and has the same name as the class.

### Syntax

```java
ClassName() {
}
```

### Example

```java
class Student {
    Student() {
        System.out.println("Constructor Called");
    }
}
```

---

# 17. Inheritance

### Definition

One class acquires the properties of another class.

### Syntax

```java
class Child extends Parent {
}
```

### Example

```java
class Animal {
    void eat() {
        System.out.println("Eating");
    }
}

class Dog extends Animal {
}
```

---

# 18. Exception Handling

### Definition

Exception handling manages runtime errors.

### Syntax

```java
try {
}
catch(Exception e) {
}
```

### Example

```java
try {
    int x = 10 / 0;
}
catch(Exception e) {
    System.out.println("Error Occurred");
}
```

---

# 19. Packages

### Definition

A package is a collection of related classes and interfaces.

### Syntax

```java
package packageName;
```

### Example

```java
package mypackage;
```

---

# 20. Java Memory Areas

### Stack Memory

Stores:

* Local variables
* Method calls

### Heap Memory

Stores:

* Objects
* Arrays

### Example

```java
Student s = new Student();
```

Here:

* `s` → Stack Memory
* Object → Heap Memory

---

## Quick Revision

1. Java Program Structure
2. Variables
3. Data Types
4. Keywords
5. Identifiers
6. Constants
7. Operators
8. Input/Output
9. Conditional Statements
10. Loops
11. Arrays
12. Methods
13. Classes and Objects
14. Constructors
15. Inheritance
16. Exception Handling
17. Packages
18. Memory Management

These are the core Java concepts typically asked in interviews, viva examinations, and university exams.
