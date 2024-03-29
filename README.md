# JavaInterfaces
Several examples of how to use Java Interfaces (including nested ones).

## What is an Interface?
An interface in the Java programming language is an abstract type that is used to declare a behavior that classes must implement. They are similar to protocols. Interfaces are declared using the interface keyword, and may only contain method signature and constant declarations (variable declarations that are declared to be both static and final). All methods of an Interface do not contain implementation (method bodies) as of all versions below Java 8. Starting with Java 8, default and static methods may have implementation in the interface definition. Then, in Java 9, private and private static methods were added. At present, a Java interface can have up to six different types.

Interfaces cannot be instantiated, but rather are implemented. A class that implements an interface must implement all of the non-default methods described in the interface, or be an abstract class. Object references in Java may be specified to be of an interface type; in each case, they must either be null, or be bound to an object that implements the interface.
![image](https://user-images.githubusercontent.com/31170255/235689461-f69b6182-83cf-4318-a1df-e13a51b652f9.png)
![image](https://user-images.githubusercontent.com/31170255/235689582-4075b577-5a3f-41af-9af6-74c100b7e79d.png)

One benefit of using interfaces is that they simulate multiple inheritance. All classes in Java must have exactly one base class, the only exception being java.lang.Object (the root class of the Java type system); multiple inheritance of classes is not allowed. However, an interface may inherit multiple interfaces and a class may implement multiple interfaces.

Source: Wikipedia
