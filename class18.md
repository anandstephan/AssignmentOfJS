### Class 18

**Topic:** setTimeout + setInterval

**Content:**

- `setTimeout`
- `setInterval`

**Questions:**

1. What is the `setTimeout` function in JavaScript and how is it used? Provide an example.
2. Describe the `setInterval` function and give an example of its use.

**Coding Questions:**

1. Write a JavaScript function that displays a message after 3 seconds using `setTimeout`.

   ```javascript
   setTimeout(() => {
     console.log("This message is displayed after 3 seconds");
   }, 3000);
   ```

2. Create a JavaScript function that updates the current time every second using `setInterval`.
   ```javascript
   setInterval(() => {
     const now = new Date();
     console.log(now.toLocaleTimeString());
   }, 1000);
   ```

**References:**

- [GeeksforGeeks: JavaScript setTimeout and setInterval](https://www.geeksforgeeks.org/javascript-settimeout-setinterval)
