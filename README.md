# TechKnowledge
A guide for the technical (non-coding) questions commonly asked during software engineering interviews with brief answers to each concept.

## OOPS Concepts
* **Overloading vs Overriding** : Overloading is the concept where 2 methods have the same name but different parameters. Overriding is the concept where 2 methods have the same name and the same parameters. (one method would be in parent class and the other in child class)

* **Virtual Functions** : A function declared in base class but defined in derived class (overriding), use a pointer/reference to base class to call the derived class's version. It must be declared in public. [Runtime Polymorphism]

* **Pure Virtual Functions** : A pure virtual function doesn't have an implementation, just a declaration. Example: virtual void show() = 0;

* **Virtual vs Abstract Functions**
Virtual functions have an implementation whereas abstract functions don't in the base class.

* **Polymorphism** : The ability of an object to vary it's behaviour based on its type i.e. allows you to handle different data types/objects through the same interface. (Concept similar to overriding)

* **Encapsulation** : Restrict access to data or methods (public,private,protected) and bundling of data and methods together is known as encapsulation.

* **Inheritance** : Purpose is code reuse where any class can be written based on another class and use its data and methods.

* **Abstraction** : based on building a model of a method/class. Requires minimal knowledge of implementation details like methods of the class or parameters of the method to trigger a specific operation.

* **Static Functions**: They are global to a particular file and can be called anywhere in that particular file.

* **Static Variables**: To modify a variable outside a function's scope we declare it static. 

## C/C++ specific questions
* **Size of data types** : *char* - 1 byte, *int* - 2 bytes *float* - 4 bytes, *double* - 8 bytes

## Data Structures
* **Difference between ordered_map and map** :
* **Difference between ordered_set and set** :

## Databases
* **Database index** : Indexing is a way of sorting a number of records by creating another data structure that holds the field value and pointer to the record it relates to. The disadavantage of using indexes is that it requires extra disk space
* **Data warehousing** : Aggregation of data from multiple sources to make a central repository of information that can be analysed to make informed decisions or for other purposes of data usage by an organisation. 

## Operating Systems
* **Mutex** :  
* **Condition Variable** :
* **Threads vs Process** :
* **Memory hierachy** :


## Others
* **Microservices** : Microservices enable continuous deployment of large/complex applications, with the ability to change or evolve tech stack on which the application is built. (In simpler words, the ability to build an application by breaking it down to multiple components, where each component can be individually deployed and maintained).
This makes applications easier to understand and maintain.