# JS Promises

**What are the three states of a Promise?**

Pending: Initial State, before the Promise succeeds or fails
Resolved: Completed Promise
Rejected: Failed Promise

**How do promises seek to resolve the issues of "callback hell"?**
 Promises seek to resolve the issue of callback hell by being able to chain different promises so it basically has a fall back for multiple scenarios.
 Chaining is one of the best features of Promises.


**What is the difference between .then() and .catch()?**
The then( ) method is called after the Promise is resolved. Then we can decide what to do with the resolved Promise.
What if the Promise fails? Then, we need to use the catch( ) method.
So if the promise gets rejected, it will jump to the catch( ) method and this time we will see a different message on the console.

link for lab

 https://kylemhanna.github.io/GregsList/