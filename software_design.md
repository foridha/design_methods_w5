# Notes:

There are three principle design strategies used in software engineering:

- Structured design
- Function oriented design
- Object oriented design

There is no single correct way to approach a software engineering problem. but usually one method is better over another. 

#What do we mean by coupling and cohesion when discussing structured design?
Coupling refers to how modules or components in a software system are connected, with low coupling being better for flexibility. Cohesion measures how closely related the functions within a module are, with high cohesion indicating a focused purpose.

# Questions:

### What is the difference between top-down and bottom-up design? Which best describes a function oriented design?
Top-down design starts with an overall view and breaks it into smaller parts, while bottom-up design begins with small components and builds up. Function-oriented design often uses both approaches depending on the situation.

### In which design methodology would a class diagram be most useful?
Class diagrams are most useful in the object-oriented design methodology. They visually represent classes, attributes, methods, and their relationships, which is vital for designing systems with objects and classes.

### What are the four pillars of object oriented programming? Give a single-sentence description of each.
These include Encapsulation (bundling data and methods), Abstraction (simplifying reality), Inheritance (reusing and extending code), and Polymorphism (treating different objects as a common type).

### What is the strategy pattern? How would its implementation differ between a functional and object oriented system?   
It's a design pattern for defining and encapsulating interchangeable algorithms. In a functional system, it involves defining functions or function objects. In an object-oriented system, it creates a family of classes for different strategies.

### Imagine your is creating a new online payment system. In order to gain maximum market share it can't be tied to a particular sector - it needs to work just as well when ordering a takeaway as when buying a new coat. Which design methodology would you suggest following? Give some justification for your decision.
For a versatile payment system, following the object-oriented design methodology is better as it needs to work in many different scenarios. It allows modeling different payment methods and sectors as objects. Offering reusability and maintainability through classes, inheritance, and polymorphism. s