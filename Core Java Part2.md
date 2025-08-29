#### Q21: Explain the difference b/w two statements?
     1. String s = "Hello"
     2. String s = new String("Hello")
     A: In the first statement == ( assignment ) operator is used to assign a string literal to String variable s. 
        In this case. JVM first of all checks of same object is available in string constant pool . if same object 
        is available then new string is not created but a reference is created. if not then it creates new object in the constant pool.

        In Second statement new operator is used to create string object. in this case JVM will always create new object
---

#### Q22: What is the difference b/w String and StringBuffer classes?
     A: String class objects are immutable, hence their content cannot be modified. StringBuffer classe objects are mutable, so they can be modified
        Moreover the methods that directly manipulate data of the object are not present in String class. Such Methods are available in StringBuffer class.
---

#### Q23: What is the difference b/w StringBuffer and StringBuilder classes?
     A: StringBuffer is Synchronized ( reliable result )  and StringBuilder( Improved time ) is not. 
---

#### Q24: What is Object Oriented Approach?
     A: Method is which Computer system is designed using Classes and Objects.
---

#### Q25: Difference between Object Oriented programming Languages and Object based programming Languages?
     A: Object Oriented programming languages strictly follow OOps Concepts . Smalltalk, C++, Java are examples. 
        Object Based programming languages follow all features except inheritance. JavaScript, VBScript.
---

#### Q26: What is hashcode?
     A: hashcode is unique identification number allocated to the object by JVM. This hashcode number is also called reference             number which is created based on the location of the object in the memory and its unique for all the objects except for            strings . 
        Hashcode Internally represents heap memory where instance and variables are stored.
---

#### Q27: What are factory Methods?
     A: The factory method is a method that creates and returns a object to the class which it belongs. A single factory method replaces several
        constructors in the class by accepting different options from the user, while creating the object.
---

#### Q28: In how many ways can you create object in java?
     A: There are 4 Ways 
        - using new operator
             Person P=new Person();
        - Using factory Methods
             NumberFormat obj= NumberFormat.getNumberInstance();
        - using newInstance() method
             Class c = Class.forName("Employee");
             Employee obj = (Employee)c.newInstance();
        - By Cloning already available object.
---

#### Q29: What is Object Graph?
     A: Object graph is a graph showing relationships between different objects in memory.
---

#### Q30: What is anonymous inner class?
     A: It is an inner class whose name is not written in the outer class. For which only only one object is created.
---

#### Q31: What is inheritance?
     A: Deriving new classes from existing classes such that the new classes acquire all the features of existing classes is called inheritance.
---

#### Q32: Why multiple inheritance is not available in java?
     A: It leads to confusion for java program
        The programmer can acheieve multiple inheritance using interfaces.
        The programmer can achieve multiple inheritance by using multiple single inheritance.
---

#### Q33: How many types of inheritance are there?
     A: There are two types of inheritance. Java supports onlysingle inheritance.
---

#### Q36: What is coercion?
     A: Coercion is the automatic conersion between data types done by compiler

---

#### Q37: What is conversion?
     A: Conversion is the explicit change in data type specified by cast operator 
---

#### Q38: What is Method Signature?
     A: Method Signature represonts the method name alogn with method parameters.
---
