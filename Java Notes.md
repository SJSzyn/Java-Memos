## Polymorphism

- Compile-time Poly
	- Static
	- Many functions with same name | ! But has distinct parameters => Overload
- Run-time Poly
	- Dynamic Method Dispatch

## Inheritance (Remember Various Types of Inheritance)

- Inherit characters & behaviors of the parent
- Build new classes based on existing ones
- Take existing methods from parent class | Add new methods in current class
- sub/child classes : The one that inherits from the parent class
- superclass: This takes class already has predetermined methods

- Multilevel Inheritance

## Data Abstraction

- Hiding details, but shows only functionality
- delcared with keyword
- can be abstract and non-abstract methods
- It cannot be instantiated
- It can have final methods
- It can have constructors and static methods also.

It's real scenerio
## Encapsulation

- Wrapping code into a single data
- Use setter & getter to retrieve data
- Data hiding & data binding
## Class

- takes no memory since it's a blueprint
	- But when the objets are created, then memory is used

## Constructors

- Special methods that take on the class name

## Garbage collection

- Handling memory in the program
- through garabage collection it is freed up and get rids of unwanted objects

# Methods
- camelCase
- Starts with a verb that describes the action of method (get, set, find, reset, show...)
- The name is followed by what it does
- Verb d'etat for boolean stuff

# Interface

- Interfaces cannot be declared as private or protected. Only public and default modifiers are allowed.
- Every interface in Java is by default abstract.
- A class can extend another class and can implement an interface as well.
- From Java 8 onward, an interface can have default and static methods with a body.
- An interface can have another interface inside it

# Abstract

- Abstract classes are used to provide common method implementation to all the subclasses or to provide a default implementation
- An abstract class can have abstract methods without a body and can also have methods with a body.
- It is not necessary for an abstract class to have abstract methods. A class can be marked as abstract even if it doesn't declare any abstract methods[
- Abstract classes cannot be instantiated and can have constructors.

---
