### Class 7

**Topic:** Conditions => if else + switch case + ternary

**Content:**

- if else
- switch case
- ternary

**Questions:**

1. Explain the use of `if...else` statements in JavaScript with examples.
2. Describe how `switch` cases work and provide an example.
3. What is a ternary operator and how is it used? Provide an example.

**Coding Questions:**

1. Write a JavaScript function that takes a number and returns whether it is even or odd using `if...else`.

   ```javascript
   function checkEvenOdd(num) {
     if (num % 2 === 0) {
       return "Even";
     } else {
       return "Odd";
     }
   }
   console.log(checkEvenOdd(4)); // Even
   ```

2. Create a JavaScript function that assigns a grade based on a given score using a `switch` case.

   ```javascript
   function getGrade(score) {
     let grade;
     switch (true) {
       case score >= 90:
         grade = "A";
         break;
       case score >= 80:
         grade = "B";
         break;
       case score >= 70:
         grade = "C";
         break;
       case score >= 60:
         grade = "D";
         break;
       default:
         grade = "F";
     }
     return grade;
   }
   console.log(getGrade(85)); // B
   ```

3. Use the ternary operator to create a function that returns "Adult" if age is 18 or older, otherwise "Minor".
   ```javascript
   function checkAge(age) {
     return age >= 18 ? "Adult" : "Minor";
   }
   console.log(checkAge(20)); // Adult
   ```

**References:**

- [MDN: Conditional Statements](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/if...else)



