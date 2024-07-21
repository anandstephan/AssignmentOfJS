### Class 13

**Topic:** Scope in JS

**Content:**

- Local Scope
- Global Scope
- Lexical Scope

**Questions:**

1. Explain the difference between local scope and global scope with examples.
2. What is lexical scope in JavaScript?

**Coding Questions:**

1. Write a JavaScript function demonstrating local and global scope.

   ```javascript
   let globalVar = "I am global";

   function scopeTest() {
     let localVar = "I am local";
     console.log(globalVar); // I am global
     console.log(localVar); // I am local
   }

   scopeTest();
   console.log(localVar); // ReferenceError
   ```

2. Create an example to demonstrate lexical scope in JavaScript.

   ```javascript
   function outerFunction() {
     let outerVar = "I am outer";

     function innerFunction() {
       console.log(outerVar); // I am outer
     }

     innerFunction();
   }

   outerFunction();
   ```

**References:**

- [JavaScript scope](https://javascript.plainenglish.io/javascript-scope-8c8793f2ef5d)

---
