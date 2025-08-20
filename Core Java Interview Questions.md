#### Q1: What is Unicode System?
      A: Unicode system is encoding standard that provides unique number for every character. no matter what the platform, program or the language is . Unicode uses 2 bytes to represent a single character.
      
---

#### Q2: What is the difference between float and double?
      A: Float can represnt 7 digit accurately after decimal point whereas double can represent 15 digits accurately after decimal point.

---

#### Q3: What is the difference between ``` print() ``` and ``` println()``` ?
      A: print()  prints the result  and returns the cursor in the same line next to the end of the result.
         println() prints the result and throws the cursor to the next line.
---

#### Q4: What happens if ``` String args [] ``` is not written in ```main()``` ?
      A: When main() method is written without String args [] as 
         public static void main()
         The code will compile but JVM cannot run the code becoz it cannot recognise the main() method as the method where it should start the execution of java program.
         JVM always looks for main() method with String args [] parameter ( String type array as a parameter ).
         
---

#### Q5: What is the difference b/w ``` include ``` and  ``` import ``` ?
      A: #include directive makes C/C++ compiler Standard library. Copy the code from the headers files to the program. As a result program size increases, thus wasting memory and processors time.
         import statement makes JVM to go to standard Library, execute the code there and substite the result to the program. Here no code is copied and hence no waste of memory and processors time.
         import is efficient than include.
---

#### Q6: What is JIT compiler ?
      A: JIT compiler is part of JVM which increases the speed of java program.
---
