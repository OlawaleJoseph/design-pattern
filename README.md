# Design Patterns

## Table of Contents

- [What is OOP?](#what-is-oop)
- [What is an Object?](#what-is-an-object)
- [What is a subclass?](#what-is-a-subclass)
- [What are the Pillars of OOP?](#what-are-the-pillars-of-oop)
- [What is Abstraction?](#what-is-abstraction)
- [What is Encapsulation?](#what-is-encapsulation)
- [What is Inheritance?](#what-is-inheritance)
- [What is Polymorphism?](#what-is-polymorphism)
- [What is Dependency?](#what-is-dependency)
- [UML Relations Between Objects](#uml-relations-between-objects)
  - [What is UML Dependency?](#what-is-uml-dependency)
  - [What is UML Association?](#what-is-uml-association)
  - [What is UML Aggregation?](#what-is-uml-aggregation)
  - [What is UML Composition?](#what-is-uml-composition)
  - [What is UML Composition?](#what-is-uml-composition-1)
  - [What is UML Implementation?](#what-is-uml-implementation)
- [What is UML Inheritance?](#what-is-uml-inheritance)
- [What is a Design Pattern?](#what-is-a-design-pattern)
- [List some software desgin principles](#list-some-software-desgin-principles)
- [What is Encapsulate What Varies?](#what-is-encapsulate-what-varies)
- [What is Program to an Interface, not an Implementation?](#what-is-program-to-an-interface-not-an-implementation)
- [What are the probles when using inheritance?](#what-are-the-probles-when-using-inheritance)
- [What is Favor Composition Over Inheritance?](#what-is-favor-composition-over-inheritance)
- [What are SOLID Principles?](#what-are-solid-principles)
- [What is Single Responsibility Principle?](#what-is-single-responsibility-principle)
- [What is Open/Closed Principle?](#what-is-openclosed-principle)
- [What is Liskov substitution principle?](#what-is-liskov-substitution-principle)
- [What is Interface Segregation Principle?](#what-is-interface-segregation-principle)
- [What is Dependency Inversion Principle?](#what-is-dependency-inversion-principle)
- [What are Low-level classes?](#what-are-low-level-classes)
- [What are High-level classes?](#what-are-high-level-classes)
- [What are the three types of design patterns?](#what-are-the-three-types-of-design-patterns)
- [What is the creational design patterns](#what-is-the-creational-design-patterns)

## What is OOP?

Object-oriented programming is a paradigm based on the con- cept of wrapping pieces of data, and behavior related to that data, into special bundles called objects, which are construct- ed from a set of “blueprints”, defined by a programmer, called classes.

**[⬆ Back to Top](#design-patterns)**

## What is an Object?

An object is instances of a classe.

**[⬆ Back to Top](#design-patterns)**

## What is a subclass?

A subclass inherits state and behavior from it's parent, defining only attributes or behaviors that differ.

**[⬆ Back to Top](#design-patterns)**

## What are the Pillars of OOP?

1. Abstraction
2. Encapsulation
3. Inheritance
4. Polymorphism

**[⬆ Back to Top](#design-patterns)**

## What is Abstraction?

Abstraction is a model of a real-world object or phenomenon, limited to a specific context, which represents all details rele- vant to this context with high accuracy and omits all the rest.

**[⬆ Back to Top](#design-patterns)**

## What is Encapsulation?

Encapsulation is the ability of an object to hide parts of its state and behaviors from other objects, exposing only a limit- ed interface to the rest of the program.

**[⬆ Back to Top](#design-patterns)**

## What is Inheritance?

Inheritance is the ability to build new classes on top of exist- ing ones. The main benefit of inheritance is code reuse.

**[⬆ Back to Top](#design-patterns)**

## What is Polymorphism?

Polymorphism is the ability of a program to detect the real class of an object and call its implementation even when its real type is unknown in the current context.

**[⬆ Back to Top](#design-patterns)**

## What is Dependency?

There is a dependency between two class- es if some changes to the definition of one class might result in modifications to another class.

Dependency typically occurs when you use concrete class names in your code. You can make a dependency weaker if you make your code dependent on interfaces or abstract classes instead of concrete classes.

**[⬆ Back to Top](#design-patterns)**

## UML Relations Between Objects

![](https://user-images.githubusercontent.com/11765228/74296674-78bc1980-4d7f-11ea-8e52-2cbc14bf0ecb.png)

### What is UML Dependency?

Class А can be affected by changes in class B.

**[⬆ Back to Top](#design-patterns)**

### What is UML Association?

Object А knows about object B. Class A depends on B.

**[⬆ Back to Top](#design-patterns)**

### What is UML Aggregation?

Object А knows about object B, and consists of B. Class A depends on B.

**[⬆ Back to Top](#design-patterns)**

### What is UML Composition?

Object А knows about object B, consists of B, and manages B’s life cycle. Class A depends on B.

**[⬆ Back to Top](#design-patterns)**

### What is UML Composition?

Object А knows about object B, consists of B, and manages B’s life cycle. Class A depends on B.

**[⬆ Back to Top](#design-patterns)**

### What is UML Implementation?

Class А defines methods declared in interface B. Objects A can be treated as B. Class A depends on B.

**[⬆ Back to Top](#design-patterns)**

## What is UML Inheritance?

Class А inherits interface and implementation of class B but can extend it. Objects A can be treated as B. Class A depends on B.

**[⬆ Back to Top](#design-patterns)**

## What is a Design Pattern?

Design patterns are typical solutions to commonly occurring problems in software design. They are like pre-made blueprints that you can customize to solve a recurring design problem in your code.

**[⬆ Back to Top](#design-patterns)**

## List some software desgin principles

1. Code reuse
2. Extensibility
3. Encapsulate What Varies
4. Program to an Interface, not an Implementation
5. Favor Composition Over Inheritance
6. SOLID Principles

**[⬆ Back to Top](#design-patterns)**

## What is Encapsulate What Varies?

Identify the aspects of your application that vary and separate them from what stays the same.

**[⬆ Back to Top](#design-patterns)**

## What is Program to an Interface, not an Implementation?

Depend on abstractions, not on concrete classes.

**[⬆ Back to Top](#design-patterns)**

## What are the probles when using inheritance?

- Subclasses are tightly coupled to superclasses. Any change in a superclass may break the functionality of subclasses.
- A subclass can’t reduce the interface of the superclass. You have to implement all abstract methods of the parent class even if you won’t be using them.

**[⬆ Back to Top](#design-patterns)**

## What is Favor Composition Over Inheritance?

Instead of car objects implementing a behavior on their own, they can dele- gate it to other objects.

**[⬆ Back to Top](#design-patterns)**

## What are SOLID Principles?

1. Single Responsibility Principle

**[⬆ Back to Top](#design-patterns)**

## What is Single Responsibility Principle?

> A class should have just one reason to change.

The main goal of this principle is reducing complexity. You don’t need to invent a sophisticated design for a program that only has about 200 lines of code. Make a dozen methods pret- ty, and you’ll be fine.

**[⬆ Back to Top](#design-patterns)**

## What is Open/Closed Principle?

> Classes should be open for extension, but closed for modification.

**[⬆ Back to Top](#design-patterns)**

## What is Liskov substitution principle?

> When extending a class, remember that you should be able to pass objects of the subclass in place of objects of the parent class without breaking the client code.

This means that the subclass should remain compatible with the behavior of the superclass. When overriding a method, extend the base behavior rather than replacing it with something else entirely.

The substitution principle is a set of checks that help pre- dict whether a subclass remains compatible with the code that was able to work with objects of the superclass.

The safest way to extend a class is to introduce new fields and methods, and not mess with any existing members of the superclass. Of course, that’s not always doable in real life.

**[⬆ Back to Top](#design-patterns)**

## What is Interface Segregation Principle?

> Clients shouldn't be forced to depend on methods they do not use.

According to the interface segregation principle, you should break down “fat” interfaces into more granular and specific ones. Clients should implement only those methods that they really need. Otherwise, a change to a “fat” interface would break even clients that don’t use the changed methods.

![](https://user-images.githubusercontent.com/11765228/74307832-926e5880-4da1-11ea-8f9b-b9c6c35010eb.png)

**[⬆ Back to Top](#design-patterns)**

## What is Dependency Inversion Principle?

> High-level classes should not depend on low-level classes. Both should depend on abstractions. Abstractions shouldn't depend on details. Details should depend on abstractions.

![](https://user-images.githubusercontent.com/11765228/74308169-79b27280-4da2-11ea-8183-43c1f0b57f70.png)

**[⬆ Back to Top](#design-patterns)**

## What are Low-level classes?

Low-level classes implement basic operations such as working with a disk, transferring data over a network, connecting to a database, etc.

**[⬆ Back to Top](#design-patterns)**

## What are High-level classes?

High-level classes contain complex business logic that directs low-level classes to do something.

**[⬆ Back to Top](#design-patterns)**

## What are the three types of design patterns?

1. Creational patterns
2. Structural patterns
3. Behavioral patterns

**[⬆ Back to Top](#design-patterns)**

## What is the creational design patterns

Creational patterns provide various object creation mecha- nisms, which increase flexibility and reuse of existing code.

**[⬆ Back to Top](#design-patterns)**
