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
