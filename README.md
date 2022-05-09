# staticVariablesMethodsAndMore

1. static keyword is non-access modifier
2. Access Modifiers are
    1. Public
    2. Private
    3. Default
    4. Protected
3. Non Access Modifiers are
    1. static
    2. final
    3. abstract
    4. synchronized
    5. transient
    6. volatile
    7. strictfp
4. static keyword can be used with class level variable, method , block , inner class
5. static keyword should not be used with local variables
6. static keyword should not be used with outer class
7. we can access static variables from class itself we need not create object of class to access static variables ,
   However for accessing non-static variables we need to create object of class
8. What is need of static variables?
    1. Memory management
9. Static variables once created are allocated in Class area, and they share themselves each time we create new object
10. Any method before which static keyword is added is called static method
11. Static methods belong to class and not an object hence we need not create object for it , we can directly access it from class level
12. Advantages for static method?
    1. Memory Management : we need not create object to access the methods
13. A static method can only access static data it cannot access non static data i.e. instance data
14. From static method we cannot make use of this and super
15. Static block executes automatically when then class is loaded in memory
16. Static block is executed before any other method
17. Before Java 7 we were able to run or print static block without main method, after Java6 we need main method to execute static blocks
18. Static members are executed top to bottom
19. Static blocks are used to execute a code which we want to run at the time of class loading
20. Static variables can be initialized in static blocks