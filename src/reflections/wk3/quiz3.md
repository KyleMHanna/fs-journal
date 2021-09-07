# Application Architecture, MVC Design Pattern

**1.** What are the Pillars of Object Oriented Programming (`OOP`)?
<!-- enter you answer in the space below -->
```
encapsulation, inheritance, and polymorphism.
```
**2.** How would you access the `name` of the below object using the `property` variable?
```js
let staff = {
  name: "Tim",
  age: 26,
  job: "Code Monkey"
  }
let property = 'name'
```
<!-- enter you answer in the space below -->

```
let property=staff.name
```
**3.** What is Encapsulation?
<!-- enter you answer in the space below -->
```
In object-oriented programming, encapsulation refers to the bundling of data with the methods that operate on that data, or the restricting of direct access to some of an object's components
```
**4.** What does the S stand for in the `SOLID` principles?
<!-- enter you answer in the space below -->
```
The single-responsibility principle
```
**5.** What the difference between a `class` and an instance of a `class`?
<!-- enter you answer in the space below -->
```
A class is a blueprint which you use to create objects. An object is an instance of a class - it's a concrete 'thing' that you made using a specific class. So, 'object' and 'instance' are the same thing, but the word 'instance' indicates the relationship of an object to its class.
```
**6.** What is a `Proxy` object?
<!-- enter you answer in the space below -->
```

The proxy object in JavaScript is used to define the custom behavior of fundamental operations (e.g. property lookup, assignment, enumeration, function invocation, etc). Syntax: var p = new Proxy(target, handler)
```

**7.** What is the purpose of the `MVC` pattern?
<!-- enter you answer in the space below -->
```
Model–view–controller (usually known as MVC) is a software design pattern commonly used for developing user interfaces that divide the related program logic into three interconnected elements.
```
**8.** What is the job of the `Controller` in the `MVC` Pattern?
<!-- enter you answer in the space below -->
```
Inputs something on screen. If you were to think of it as a video game it would be the inputs of the actual controller. 
```

**9.** What is the job of the `Service` in `MVC`?
<!-- enter you answer in the space below -->
```
The service is the check all the values and make sure they are protected. 
A service layer is an additional layer in an ASP.NET MVC application that mediates communication between a controller and repository layer. The service layer contains business logic. In particular, it contains validation logic
```
**10.** What is the job of the `Model` in `MVC`?
<!-- enter you answer in the space below -->
```
In a Model-View-Controller (MVC) application, the Model is responsible for the application's state and non-UI specific behavior. In simple applications, there may be just one kind of model class that is used by persistence, presentation, and any business logic.
```

