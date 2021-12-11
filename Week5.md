# Week 5

## Package

### 1. folder/directory/package
* `folder`: something that holds files
* `directory`: offical name of folder when talking about traversing around the computer.
* `package`: a folder inside an object oriented program that contains codes or subfolders containing code.

### 2. Purpose of packaging:
* Organize the code so that people can easily locate the class he want to find.
* Access modifier can make everything as private as possible so that one part of the code doesn't care what happens to another part of the code.

### 3. Two meanings of "use case"
* Use case in Clean Architecture. 
* How one might use a program.
    Example: User searches for a specific title. / User searches for all authors last name starting with A.

### 4. Dependency and ...
* Class A is dependent on class B if a change to class B can necessitate a change to class A. (A calls a method in B)
*

### 5. Packaging Strategry
* By Layer
* By Feature
* Inside/Outside
* By Component

## Design Patterns

### 1. Definition: 
A design pattern is a general, reusable solution to a commonly occurring problem within a given context in software design. It is not a finished design that can be transformed directly into source or machine code. Rather, it is a description or template for how to solve a problem that can be used in many different situations.

### 2. Requirements:

* Goals of object-oriented design:
    * Loose (Low) Coupling: Coupling refers to the degree to which the different modules/classes depend on each other, it is suggested that all modules should be independent as far as possible. It has to do with the elements among different modules/classes.
    * High Cohesion: Cohesion refers to the degree to which the elements of a module/class belong together, it is suggested that the related code should be close to each other. It has to do with the elements within the module/class. (Make each class does one thing and does it well.)
* Solid Principles