<!-- START doctoc generated TOC please keep comment here to allow auto update -->
<!-- DON'T EDIT THIS SECTION, INSTEAD RE-RUN doctoc TO UPDATE -->
Table of Contents

-   [Memory Models](#memory-models)
-   [Drawing Memory Models with Primitive
    Data](#drawing-memory-models-with-primitive-data)
-   [Drawing Memory Models with
    Objects](#drawing-memory-models-with-objects)
-   [Core: Introduction to Scope](#core-introduction-to-scope)

<!-- END doctoc generated TOC please keep comment here to allow auto update -->
Memory Models
=============

Drawing Memory Models with Primitive Data
-----------------------------------------

Code tracing warm up

``` {.java}
int var1;
var1 = 52;
int var2;
var2 = var1;
var1 = 127;
System.out.println("var1 is " + var1 + ", var2 is " + var2);
```

![]() todo: trace and create memory model diagram

-   People who are better at writing code are that way because they can
    reason better through code.

**Creating code models for tracing**:

-   **Variable declaration**: draw a box and label it with the
    variable's namea
-   **Variable assignment**: put the value of the right hand side (RHS)
    into the box for the variable on the left hand side (LHS)

In java, the line `var2 = var1` does **NOT** mean that they are the same
variable. In java, this means that the value **only** gets copied. Not
the entire variable in memory.

Drawing Memory Models with Objects
----------------------------------

-   **Primitive type** in Java:
    -   boolean
    -   byte
    -   short
    -   int
    -   long
    -   float
    -   double
    -   char
-   **Object type**:
    -   Arrays
    -   Classes
    -   Anything else
-   Objects are stored in **the heap**.
    -   `new` allocates space in the heap.

Core: Introduction to Scope
---------------------------

-   The **scope** of a variable is the area where it is defined to have
    a value.
-   **Local variables** are declared inside a method.
-   **Parameters** are values that are parts of methods. They function
    like local variables.
-   **Member variables** are declares outside any method.

-   `this` is optional in Java. If you don't use it, Java will look for
    available variables in the local scope with the same name. If none
    exist, then it looks in any available member variables.


