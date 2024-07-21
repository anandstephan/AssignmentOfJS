### Class 16

**Topic:** JavaScript Form Events + Mouse Events

**Content:**

- Form Events:
  - `input`
  - `change`
  - `submit`
- Mouse Events:
  - `mouseover`
  - `mouseout`
  - `mousedown`
  - `mouseup`
  - `click`
  - `dblclick`

**Questions:**

1. Explain the use of form events (`input`, `change`, `submit`) in JavaScript with examples.
2. Describe how mouse events (`mouseover`, `mouseout`, `click`, `dblclick`) work and provide examples.

**Coding Questions:**

1. Write a JavaScript function that changes the background color of an input field when the user focuses on it and reverts when it loses focus.

   ```javascript
   const inputField = document.getElementById("inputField");

   inputField.addEventListener("focus", () => {
     inputField.style.backgroundColor = "yellow";
   });

   inputField.addEventListener("blur", () => {
     inputField.style.backgroundColor = "";
   });
   ```

2. Create a JavaScript function that displays an alert when a button is double-clicked.

   ```javascript
   const button = document.getElementById("alertButton");

   button.addEventListener("dblclick", () => {
     alert("Button double-clicked!");
   });
   ```

**References:**

- [W3Schools: JavaScript Event Examples](https://www.w3schools.com/js/js_events_examples.asp)

---
