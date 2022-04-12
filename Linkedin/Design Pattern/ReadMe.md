# Object Oriented Design

### Learning objectives:
* What are design patterns?
* Encapsulating code that varies with the Strategy pattern
* The limitations of inheritance
* Using the Adapter pattern
* Implementing the Observer pattern
* Extending behavior with composition and the Decorator pattern
* Encapsulating iteration with the Iterator pattern
* Object creation with the Factory Method pattern
* Using design principles to guide your object-oriented design
---
**program to an interface,Not an implementation:** client reamin unware of specific types of objects they use,as long as object adhere to the interface that clients expect.

**favor composition over inheritance:** classes should achieve code reuse using composition rather than inheritance from a superclass.

---
###### Design Patterns:

**importance of the fundamental properties of object-**:
* inheritance
* polymorphism
* abstraction
* encapsulation
-  When these are the only tools in your toolbox, your design process can quickly go off the rails. In fact, it can lead to software that is downright difficult to design, maintain, and extend



********
- Design patterns were first described in the book Design Patterns: Elements of Reusable Object-Oriented Software Design. 

##### Advanges of design patters:
* Not reinvent the wheel.
* create software that is resilient to change.
* preparing for future additions.

**Design patterns:** are all about reusing experience, design experience. Design patterns aren't algorithms, and they're not code. A design pattern is an approach to thinking about software design .


**the strategy pattern** this pattern defines a family of algoithm, encapsulate each one, and make them interchangeable.


**Dsesign priciple:** give you a set of guidelines that will help you to avoid bad object-oriented design.


| design principles  | design patterns           |
| ------------------ | ------------------------- |
| general guidelines | specific design solutions |

EX:
**encapsulate what varies:** identify the aspect of your application that vary and seperate them from what stay the same.

---
##  The Strategy Pattern

** So pay attention.if all your class relationships are IS_A Relationsgips, it might be time to take a closer look at your design**

**Why**
Because when you overuse inheritance, you can end up with designs that are inflexible and difficult to change

**problem with inheritnace design:**
* don't seem to be getting a huge reuse benefits and things are getting a little messy.
* code duplicated across the classes.
* it's hard to gain knowledge of all the ducks.
* a simple change to the superclass can lead to unintended side effects with the other ducks.
* runtimebehaviors changes are diffcult.
  

  **problem with interface design:**

* it destroys code reuse.
* it become a maintenance nightware.
* it doesn't allow for runtime changes in behaviors.
  
**strategy pattern:**

![strategy pattern](https://user-images.githubusercontent.com/70604321/162845397-0ccbda72-748e-4436-a1a6-78a6dfd455b7.PNG)

---

## The Adapter Pattern

this pattern converts the interface of a class into another interface that clients expect,it allow classes to work together that couldn't otherwise because of incompatible interface.


**Adapter pattern:**
![adapter](https://user-images.githubusercontent.com/70604321/162852972-d70e9ade-5670-45b3-83ad-9b2f0c31e180.PNG)

**Adapter Use Composition:**
* The client is composed with with the class with the target interface
* the adapter is composed with the adaptee.
* the adapter delegates calls to the adaptee, and return any need value.
* the client and adaptee dontn't know three's a adapter between them.

-----


## Observer pattern


**Loose coupling:** strive for loosely coupled designs between objects that interact

-> s? We say that objects are loosely coupled when they interact with one another, which makes them coupled, but they don't know a lot about each other.

**The observer Pattern:** The observer pattern defines a one-to-many dependency between objects so that when one object changes state, all its dependents are notified and updated automatically


![observer](https://user-images.githubusercontent.com/70604321/162856115-6015671d-95a0-4137-9c6f-091ba224514b.PNG)

![observe](https://user-images.githubusercontent.com/70604321/162856570-d56faadd-59f5-47f0-94cf-1e33ed2b1b44.PNG)
