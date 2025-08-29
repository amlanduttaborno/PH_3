1. Difference between getElementById, getElementsByClassName, and querySelector / querySelectorAll:

getElementById selects a single element by its unique id and getElementsByClassName selects all elements with a specific class name.
querySelector selects the first element that matches a CSS selector and querySelectorAll selects all elements matching a CSS selector.


2. How do you create and insert a new element into the DOM?

We can use document.createElement('tagName') to create an element and then insert it's properties using append method.

3. What is Event Bubbling and how does it work?

Event bubbling is when an event starts at the target element and then bubbles up to its ancestors in the DOM tree, triggering event handlers on each parent unless stopped.


4. What is Event Delegation in JavaScript? Why is it useful?

Event delegation is attaching a single event listener to a parent element to handle events for its children. It’s useful for efficiency and for handling dynamically added elements.


5. Difference between preventDefault() and stopPropagation():

preventDefault() stops the default browser action.
stopPropagation() stops the event from bubbling up to parent elements.