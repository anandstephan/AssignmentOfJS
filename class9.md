### Class 9

**Topic:** DOM + BOM Introduction

**Content:**

- DOM:
  - createElement
  - append
  - appendChild
  - getElementById
  - getElementByClassName

**Questions:**

1. What is the DOM and why is it important in web development?
2. Explain the difference between `append` and `appendChild` methods.
3. How do you select an element by its ID and by its class name? Provide examples.

**Coding Questions:**

1. Write a JavaScript function that creates a new `<p>` element with text content and appends it to the body.

   ```javascript
   function addParagraph() {
     const p = document.createElement("p");
     p.textContent = "This is a new paragraph.";
     document.body.appendChild(p);
   }
   addParagraph();
   ```

2. Create a JavaScript function that changes the text content of an element with a specific ID.
   ```javascript
   function changeText(id, newText) {
     const element = document.getElementById(id);
     if (element) {
       element.textContent = newText;
     }
   }
   changeText("myElement", "New Text Content");
   ```

**References:**

- [MDN: Document Object Model (DOM)](https://developer.mozilla.org/en-US/docs/Web/API/Document_Object_Model)

---
