# UML 

![circle](https://cppcodetips.files.wordpress.com/2013/12/class_diagram_sample.png)

Different visibility of the class can be represented as:

* “+” Public
* “-” Private
* “#” Protected

Different Parameter direction
* “in”           The parameter is an input parameter.
* “Inout”    The parameter is capable of both input and output.
* “Out”        The parameter is an output parameter.

Different type of members in a class
* 1) Static members are represented as underlined.
* 2) Pure virtual functions are represented as italics.

## Class relationship

In a system a class may be related to different classes,following are the different relation ship.

* Association (knows a)
* Dependency (uses a)
* Composition (has a)
* Aggregation (has a)
*  Inheritance (is a)
*  Class template

Different Multiplicity in a relation
* “0..1”            No instances, or one instance (optional, may)
* “1”                  Exactly one instance
* “0..* or *”    Zero or more instances
* “1..*”              One or more instances (at least one)

## Association
One object is aware of another; it contains a pointer or reference to another object.

![Association](https://cppcodetips.files.wordpress.com/2013/12/association_class_diagram.png)

## Dependency
One class depends on another if the independent class is a parameter variable or local variable of a method of the dependent class

![Dependency](https://cppcodetips.files.wordpress.com/2013/12/class_diagram_dependency.png)


## Aggregation
Aggregation can occur when a class is a collection or container of other classes, but where the contained classes do not have a strong life cycle dependency on the container—essentially, if the container is destroyed, its contents are not. You may have confusion between aggregation and association .Association differs from aggregation only in that it does not imply any containment.

![Aggregation](https://cppcodetips.files.wordpress.com/2013/12/class_diagram_aggregation.png)

## Composition
Composition is the stronger form of aggregation. Composition can occur when a class is a collection or container of other classes, but where the contained classes have a strong life cycle dependency on the container—essentially, if the container is destroyed, its contents are also destroyed

![Composition](https://cppcodetips.files.wordpress.com/2013/12/class_diagram_composition.png)

## Inheritance (Generalization)
In Inheritance relationship a class is derived from another class. It is a “is a” relationship between two classes.

![Composition](https://cppcodetips.files.wordpress.com/2013/12/class_diagram_inheritance.png)


Here Shape is an abstract class that is why it is shown in Italics. Draw () and Erase () methods of Shape class is pure virtual function, so it is also shown as italics.

![Composition](https://cppcodetips.files.wordpress.com/2013/12/class_diagram_inheritance_2.png)

## Class Template
Template class mean generic classes.Languages like C++, java, C# supports generic programming.
Representation

![Composition](https://cppcodetips.files.wordpress.com/2013/12/class_diagram_template.png)



