### Class 14

**Topic:** Hoisting + Closures

**Content:**

- Hoisting concept
- Rearrange top
- Closures

**Questions:**

1. What is hoisting in JavaScript? Explain with an example.
2. Define closures and provide an example of how they work.

**Coding Questions:**

1. Write a JavaScript function to demonstrate hoisting.

   ```javascript
   console.log(hoistedVar); // undefined
   var hoistedVar = "I am hoisted";

   hoistedFunction(); // I am a hoisted function

   function hoistedFunction() {
     console.log("I am a hoisted function");
   }
   ```

2. Create a closure that allows you to increment a counter.

   ```javascript
   function createCounter() {
     let count = 0;
     return function () {
       count++;
       return count;
     };
   }

   const counter = createCounter();
   console.log(counter()); // 1
   console.log(counter()); // 2
   ```

**References:**

- [Closures in JavaScript](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Closures)
- [Hoisting references](https://www.programiz.com/javascript/hoisting)

---
