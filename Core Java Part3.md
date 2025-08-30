
#### Q41: What is the difference method overloading and method overriding?
    A:  Method Overloading:
          - Same method name but different method signature( Different return type, Different no of parameters , Difference in Parameter type and theier               order
          - This happens with methods in same class
          - JVM decides which method to call based on the method signature 
          - Method Overloading is code refinement

          Method Overridding:
            - Same method signature ( name , Number of params , type of params and return type all should be same )
            - Method overriding is done from super class and subclass
            - JVM decision on which method to call is based on the data type of the caller (object)
            - Method Overriding is a code replacement
            
---

#### Q42: Can you override Private methods?
    A: No, Overriding is only possible to the methods and variables available ot subclass, Private methods are not available to subclass.
            
---

#### Q43: Can we take Private methods and Final Methods Same?
    A: Yes, Java Compiler assigns the value for private methods at the time of compilation. Private methods cannot be modified at runtime.
       This is the same case with Final methods Neither Private methods or Final methods can be overriden.
---

#### Q44: What is final?
    A: Final Keyword is used in two ways:
            1. It is used to declare constants
            2. It is used to prevent inheritance
---

#### Q45: What is the difference b/w Static polymorphism and Dynamic polymorphism?
    A: Dynamic polymorphism is a polymorphism exhibited at runtime, Here compiler doesnot undestands which methods to call at compile time
       only JVM decidies based on the reference type.
       Methods overloading and Method overriding using instance methods are examples

       Static polymorphism is polymorphism exhibited at compile time, Java compiler knows which method to call.
       Method overloading and Method overriding using static methods
       
---

#### Q46: What is the difference b/w primitive datatype and advanced data type?
    A: Primitive datatypes represent single value. Advanced datatype represent multiple values. Also methods are not available to primitive data types.
       In case of advanced data types several methods are available for several operations.
       
---

#### Q47: What is implicit casting?
    A: Automatic casting done by java compiler internally is called implicit casting. Implicit casting is done to convert lower data type to higher           data type.
       
---

#### Q48: What is explicit casting?
    A: Casting done by programmer using casting operator is called explicit casting. This is compulsory while converting higher data type to lower data          type
       
---

#### Q49: What is generalization and specialization?
    A: Generalization is the process where subclass is promoted to super class and hence becomes more general. Generalizations needs widening or 
       up-casting.

       Specialiazation is a phenomenon where super class is narrowed down to subclass. This needs to down-casting.
       
---

#### Q50: What is widening and narrowing?
    A: Converting lower data type to higher data type is called widening and converting higher data type to lower is called narrowing.
       Widening is a safe operation. Narrowing is unsafe hence programmer should explictly use cast operator       
---

