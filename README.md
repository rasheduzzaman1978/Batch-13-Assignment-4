### 1. What is the difference between getElementById, getElementsByClassName, and querySelector / querySelectorAll?

Answer: These are DOM selection methods in JavaScript, used to select HTML elements. The main differences are given below:
(i) getElementById() selects one element by ID.
(ii) getElementsByClassName() selects elements by class name.
(iii) querySelector() selects first matching element using CSS selector.
(iv) querySelectorAll() selects all matching elements using CSS selector. It returns NodeList, multiple elements, static list (does not auto update) and supports forEach() method.

### 2. How do you create and insert a new element into the DOM?

Answer: To create and insert a new element into the DOM, I can use these main methods:
i. document.createElement()
ii. appendChild()
iii. append()
iv. prepend()
v. insertBefore()

### 3. What is Event Bubbling? And how does it work?

Answer: Event Bubbling is when an event starts from the target element and then bubbles up to its parent elements.
It moves: Child-> Parent -> Grandparent -> document

If anyone click the button, the event happens in this order:
a. button (child)
b. div (parent)
c. body
d. document

This is called bubbling.

### 4. What is Event Delegation in JavaScript? Why is it useful?

### 5. What is the difference between preventDefault() and stopPropagation() methods?