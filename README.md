# OOPS-CLASS-OBJECT-INHERITANCE-POLYMORPHISM


Why OOP ?
It makes it so much easier to maintain and update existing code.
Provides code reusability.
It is best for real-life problems.
Provides a modular structure.
It is easy to debug.
In comparison to others (functional or structural), it is much faster and more efficient to use.

Class & Object
A class works as a blueprint for the object. With the help of one class, many objects can be created. An object is an instance of the class.
obj_name = ClassName() is the syntax for creating an object for the class.

A class can contain functions and variables both. The function that is defined inside a class is called a class method. Every member of the class is only accessed by the object of the class, including variables and methods.

__init__ is a reserved method for classes in Python. It is a constructor that is automatically called when the object is created for the class. It is mostly used for defining variables for the class. Variables inside the constructor are instance attributes.

The Four Pillars Of OOP
1.Inheritance
2.Encapsulation
3.Abstraction
4.Polymorphism


1. Inheritance
Inheritance is the process by which one class inherits the properties of another class. This newly formed class is called a child class and the other class is called a parent class. It provides code reusability because we are using an existing class to increase the properties of a new class. A child class can access all the data members and functions of the parent class.

2. Encapsulation
Encapsulation is the process of hiding the data, providing security to data by making the variable protected. The protected member can only be accessed by the class member. If you try to access it outside the class normally, by creating an object. it will result in an error. To access the protected member you need to use object._protectedmember.

3. Polymorphism
Polymorphism means having different forms. It refers to the ability of a function with the same name to carry a different functionality altogether. One of the best examples of inbuild polymorphism is the len() function. When we use it for a list, it returns the count of number elements in the list. When we use it with a dictionary, it returns the count of keys. When we use it with a string, it returns the number of characters in the string. Let’s see an example of polymorphism.

4. Abstraction
Abstraction is used to hide the internal functionality of the function from the users. By applying abstraction, each object is only exposed to a high-level mechanism for using it. A method that only has a declaration and not a definition is called an abstract method. An abstract method doesn’t have anything inside the body. A class that has an abstract method is called an abstract class.


Some Things To Remember
A method inside the class without self can only use class attributes.
Class and instance attributes are both accessible using the object of the class.
You don't need to call the constructor __init__. It is automatically called at the time of object creation.
A child class can access all the attributes of the parent class, but it does not happen vice versa.
To access a protected member, we need to use _ at the time of accessing it through an object or class member.
You can’t create objects for abstract classes


reference:https://medium.com/pythoneers/a-quick-look-at-object-oriented-programming-oop-in-python-975fc3cb9618
