# The key differences between classes and objects in Python, and how are they used to create and manage instances of a class

* Definition vs. Instance: A class is a blueprint or template that defines the attributes and behaviors of objects. An object, also known as an instance, is a specific realization of a class that holds its own unique data and behavior.

* Attributes and Methods: Classes define attributes (variables) and methods (functions) that represent the properties and actions of objects. Objects hold the actual values for the attributes and can invoke the methods defined in the class.

* Object Instantiation: To create an instance of a class, you need to instantiate the class by calling it as if it were a function. This creates a new object based on the class definition. During instantiation, the class's __init__ method is called, allowing you to initialize the object's attributes. Each instance operates independently, with its own attribute values.

In summary, classes act as blueprints for creating objects, objects represent specific instances of a class with their own data and behavior, and object instantiation creates new objects based on the class definition.

# Recursion function and the best practices to follow when implementing it


* Recursion is a programming concept where a function calls itself to solve a problem by breaking it down into smaller subproblems.
* It involves defining base case(s) that act as termination conditions and recursive case(s) where the function calls itself with a smaller or simpler input.
* Best practices include defining proper base cases, ensuring progress towards the base case, avoiding redundant computations, using appropriate function parameters, and testing with different inputs.

## When implementing a recursive function follow this steps:

* define a base case that will terminate the recursion.

* Make sure that the recursive calls to the function are getting closer to the base case.

* test the function with different inputs.


# pytest fixtures and code coverage

* Pytest fixtures provide reusable setup and data for tests, improving test quality and maintainability.
* Code coverage measures the percentage of code executed during testing, helping identify areas that need additional test coverage.
* Using fixtures and code coverage together enhances test quality, readability, and maintainability.
* Fixtures enable modular and well-structured tests, reducing duplication and making tests easier to understand.
* Code coverage analysis ensures critical areas of the codebase are adequately tested and helps track and maintain test coverage over time.
