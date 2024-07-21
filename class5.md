### Class 5
**Topic:** Logical Operators and Looping

#### Logical Operators
**Questions:**

1. What are logical operators in JavaScript? Provide examples.
2. Explain the use of the `&&`, `||`, and `!` operators with examples.

**Coding Questions:**

1. Write a JavaScript function that uses the `&&` operator to check if two conditions are true.
    ```javascript
    function checkConditions(a, b) {
        return a > 0 && b > 0;
    }
    console.log(checkConditions(5, 10)); // true
    ```

2. Create a JavaScript function that uses the `||` operator to check if at least one of two conditions is true.
    ```javascript
    function checkAnyCondition(a, b) {
        return a > 0 || b > 0;
    }
    console.log(checkAnyCondition(-5, 10)); // true
    ```

#### Looping
**Questions:**

1. Explain the `for` loop in JavaScript with an example.
2. Describe the `while` loop and provide an example.
3. What is a `do-while` loop? Provide an example.
4. How do the `map`, `filter`, and `reduce` methods work in JavaScript? Provide examples.
5. Explain the difference between `for...in` and `for...of` loops with examples.
6. What is the `forEach` method in JavaScript and how does it work?

**Coding Questions:**

1. Write a JavaScript program that uses a `for` loop to print numbers from 1 to 10.
    ```javascript
    for (let i = 1; i <= 10; i++) {
        console.log(i);
    }
    ```

2. Create a JavaScript function that uses a `while` loop to print the first 5 even numbers.
    ```javascript
    function printEvenNumbers() {
        let i = 0;
        let count = 0;
        while (count < 5) {
            if (i % 2 === 0) {
            console.log(i)
            }
        }
    }
3.Array Methods
 * Map 