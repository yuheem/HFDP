# Chapter 1

What are disadvantages of using inheritance?
* Changing a superclass may have unintended consequences on subclasses

No matter how well you design an application over time an application
must grow and change or it will die.

Design Principle 1:
Identify the aspects of your application that vary and separate them
from what stays the same. Take the parts that vary and encapsulate
them, so later we can alter or extend the parts that vary without 
affecting those that don't.

Design Principle 2:
Program to an interface, not an implementation.

We want to assign the concrete implementation object at runtime.

A class should delegate its behaviors instead of using concrete 
methods defined in the class for its behaviors. Shift the responsibility
of the behavior to the interface. The constructor will assign the 
correct behavior during runtime. Then we can ask the referenced 
behavior object to just perform the behavior for our class.
