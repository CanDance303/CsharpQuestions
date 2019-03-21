# Csharp Questions
*****

1. What is a namespace?
  * A namespace is the name of your code and each project can have different namespaces as an organization method.
2. What are value types?
  * Value types can have a specific value assigned directly to them. Some examples would be: bool, int, char and float.
3.  What are reference types?
  * Reference types store references to different objects. A string is a good example of a reference type. I could lable a string as 'dog' and then write a specific code for that string under it. I could then call upon that smaller code in other parts of the project by using 'dog' rather than typing the whole code over.
4. What is an automatic property and how is it useful?
  * It makes property declaration very simple and saves a lot of time when building the code.
5. What is the purpose of **using** statement?
  * The using statement allows you specify certain objects in the code block but once they are no longer needed or there is some type of exception to that code block, the process will automaticlly end rather than you needing to write in the part of the code that will cause an exit.
6. What are dynamic type variables?
  * They are variables that would gernally cause a complier error when the code runs but it is passed over due to the use of dynamic. This would allow you to use variables that aren't declared until they are input by the user. Note: use of dynamic can result in runtime errors as the complier is bypassed.
7. What is the purpose of the **is** operator?
  * Is checks to see if different objects are compatible during runtime.
8. What are generics and how is using them useful?
  * Generics allows you to create a class of placeholders and when the code is compiled, the placeholders are replaced with their respective types. This is useful as it allows you to reuse code and is often used to make collection classes.
9. What is the scope of a public member of a class?
  * I believe this refers to different access specifiers. There are five of them and they are listed in #33.
10. Can you create a function that can accept a varying number of arguments?
  * Yes, you would use **params** to do this.
11. How do you sort an array?
  * I would use Array.Sort(NameofArray).
12. What is a nullable type and what purpose does it serve?
  * It represents any and all underlying type values. You would use this is if you're trying assign values to code where some areas may or may not have a value and if they don't, during runtime it the program will write 'null'.
13. What is an enumeration?
  * A set of named constants.
14. What is inheritance?
  * It allows you to create a secondary class that feeds off of the main class yet can be changed or extended without altering the main class.
15. Is multiple inheritance supported?
  * No.
16. What is the purpose of **as** operator?
  * It allows you to convert between similar reference types and nullable types.
17. What is an object?
  * An object can be different variables, arrays or collections in C#.
18. What is the difference between a struct and a class?
  * Structs are value types and Classes are reference types.
19. What is the difference between **continue** and **break** statements?
  * **Break** will break a loop whereas **Continue** allows you to skip over something without breaking the loop.
20. What is **this** and how is it used?
  * It is a keyword in C# and refers to the current instance of a class.
21. What is **try** and **catch** and when are they used?
  * The **try** block will run until an exception occurs or it completes its task. When the exception occurs in **try**, **catch** then comes into play and will tell the program what to do with the exception. They're used for finding exceptions and then handling those exceptions.
22. How is exception handling done?
  * Exception handling is done through the **catch** block of a **try**-**catch** code.
23. What is **finally** and what is its purpose?
  * **Finally** can be added at the end of a **try**-**catch** block and will run when the program ends (either successfully or due to an exception) as it frees up system resources.
24. List the differences between Array and ArrayList.
  * I prefer comparison lists to be in tables so please see below:

| Array        | ArrayList          |
| :-------------: |:-------------:|
| Stores one data type     | Stores different data types |
| Stores one specific item/element    | Stores any item/element      |
| Cannot accept null | Can accept null      |

25. What is an object?
  * As stated in question 17: An object can be different variables, arrays or collections in C#.
26. Define **constructor**.
  * **Constructor** is automatically created when you make a new class or struct. It lets you make default values and allows your code to be easily read.
27. When can **var** be used to declare a variable and how is the type for the variable determined?
  * You can use **var** when you want the compiler to determine the variable type. The type is determined when the code is compiled by the compiler.
28. What is an abstract class?
  * An abstract class is a class that uses the keyword abstract. This means that the abstract class of the code can only be used if another class calls upon it. If it's not called upon, then that part of the code will not run during runtime.
29. What is an interface?
  * An interface is where you can define different items or write a code that you wish to have other classes pull from.
30. What is a method?
  * A method is a block of code in a program.
31. What is a property?
  * Properties are named classes, interfaces and structures in a code. It allows for reading, writing and computing.
32. What is an access specifier?
  * An access specifier allows the code writer to define what parts of the code is accessable to different types of users during runtime.
33. What access specifiers are supported and what do they mean?
  * Private: Limits what type of code is avaible during runtime. If Class1 is Public but Class2 is Private, Class1 will not have access to Class2.
  * Public: All code is avaiable and useable.
  * Internal: If you use this, any class in your code will be able to access this portion of the code.
  * Protected: Only applies when using inheritance. Allows class to be seen by child class but no other class.
  * Protected Internal: Allows any class to access, also applies when using inheritance
34. What is a collection?
  * This is used for storing different data that you want to pull from during runtime.
35. What is a Hash Table?
  * Key/Value pairs that are organized by hash code.
