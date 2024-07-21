### Class 17

**Topic:** JavaScript Keyboard Events + Clipboard Events + Drag Events

**Content:**

- Keyboard Events:
  - `keyup`
  - `keydown`
- Clipboard Events:
  - `copy`
  - `cut`
  - `paste`
- Drag Events:
  - `drag`
  - `drop`
  - `dragstart`
  - `dragend`

**Questions:**

1. What are keyboard events in JavaScript? Explain with examples.
2. Describe clipboard events (`copy`, `cut`, `paste`) and provide examples of their use.
3. Explain how drag and drop functionality is implemented in JavaScript.

**Coding Questions:**

1. Write a JavaScript function that logs a message to the console when a key is pressed.

   ```javascript
   document.addEventListener("keydown", (event) => {
     console.log(`Key pressed: ${event.key}`);
   });
   ```

2. Create a JavaScript function that allows an element to be dragged and dropped to a new location.

   ```javascript
   const draggable = document.getElementById("draggable");
   const dropzone = document.getElementById("dropzone");

   draggable.addEventListener("dragstart", (event) => {
     event.dataTransfer.setData("text/plain", draggable.id);
   });

   dropzone.addEventListener("dragover", (event) => {
     event.preventDefault();
   });

   dropzone.addEventListener("drop", (event) => {
     event.preventDefault();
     const id = event.dataTransfer.getData("text/plain");
     const element = document.getElementById(id);
     dropzone.appendChild(element);
   });
   ```

**References:**

- [W3Schools: JavaScript Event Examples](https://www.w3schools.com/js/js_events_examples.asp)

---
