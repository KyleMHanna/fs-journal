# Get organized and get secure #Encapsulation

## What is the purpose of Encapsulation?

The purpse of encapsulation is for security and organization. 


**What were some of the problems with closures and the underscore prefix?**
Internal properties and methods tend to change more frequently than public properties and methods.
Unfortunately for the users, many new developers are unaware of the underscore prefix convention, so may use the properties anyway.A large number of people ignore the covention and is leads to more breaking changes then necessary. 


**How do we create private variables in a ES6 Class? Why would you do this?**
class Counter {
  #count = 0

  click () {
    this.#count += 1;
  }
  getCount () {
    return this.#count.toLocaleString()
  }
}
const myCounter = new Counter();
myCounter.click();
myCounter.click();
myCounter.click();
console.log(
  myCounter.getCount()
);




link for lab 
https://kylemhanna.github.io/Vending-machine/