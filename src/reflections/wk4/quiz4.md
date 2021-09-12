# UnderStanding Asynchronous Code, and API's

**1.** What is the difference between `asynchronous` code and `synchronous` code?
<!-- enter you answer in the space below -->
```
In synchronous operations tasks are performed one at a time and only when one is completed, the following is unblocked. In other words, you need to wait for a task to finish to move to the next one. In asynchronous operations, on the other hand, you can move to another task before the previous one finishes
```
**2.** What is an event listener?
<!-- enter you answer in the space below -->
```
The EventListener interface represents an object that can handle an event dispatched by an EventTarget object.
```
**3.** What does the `O` represent in the `SOLID` principles?
<!-- enter you answer in the space below -->
```
These principles are summarized by the acronym SOLID, which stands for: S: The single-responsibility principle. O: The open-closed principle. L: The Liskov substitution principle.
```
**4.** What is a callback / higher order function?
<!-- enter you answer in the space below -->
```
A higher-order function is a function that takes another function(s) as an argument(s) and/or returns a function to its callers. A callback function is a function that is passed to another function with the expectation that the other function will call it

```
**5.** What is a `promise`? How do you capture an error from a `promise`?
<!-- enter you answer in the space below -->
```
The Promise object represents the eventual completion (or failure) of an asynchronous operation and its resulting value. There are two ways in which you can handle errors in your promise chain, either by passing an error handler to then block or using the catch operator.
```
**6.** Name three processes used to make requests over `HTTP`?
<!-- enter you answer in the space below -->
```
An HTTP request is divided into three parts: Request line, header and body. An HTTP response is also divided into three parts: Status line, header and body
```
**7.** What does the `API` acronym stand for?
<!-- enter you answer in the space below -->
```
Application Programming Interface (API) Application programming interfaces, or APIs, simplify software development and innovation by enabling applications to exchange data and functionality easily and securely.
```
**8.** In the `MVC` design pattern, who is responsible for making calls to `APIs`?
<!-- enter you answer in the space below -->
```
The service is what usually does all the put post get and deletes. 

```
**9.** What is the purpose of encapsulation in programming?
<!-- enter you answer in the space below -->
```
Encapsulation can be used to hide both data members and data functions or methods associated with an instantiated class or object.

```
**10.** What is `HTTP` response code for a successful request?
<!-- enter you answer in the space below -->
```
2xx successful Usually anything in the 200 range is successful.
```
**11.** What is a 500 error?
<!-- enter you answer in the space below -->
```
The HyperText Transfer Protocol (HTTP) 500 Internal Server Error server error response code indicates that the server encountered an unexpected condition that prevented it from fulfilling the request

```