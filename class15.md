### Class 15

**Topic:** String method + new Date object

**Content:**

- String Methods:
  - .split()
  - .slice()
  - .replace()
  - .replaceAll()
  - .toLowerCase()
  - .toUpperCase()
  - .includes()
  - .charAt()
- Date Object:
  - new Date()
  - new Date().toLocaleString()
  - new Date().toLocaleDateString()
  - new Date().toLocaleTimeString()
  - new Date().getTime()
  - new Date().getDate()
  - new Date().getDay()

**Questions:**

1. Explain the use of the `.split()` and `.slice()` methods in JavaScript with examples.
2. How does the Date object work in JavaScript? Provide examples of its methods.

**Coding Questions:**

1. Write a JavaScript function that converts a string to lowercase and replaces all spaces with hyphens.

   ```javascript
   function convertString(str) {
     return str.toLowerCase().replace(/ /g, "-");
   }
   console.log(convertString("Hello World")); // hello-world
   ```

2. Create a JavaScript function that returns the current date and time in a readable format.
   ```javascript
   function getCurrentDateTime() {
     return new Date().toLocaleString();
   }
   console.log(getCurrentDateTime()); // Current date and time
   ```

**References:**

- [String methods](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String)
- [Date object](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Date)
