# technical interview prep
## YT - Fundamental Concepts of Object Oriented Programming- https://www.youtube.com/watch?v=m_MQYyJpIjg

1) Abstraction
2) Encapsulation
3) Inheritance
4) Polymorphism

What is an object?
- a thing you want to store and process data about, an entity

Abstraction
- simplify reality and focus only on the data and processes relevant to the application being built
- attributes and methods
- to create objects, you need a class. A class is a template of an object to define the attributes (properties) and the operations (methods).
- Cookie cutter
- each object is an instance of a class. Instantiation, making an instance of a class.
- These instances of an object can hold state of that particular object.
- constructor method using the keyword NEW.

Encapsulation
- hiding data and complexity (information hiding, safe from outside interference)
- we don't necessarily need to know the implementation code of a method to be able to use it.
- Data and the programs those data are bound together and their complexity is hidden

Inheritance
- a class can derive its methods and properties from another class. Resulting in a hierarchy of classes
- You can have an underlying class of Person, and then build more specific types of Person instances based on another class like, Employee or Customer, each of which is a type of Person. Super classes and sub classes

Polymorphism
- A class can implement an inherited method in its own way
- allows a subclass can override the workings of a method that it inherits from a super class

## OOP - with Freecodecamp - https://www.youtube.com/watch?v=SiBw7os-_zI
- Primitive data types - store single, simple values (byte, int, float, boolean, double, char)
- Simple, but there was a need to build on complexity. So, primitive data types were not enough.
- Grouping related variables together are necessary. So, there was a need for a structure.
    - You need ot store many pieces of different data together
    - allows for growing complexity
    - structure was a precursor for objects

Objects - allowed you to go beyond structures and store different types of data but also methods.
- Objects are instances of a class, classes are instances of an object.

1) Encapsulation: bundling data with methods that can operate on that data within a class
- hiding it within a class, preventing anything outside that class from directly interacting with it. Members of other classes can interact with the attribuites of another object through its methods. (Getters and Setters) Access internal attributes of an object through methods.
- You can run some validations on your setter methods
- You can have some attributes to be "read only" from the outside
- If you were to change attributes directly, it could violate some of the rules (behavior) you are intending for the program so using setters and getters can avoid that by having you validate the change before making the change.
- KEEPS THE PROGRAMMER IN CONTROL OF ACCESS TO DATA
- PREVENTS THE PROGRAM FROM ENDING UP IN ANY STRANGE OR UNWANTED STATES

2) Abstraction
- only showing essential details and keeping everything else hidden
- You only need to understand how to drive a car, but not how the internal combustion engine works.
- users of your classes should not worry about the inner workings of class.
- Making larger programs more manageable
- Think of it in terms of two parts - Interface and Implementation
    - we need to know how to use the interface but not need to understand the implementation.
    - built in .sort()

3) Inheritance
- allows classes to derive from other classes, inherit attributes and methods from another class.
- super class, subclass where the latter is a "type of" the former so you need to specify unqiue attributes and methods for each subclass. For example, a car Superclass, a ferrari subclass vs a honda subclass.
- Access Modifiers: change which classes have access to other classes, methods, or attributes
    - Public - can be accessed from anywhere in your program
    - Private - can only be accessed within the same class that the member is defined
    - Protected - can be accessed within the class it is defined, as well as any subclasses of that class.

4) Polymorphism
- methods that are able to take on many forms
    - Dynamic polymorphism
        - occurs during runtime, when a method signature is present in a subclass and superclass but have different implementation, the subclass implementation overrides that of the superclass.
    - Static polymorphism
        - occurs during compile time, when multiple methods with the same name but different arguments are defined in the same class (known as method overloading)

