# Authentication

- Explain what a “Singleton” is (in Computer Science terms)
    - In software engineering, the singleton pattern is a software design pattern that restricts the instantiation of a class to one "single" instance. This is useful when exactly one object is needed to coordinate actions across the system. The term comes from the mathematical concept of a singleton.In software engineering, the singleton pattern is a software design pattern that restricts the instantiation of a class to one "single" instance. This is useful when exactly one object is needed to coordinate actions across the system. The term comes from the mathematical concept of a singleton.
- Explain how the Singleton pattern can be used with Node modules, specifically with classes
    - We need singleton when we want to make sure there is only one object instantiated. Therefore, instead of creating a new object we need to ensure the constructor was called only once and then we reuse the instance.
        - We can achieve this by refactoring our class to have:
            - hidden (private) `constructor`
            - public `getInstance` method that returns instance of the class
- If you were tasked with building a middleware system like Express uses, what approach might you take to construct/operate it?
    - I will use public method to use getInstance function to give me an open instance to the middleware.

---

- `Routing Middleware`: It is a function in Express as a way to do something before a request is processed. 
- `Dynamic Module Loading`: Dynamic loading is a mechanism by which a computer program can, at run time, load a library (or other binary) into memory, retrieve the addresses of functions and variables contained in the library, execute those functions or access those variables, and unload the library from memory.
- `Singleton Pattern`: it is a method to make sure of the instantiation of the system.
- `CRUD -> REST Method Matches`: the crud app and rest sharing the same method PUT GET CREATE DELETE
- `Mock Testing`: testing the outputs and the inputs of the functions or methods or routs to check the results.

