### Class 12

**Topic:** Method => Array reduce

**Content:**

- reduce()
- () => {}
- return
- return type
- Operational method, non-operational method

**Questions:**

1. What is the `reduce` method in JavaScript and how does it work?
2. Explain the difference between operational and non-operational methods with examples.

**Coding Questions:**

1. Write a JavaScript function that uses the `reduce` method to calculate the sum of all elements in an array.

   ```javascript
   const numbers = [1, 2, 3, 4];
   const sum = numbers.reduce((acc, num) => acc + num, 0);
   console.log(sum); // 10
   ```

2. Create a function that uses `reduce` to find the maximum value in an array.
   ```javascript
   const numbers = [1, 5, 3, 9, 2];
   const max = numbers.reduce(
     (acc, num) => (num > acc ? num : acc),
     numbers[0]
   );
   console.log(max); // 9
   ```

**References:**

- [Array reduce method explanation and examples](https://coursework.vschool.io/javascript-array-reduce-method)

---
