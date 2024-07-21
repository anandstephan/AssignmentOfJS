### Class 10

**Topic:** DOM Practice

**Content:**

- Hands-on DOM and multiple practice examples
- Example => header visible but not hidden
- Hide/unhide toggle password

**Questions:**

1. Describe a practical example where manipulating the DOM is useful in web development.
2. Explain how you can toggle the visibility of an element using JavaScript.

**Coding Questions:**

1. Write a JavaScript function that toggles the visibility of a password input field.

   ```javascript
   function togglePasswordVisibility() {
     const passwordField = document.getElementById("password");
     const type =
       passwordField.getAttribute("type") === "password" ? "text" : "password";
     passwordField.setAttribute("type", type);
   }
   ```

2. Create a JavaScript function that hides an element when a button is clicked.
   ```javascript
   function hideElement(id) {
     const element = document.getElementById(id);
     if (element) {
       element.style.display = "none";
     }
   }
   ```

**References:**

- Hands-on DOM and multiple practice examples

---
