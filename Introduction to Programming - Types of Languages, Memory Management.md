1️⃣ Why Programming Languages Exist
===================================

### 🔹 Core Idea

-   Computers understand only **binary (0s and 1s)**.

-   Writing instructions directly in binary is very difficult.

-   So we use **programming languages** like Java, Python, C++.

-   These languages are human-readable.

-   Internally, the computer converts them into machine code.

### 🔹 Example

If you want to:

-   Print "Good Morning"

-   Add two numbers

-   Store student details

You write code → It gets compiled/interpreted → Converted to machine code → Executed.

* * * * *

2️⃣ What Is a Programming Language?
===================================

A programming language allows us to:

-   Write instructions

-   Give commands to CPU

-   Take input

-   Process data

-   Produce output

### Example Programs Mentioned

-   Program to print table of 2

-   Program to store student data

-   Program to print current date

-   Program to print "Hi, how are you?"

* * * * *

3️⃣ Types of Programming Languages (By Programming Paradigm)
============================================================

The video explains that languages can follow multiple paradigms.\
A language is not restricted to just one type.

* * * * *

🔹 A. Procedural Programming
----------------------------

### 📌 Definition

Program is written as a sequence of steps.

It follows:

1.  Input

2.  Process

3.  Output

### Example: Add Two Numbers

Step 1: Take first number\
Step 2: Take second number\
Step 3: Add them\
Step 4: Print result

You cannot add before taking both numbers.

### Key Points:

-   Uses statements

-   Uses loops

-   Uses functions

-   Uses conditional logic

### Languages that support this:

-   Java

-   Python

-   C++

-   C

All major languages support procedural style.

* * * * *

🔹 B. Functional Programming
----------------------------

### 📌 Definition

Program is written using **pure functions**.

### What is a Function?

A reusable block of code.

Instead of writing same logic multiple times, write it once and reuse.

* * * * *

### Pure Functions

-   Do not modify original variables.

-   Create new output.

### Example Concept:

If you have dataset:

-   You perform operations on it.

-   Instead of modifying original dataset,

-   You create a new dataset.

* * * * *

### First-Class Functions (Important Concept)

If a language supports first-class functions, then:

-   Functions can be assigned to variables

-   Functions can be passed as arguments

-   Functions can be returned from other functions

Example concept:

    a = 10
    b = a

Just like variables can be reassigned, functions can also behave similarly in functional programming.

* * * * *

### Languages

-   Python supports functional concepts.

-   It may not be purely functional but supports many functional ideas.

* * * * *

🔹 C. Object-Oriented Programming (OOP)
---------------------------------------

This is a major focus area.

### 📌 Core Idea

Code revolves around objects.

* * * * *

### What Is a Class?

A class is a blueprint/template.

Example:\
Class = Human\
Properties:

-   2 eyes

-   2 hands

-   1 nose

-   2 legs

* * * * *

### What Is an Object?

An object is an instance of a class.

Example:\
You are an object of class Human.

* * * * *

### Student Example from Video

Suppose each student has:

-   Name (String)

-   Roll Number (Integer)

-   Marks (Decimal)

What is the data type of student?

It is not:

-   Only string

-   Only integer

-   Only decimal

So we create a custom data type called class.

`class Student {
   name
   rollNumber
   marks
}`

Each student becomes an object.

* * * * *

### Why OOP?

Benefits:

-   Easy development

-   Easy debugging

-   Easy maintenance

-   Code reuse

* * * * *

### Car Example Explained

Car contains:

-   Engine

-   Steering

-   Wheels

If you want to change engine:

-   You don't replace entire car.

-   You modify only engine part.

OOP works the same way --- divide program into small manageable parts.

* * * * *

### Languages Supporting OOP

-   Java

-   Python

-   C++

Java heavily focuses on OOP.

* * * * *

4️⃣ Static vs Dynamic Typing
============================

This is about **when type checking happens**.

* * * * *

🔹 Static Typing
----------------

Type is checked at **compile time**.

Example (Java):

`int a = 10;
a = "kunal";   // Error`

Why?\
Because a was declared as integer.

Error appears before program runs.

* * * * *

### Compile Time Meaning

1.  You write source code.

2.  Compiler converts it to machine code.

3.  During conversion, type checking happens.

* * * * *

### Advantages:

-   Fewer runtime errors

-   More control

-   Better performance

### Languages:

-   Java

-   C

-   C++

* * * * *

🔹 Dynamic Typing
-----------------

Type is checked at **runtime**.

Example (Python):

`a = 10
a = "kunal"`

No error.

Because:

-   Type is decided when program runs.

* * * * *

### Important Concept

In dynamic typing:\
Variable can point to different objects over time.

Example:

`a = 10
a = 13.5
a = "hello"`

All valid.

* * * * *

### Disadvantage:

Error may appear during execution instead of compilation.

* * * * *

5️⃣ Compile Time vs Runtime
===========================

Compile Time:

-   Code is converted into machine code.

Runtime:

-   Program is actually executing.

Static typing → checked at compile time\
Dynamic typing → checked at runtime

* * * * *

6️⃣ Memory Management (Very Important Section)
==============================================

Two types of memory discussed:

1.  Stack Memory

2.  Heap Memory

* * * * *

🔹 Stack Memory
---------------

-   Stores reference variables

-   Stores function calls

* * * * *

🔹 Heap Memory
--------------

-   Stores actual objects (values)

* * * * *

🔹 Example
----------

`a = 10`

-   a is stored in stack

-   10 is stored in heap

-   a points to 10

Important:\
a is NOT 10\
a is just a reference.

* * * * *

7️⃣ Reference Variable vs Object
================================

Example given:

Your body = object\
Your name = reference variable

Different names:

-   Kunal

-   Son

-   Brother

-   Baby

All refer to same object.

If object changes (e.g., haircut),\
All references see same change.

* * * * *

8️⃣ Multiple Variables Pointing to Same Object
==============================================

Example:

`a = [1,3,5]
b = a`

Both point to same list.

If:

`a[0] = 99`

Then:

`b → [99,3,5]`

Because they share same object.

* * * * *

9️⃣ Garbage Collection
======================

If object has no reference pointing to it:

`a = 10
a = 37`

Now:

-   10 has no reference.

-   It becomes eligible for garbage collection.

In Java:\
Garbage Collector automatically removes unused objects.

* * * * *

🔟 Reassignment in Dynamic Language
===================================

Example:

`a = 10
a = "kunal"`

Internally:

-   New object "kunal" created

-   a now points to it

-   10 becomes unreferenced

-   Garbage collector removes it later

* * * * *

1️⃣1️⃣ Important Concepts Mentioned
===================================

-   Programming Languages

-   Binary (0s and 1s)

-   CPU & Memory (briefly mentioned)

-   Procedural Programming

-   Functional Programming

-   Pure Functions

-   First-Class Functions

-   Object-Oriented Programming

-   Classes

-   Objects

-   Compile Time

-   Runtime

-   Static Typing

-   Dynamic Typing

-   Stack Memory

-   Heap Memory

-   Reference Variables

-   Garbage Collection
