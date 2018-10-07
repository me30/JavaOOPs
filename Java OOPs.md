# JavaOOPs

OOPs Concept :
-------------
1) Inheritance
2) Polymorphism
3) Encapsulation
4) Abstraction

1)Encapsulation :-
- Encapsulation means putting togather all variable and methods in to single unit called as class.
- Class is user define data type.

2)Inheritance:
- Inheritance is a way to reuse once written code again and again, in short inheritance means code resuablility.
- The class which is inherited is called the Base class & the class which inherits is called the Derived class. They are also called parent and child class.

3) Polymorphism:
- Polymorphism means taking many forms, where ‘poly’ means many and ‘morph’ means forms.
- It is the ability of a variable, function or object to take on multiple forms. 
- In other words, polymorphism allows you define one interface or method and have multiple implementations.
- Polymorphism in Java is of two types: 
  - a) Static Binding - Compile time polymorphism - check at complie time - function overloading
  - b) Dynamic Binding - Run time polymorphism - check at runtime - function overriding 

4) Abstraction:
- something which is unknown
- Abstract data type occurs at generic level of class.
- Abstraction apply at top level class

# Class 

class A {
   int i;
   char ch;
   
   void get(){
   }
   
   void set(){
   }
   
}


If we define object 

A a1 = new A();

so there are two type memeory allow:

stack        heap
a1     ---->  i
              ch


