# S: Single Responsibility Principle
- Every class should have a single responsibility
- There should never be more than 1 reason for a class to change
- Classes should be small
- Avoid 'god classes'
- Split large classes into smaller classes

# O: Opened/Closed Principle
- Classes should be extendable/usable but not modifiable.
- Variables should be protected and methods should be used when modifying them

Open for extension, but Closed for modification. Initially I thought this was referring to overrides but it applies to any code modification too.

# L: Liskov Substitution Principle
If you have a "Shape" class and a "Circle" and "Square" subclass, code that uses Shape variables instead of Circle/Square variables should be equally correct if you use either subclass object. Otherwise your code should mention the specific subclass that matches it or have a new class type.

# I: Interface Segregation Principle
- Use specific interfaces for specific problems, instead of trying to overgeneralize
- Keep components focused and minimize dependencies.

Not complying with this can get you into situations where you no longer know what your object is, and can be impossible to recover from cleanly.

# D: Dependency Inversion Principle
1.  High-level modules should not import anything from low-level modules. Both should depend on abstractions (e.g., interfaces).
2.  Abstractions should not depend on details. Details (concrete implementations) should depend on abstractions.

This essentially means to write your code in a way that facilitates swapping out components when required. This is honestly the most complicated principle of all because it's extremely hard to know how far you're supposed to go in generalization or specification, and the ultimate goal is to save on developer costs, be it short term or long term.
