# Chapter 2

The Observer Pattern: defines a one-to-many dependency between objects 
so that when one object changes state, all of its dependents are notified
and updated automatically.

Subject interface
* registerObserver()
* removeObserver()
* notifyObservers()

Observer interface
* update()

When objects are loosely coupled they can interact but they typically
have very little knowledge of each other which gives us flexibility.

How does the Observer pattern achieve loose coupling?
1. The only thing the subjects knows about an observer is that it
implements a certain interface 
2. We can add new observers at any time
3. We never need to modify the subject to add new types of observers
4. We can reuse subjects or observers independently of each other
5. Changes to either the subject or an observer will not affect the other

Design Principle 4: Strive for loosely coupled designs between 
objects that interact

By minimizing the interdependency between objects our OO systems 
are more flexible and handle change better.
