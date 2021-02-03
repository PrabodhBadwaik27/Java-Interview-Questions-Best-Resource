# Java Interview Questions Best Resource  
[Currently in Making]  
Here are the best answers for the most popular Java questions asked in interviews.  
**Pre-requisites:** Basic Java Programming, Object Oriented Concepts.  
**Expertise:** FRESHERS and EXPERIENCED PROFESSIONALS  
**Good Sources and References:** [Reference 1](https://intellipaat.com/blog/interview-question/java-interview-questions/), [Reference 2](https://www.guru99.com/java-interview-questions-answers.html) 

## Object Oriented Programming Concepts  

#### 1. Object Oriented Programming and its advantages
- OOP contributes to the development the special features namely **Inheritence**, **Encapsulation**, **Abstraction** and **Polymorphism**. The advantages of OOP are:  
  - enhances the reusability   
  - improves the readability of program  
  - follows the modular approach of development of program which helps in collaborating with distributed teams  
  - also, modular approach eases the process of modification and maintainance of code 
  - appreciates the flexibility and reliability of code
  
#### 2. Encapsulation and its advantages  
- Encapsulation is the concept of **restricting or hiding the internal characteristics** of a certain class from the other objects.  
- In order to accelerate the power of encapsulation, Java implements 4 types of access modifiers which differentiates the accessibility of their members and objects from out of the class. The access modifiers are, **public**, **protected**, **default** and **private**.
- Advantages of encapsulation are:
  - encapsulation fuels the approach of modularity of a program
  - it helps in reusability of code and hence emphasize on the *DRY (Don't Repeat Yourself) principle* of programming.
  - thus, the modification and maintainibility costs are reduced significantly
  - overall, encapsulation adds up to the flexibility of any program

#### 3. Polymosphism and its types.
- *Polymorphism* is a Greek word meaning *many forms*. As its name suggests, the concept of polymorphism means that the single method differentiated by signatures or context works in different ways.
- There are two types of Polymorphisms in Java:  
  - **Static or Compile-time Polymorphism:** If the function call or polymorphic method is resolved at the time of compilation, it is known as compile-time polymorphism.
    - **Method Overloading:** When the polymorphic methods are distinguished by its signatures *(number of parameters, type of parameters or sequence of parameters)*, such type of polymorphism is known as Method overloading.  
    - (**BONUS!** In C++, there is one more kind of static polymorphism known as **Operator overloading**. When the presence of operator shown different behavior with regards to its position and context (e.g unary and binary minus '-'), it is known as operator overloading. **Operator overloading is not supported in Java.** One of the reason for its elimination is for the sake of simplicity of language and working of JVM.    
  - **Dynamic or Run-time Polymorphism:** If the function call is resolved at the time of execution, it is known as run-time polymorphism.
    - **Method Overriding:** This type of polymorphism is implemeted within the subclasses in case of inheritance. When the **method from *subclass overrides* the implementations of the method in *parent class***, it is known as method overriding.

#### 4. Inheritence and its different approaches.
- Inheritence is the mechanism of OOP which allows developers to derive the properties of one class, also known as *parent class* to its *child classes*.
- Parent class is also known as **superclass** or **base class**; whereas, child class is termed as **subclass** or **derived class**.
- In Java, **extends** keyword is used to implement the inheritence. (Syntax: **public subclass extends superclass {}**)
- **BONUS!** Java doesn't allow programmers to declare the parent class *private* or *protected* and immediately throws the compilation error.
- In Java, there are three types of inheritence: **Single**, **Multilevel** and **Hierarchical**
- Java disregards the occurence of **Multiple** and **Hybrid** inheritence; this is due to the ambiguaty created during the run-time on call of the inherited method.

#### 5. Abstraction
- Abstraction is the fourth paradigm of OOP which facilitates to hide the implemetation details of methods of a class from the users. Abstraction allows the user to only define the methods in parent class and implement them in the subsequent child classes; and such methods are known as **abstract methods**.
- Unlike encapsulation, abstraction works at the design level of program.
- In Java, abstraction is implemeted using **abstract classes** and **interfaces**.
  - **Abstract Classes**
    - Abstract classes are the classes which contains **atleast one** *abstract method*.
    - Abstract classes are defined with keyword **abstract**.
    - They are inherited using **extends** keyword in Java.
  - **Interfaces**
    - Interfaces are the *abstract classes* which necessarily has all methods *abstract*.
    - Interfaces are defined by the keyword **interface**.
    - The implemetation of interfaces is inherited using keyword **implements**. 

 #### 6. [Copy Constructors](https://techvidvan.com/tutorials/java-copy-constructor/) 
