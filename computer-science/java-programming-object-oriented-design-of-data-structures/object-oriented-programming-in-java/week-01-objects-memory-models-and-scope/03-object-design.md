<!-- START doctoc generated TOC please keep comment here to allow auto update -->
<!-- DON'T EDIT THIS SECTION, INSTEAD RE-RUN doctoc TO UPDATE -->
Table of Contents

-   [Object Design: Constructors, Instance Variables,
    Methods](#object-design-constructors-instance-variables-methods)
-   [Core: Defining Classes and Creating
    Objects](#core-defining-classes-and-creating-objects)
-   [Core: Overloading Methods](#core-overloading-methods)
-   [Core: Public vs. Private](#core-public-vs-private)

<!-- END doctoc generated TOC please keep comment here to allow auto update -->
Object Design: Constructors, Instance Variables, Methods
========================================================

Core: Defining Classes and Creating Objects
-------------------------------------------

-   **Computer Science**: The science of using and processing large
    amounts of information to automate useful tasks and learn about the
    world around us (using a computer).
-   How do we organize the mass amount of information?
-   Match the program to the problem we're trying to solve

-   **Class**
    -   A type of data
    -   Like a factory
-   **Object**
    -   One instance of a class
    -   Each individual object can be customized and changed without
        affecting the other objects.

**Member variables**: data an object needs to store. **Methods**: The
*things* a class can do. **Constructor**: Method to create a new object.
- Doesn't have a return type (implicitly void).

-   Creating and using objects
    -   `new` calls the constructor of a new object.
    -   `ucsd.distance(lima)`
        -   ucsd: name of the variable storing the object
        -   distance: method of the `ucsd` object
        -   lima: parameter passed to the `distance` method.

Core: Overloading Methods
-------------------------

-   You can create other declarations of the same method if it has
    different parameters.
    -   e.g. `public void test()` and `public void test(int value)` are
        all valid to be in the same exact class.
        -   You can **only** change the return type (e.g. `void`, `int`)
            if the parameter list is also different.
    -   Can apply to constructors as well.
-   How do you find out where all the different information about the
    different overloaded constructors/methods exist?
    -   Explore the Javadocs! These will have that information.

Core: Public vs. Private
------------------------
