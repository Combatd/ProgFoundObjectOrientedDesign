# ProgFoundObjectOrientedDesign
Programming Foundations Object Oriented Design

## Object-Oriented Fundamentals
* In procedural code, the program is written as a long series of operations to execute
  * Some may be organized into functions/subroutines for modularity, but otherwise it goes from A to B
* New programmers start out writing procedural programs, like a cake baking recipe list of steps.
* Object-Oriented Program is split into separate objects
  * Baking might be the mixer, pan, and oven with properties and actions related to it.
* Procedural and Object-Oriented Programming both can descirbe baking a cake, but with OOP, it is reusable.
  * I can use the OOP version to bake muffins due to their similarity, for example.
* Object-Oriented Programming languages are all over, like C++, C#, Java, JavaScript, Python, Ruby, Swift, VB.NET, and more
  * Desktop Applications, web applications, game development, etc.
* Object-Oriented Design makes more sense at scale, with larger programs that require lots of changes.

* Object-Oriented Thinking makes programming represent objects that exist in the real world.
  * A mug, a coffeepot, etc.
  * Every object has properties that maintain its current state
  * Size, weight, color...attributes, properties, state, fields, variables, those are all related terms used by programmers
* An object has nothing to do with its complexity.
 * A cell phone may be complex in the real world, but you can describe certain characteristics
 * Cell phone has behaviors like call, text, etc...
 * Each cell phone would be unique with their own identity as an object
 * Attributes: color, size, weight, brand...
 * Objects can be any sort of noun.
  * Things, people, places, ideas...
* Objects are created by classes
* A class is a code-template for creating (instantiating) objects.
 * Different classes can create different objects.
* The class always comes first.
* Classes have a name, attributes to describe an object to be created, and behaviors for what the object can do
* Sometimes referred to as type (name), properties, data (attributes), and operations (behaviors)
* A method is a block of code or procedure that can return a value
* Methods are basically functions, but they are defined as part of a class.
 * They can only access data that is known to the object
* Instances are objects made from a class
* Most Object-Oriented Languages come with provided classes, such as string, integer, etc.
* Four fundamental concepts in Object-Oriented Programming with classes
 * Abstraction
 * Polymorphism
 * Inheritance
 * Encapsulation
* A person class is abstract. If you describe a person, it doesn't have to be any particular person.
 * We can discuss essential attributes, like name, height, and gender without referring to a specific person object.
 * The attributes of the Person class are abstracted, not caring about what exact values of the attributes of Person objects.
 * If a certain attribute, like weight, is not needed for the application, then we can leave it out of Person class. 
 * The attributes of the Person class are abstracted, not caring about what exact values of the attributes on each Person instance
* With encapsulation, an object should not make anything about itself available except when necessary to make the application work
 * Black Box Testing: close off things on a class/object to only reveal specific inputs and outputs
 * You don't need to know everything about a cell phone internally in order to use it
 * We want to reduce dependencies on a single part of the application...
 * We would rather not have to change a lot when making big changes, so we should encapsulate when possible.

* Inheritance allows a new class to receive or inherit the attributes or methods of existing methods using the same implementation for code reuse
* A bakery app can have customer and employee classes, sharing some properties like name, phone, address, etc.
 * We could create a person class with common attributes and methods, then customer and employee can inherit from person class
 * Parent / Base / Superclass Class is Person
 * Subclass / Child Class Customer, Employee
* Some languages like C++ and Python allow you to inherit from multiple Superclasses, but can be confusing
* Java, Ruby, and others enforce Single Inheritance
* There are multiple forms of Polymorphism.
 * Dynamic Polymorphism uses the same interface for methods on different types of objects by overriding methods for unique instances
 * Static polymorphism uses a method overload on the parameters
 * Create an abstract class, implement an interface in multiple classes, or override inherited methods
* Unified Modeling Language (UML) Standardized notation for diagrams to visualize object-oriented systems
 * Class diagram: Name, attributes, behaviors
 * class, component, deployment, use case, other diagrams

* Functional requirements list what the app should do, with no object oriented design yet
* Non-functional requirements list attributes that are not functionality related, but should only describe essentials
* FURPS - Functionality Usability Reliability Performance Supportability
 * Functionality: Capability, Resuability, Security
 * Usability: Human Factors, Aesthetics, Consistency, Documentation
 * Reliability: Availability, Failure Rate & Duration, Predictability
 * Performance: Speed, Efficiency, Resource Consmumption, Scalability
 * Supportability: Testability, Estensibility, Serviceability, Configurability
 * Design
 * Implementation
 * Interface (external system)
 * Physical
