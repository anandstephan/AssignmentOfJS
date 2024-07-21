---

### Class 8
**Topic:** Function + Events

**Content:**
- Function keyword
- return keyword
- local variable
- arguments
- calling
- invoking
- fat arrow function

**Questions:**

1. Define a function in JavaScript and explain its components.
2. What is the difference between function declaration and function expression?
3. Explain the concept of the return keyword with an example.
4. How do fat arrow functions differ from regular functions in terms of `this` context?

**Coding Questions:**

1. Write a JavaScript function that calculates the sum of two numbers.
    ```javascript
    function sum(a, b) {
        return a + b;
    }
    console.log(sum(2, 3)); // 5
    ```

2. Create a fat arrow function that takes an array of numbers and returns an array with each number doubled.
    ```javascript
    const doubleArray = (arr) => arr.map(num => num * 2);
    console.log(doubleArray([1, 2, 3])); // [2, 4, 6]
    ```

**References:**
- [MDN: Functions](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Functions)

---
