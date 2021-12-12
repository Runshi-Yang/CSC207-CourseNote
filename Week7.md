# Week 7

## [Design Patterns](https://sourcemaking.com/design_patterns)

### Definition: 
A design pattern is a general, reusable **solution** to a commonly occurring problem within a given context in software design. It is not a finished design that can be transformed directly into source or machine code. Rather, it is a description or template for how to solve a problem that can be used in many different situations.

### Requirements:

* Goals of object-oriented design:
    * Loose (Low) Coupling: Coupling refers to the degree to which the different modules/classes depend on each other, it is suggested that all modules should be independent as far as possible. It has to do with the elements among different modules/classes.
    * High Cohesion: Cohesion refers to the degree to which the elements of a module/class belong together, it is suggested that the related code should be close to each other. It has to do with the elements within the module/class. (Make each class does one thing and does it well.)
* Solid Principles

### UML:
* Solid line arrow: inherence (from a super class)
* Dotted line arrow: implement (an interface)


### 1. Iterator Design Pattern
#### Problem:

#### UML:

#### Benifit:
* It hides how you store the things that are iterable, so that you can change how you store them easily.
* It allows people to work with the project without knowing how the iterable class is implemented.

#### Anti-pattern:
* A collection that we want to access without knowing how it is stored.


### 2. Observer Design Pattern
#### Problem:

#### UML:

#### Benifit:
* ...
* ...

#### Anti-pattern:
* ActionA (caused by calling methodA) triggers ActionB (caused by calling methodB), but methodA and methodB are not in the same class.
* We don't want the observable knowing anything about its observers.


### 3. Strategy Design Pattern
#### Problem:

#### UML:

#### Benifit:
* ...
* ...

#### Anti-pattern:
* There are multiple classes that differ only in how they do something (have different algorithms)
* We have more than one way (algorithm) doing something


### 4. Dependency Injection Design Pattern
Dependency injection makes it so that a class no longer depends on the injected object's constructor.

Dependency inversion makes it so that we only call methods from an interface so we are no longer dependent on the rest of the object either (not just the constructor).
#### Problem:

#### UML:

#### Benifit:
* ...
* ...

#### Anti-pattern:
* Get rid of dependencies we don't want
* Used as part of "inverting the dependency"

### 5. Simple Factory Design Pattern
#### Problem:

#### UML:

#### Benifit:
* ...
* ...


### 6. Builder Design Pattern
#### Problem:

#### UML:

Sometimes the `Director` is optional and the `Builder` does all the building

#### Benifit:
* ...
* ...


### 7. Abstract Factory Design Pattern
#### Problem:

#### UML:

#### Benifit:
* ...
* ...