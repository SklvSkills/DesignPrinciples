# Design principles

## [Composition over inheritance](https://en.wikipedia.org/wiki/Composition_over_inheritance)
Composition over inheritance (or composite reuse principle) in object-oriented programming (OOP) is the principle that classes should achieve polymorphic behavior and code reuse by their composition (by containing instances of other classes that implement the desired functionality) rather than inheritance from a base or parent class.

## [IoC (Inversion of control)](https://en.wikipedia.org/wiki/Inversion_of_control)
IoC inverts the flow of control as compared to traditional control flow. In IoC, custom-written portions of a computer program receive the flow of control from a generic framework. A software architecture with this design inverts control as compared to traditional procedural programming: in traditional programming, the custom code that expresses the purpose of the program calls into reusable libraries to take care of generic tasks, but with inversion of control, it is the framework that calls into the custom, or task-specific, code.

Inversion of control is used to increase modularity of the program and make it extensible, and has applications in object-oriented programming and other programming paradigms.

## [POP (Protocol-oriented programming)](https://www.pluralsight.com/guides/protocol-oriented-programming-in-swift)
In the Protocol-Oriented approach, we start designing our system by defining protocols. We rely on new concepts: protocol extensions, protocol inheritance, and protocol compositions.

## [Encapsulate what varies](https://www.oreilly.com/library/view/head-first-design/0596007124/ch01.html)
Take what varies and "encapsulate" it so it won’t affect the rest of your code. The result? Fewer unintended consequences from code changes and more flexibility in your systems!

## [KISS (Keep it short and simple)](https://en.wikipedia.org/wiki/KISS_principle)
The KISS principle states that most systems work best if they are kept simple rather than made complicated; therefore, simplicity should be a key goal in design, and unnecessary complexity should be avoided.

## [DRY (Don't repeat yourself)](https://en.wikipedia.org/wiki/Don%27t_repeat_yourself)
"Don't repeat yourself" is a principle of software development aimed at reducing repetition of software patterns, replacing it with abstractions or using data normalization to avoid redundancy.

The DRY principle is stated as "Every piece of knowledge must have a single, unambiguous, authoritative representation within a system". When the DRY principle is applied successfully, a modification of any single element of a system does not require a change in other logically unrelated elements. Additionally, elements that are logically related all change predictably and uniformly, and are thus kept in sync.

## [YAGNI (You aren't gonna need it)](https://en.wikipedia.org/wiki/You_aren%27t_gonna_need_it)
"You aren't gonna need it" is a principle of extreme programming (XP) that states a programmer should not add functionality until deemed necessary.

YAGNI is a principle behind the XP practice of "do the simplest thing that could possibly work" (DTSTTCPW). It is meant to be used in combination with several other practices, such as continuous refactoring, continuous automated unit testing, and continuous integration. Used without continuous refactoring, it could lead to disorganized code and massive rework, known as technical debt. YAGNI's dependency on supporting practices is part of the original definition of XP.

## [SOLID](https://en.wikipedia.org/wiki/SOLID)
In object-oriented computer programming, SOLID is a mnemonic acronym for five design principles intended to make software designs more understandable, flexible, and maintainable.

The SOLID concepts are:
- The **Single-responsibility principle**: "There should never be more than one reason for a class to change." In other words, every class should have only one responsibility.
- The **Open-closed principle**: "software entities ... should be open for extension, but closed for modification."
- The **Liskov substitution principle**: objects in a program should be replaceable with instances of their subtypes without altering the correctness of that program.
- The **Interface segregation principle**: "many client-specific interfaces are better than one general-purpose interface."
- The **Dependency inversion principle**: "depend upon abstractions, [not] concretions."
