### Class 11

**Topic:** Method => Array (Map & Filter)

**Content:**

- Map()
- Filter()
- () => function
- return

**Questions:**

1. What is the `map` method in JavaScript and how is it used? Provide an example.
2. Describe the `filter` method and give an example of its use.
3. Explain the use of arrow functions with `map` and `filter`.

**Coding Questions:**

1. Write a JavaScript function that uses the `map` method to create a new array where each element is squared.

   ```javascript
   const numbers = [1, 2, 3, 4];
   const squared = numbers.map((num) => num * num);
   console.log(squared); // [1, 4, 9, 16]
   ```

2. Create a JavaScript function that uses the `filter` method to return an array with only the even numbers.
   ```javascript
   const numbers = [1, 2, 3, 4, 5, 6];
   const evens = numbers.filter((num) => num % 2 === 0);
   console.log(evens); // [2, 4, 6]
   ```

**References:**

- [MDN: Array.prototype.map()](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/map)
- [MDN: Array.prototype.filter()](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/filter)
- [ES6 Arrow Functions](https://www.coursework.vschool.io/es6-arrow-functions/)
