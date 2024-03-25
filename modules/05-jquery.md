[Back to the main page](https://github.com/NicholasCaporusso/education-oer-full-stack-development)

# 05 - jQuery
jQuery is a powerful and widely-used JavaScript library that simplifies HTML document traversing, event handling, animation, and Ajax interactions. It provides a concise and easy-to-learn syntax that enables developers to perform complex tasks with minimal code. This summary covers the key aspects of jQuery, including its basics, selectors, events, methods, DOM manipulation, and a practical application of building a todo list.

jQuery is a fast, small, and feature-rich library that can be included in an HTML file using a Content Delivery Network (CDN) or by downloading the library. To start using jQuery, you need to wrap your code inside the $(document).ready(function() { ... }); block, which ensures that the code runs only after the DOM is fully loaded.

The basic syntax of jQuery is $(selector).action(), where $ is a shorthand for jQuery, (selector) is used to find HTML elements, and action() is the method performed on the selected elements. jQuery provides a wide range of selectors to target elements based on their tag name, class, id, attribute, or hierarchy. You can use multiple selectors separated by commas and also apply hierarchy selectors like parent > child or ancestor descendant.

jQuery makes it easy to handle user interactions through its event methods. Common events include click, dblclick, mouseenter, mouseleave, keypress, and submit. Event handlers can be attached to elements using the $(selector).event(function() { ... }) syntax. The on() method is useful for handling multiple events or dynamically added elements.

jQuery provides a rich set of methods to manipulate HTML elements, traverse the DOM, and modify element properties. Methods like text(), html(), val(), attr(), css(), addClass(), and removeClass() are used to get or set element content, attributes, and styles. Traversal methods such as parent(), children(), siblings(), and find() help navigate the DOM tree. jQuery also allows chaining methods for more concise code. DOM manipulation methods like append(), prepend(), after(), before(), remove(), and empty() enable the creation, insertion, and removal of elements. The clone() method is used to duplicate elements, while replaceWith() and replaceAll() replace elements with new ones.

Building a todo list is a practical application of jQuery concepts. The application involves creating an input field and a button to add new tasks, displaying tasks in a list with checkboxes and delete buttons, and using event handlers to toggle task completion and remove tasks. The application can be enhanced by implementing localStorage to persist tasks across browser sessions.

## Module contents and class plan
- Introduction to jQuery
  - jQuery is a fast, small, and feature-rich JavaScript library
  - Simplifies HTML document traversing, event handling, animating, and Ajax interactions
  - Provides a simple API that works across multiple browsers
- Getting Started with jQuery
  - Include the jQuery library in your HTML file
  - Use a Content Delivery Network (CDN) or download the library
  - Start using jQuery by adding `$(document).ready(function() { ... });`
- jQuery Syntax
  - Basic syntax: `$(selector).action()`
  - `$` is a shorthand for `jQuery`
  - `(selector)` finds HTML elements
  - `action()` is performed on the selected elements
- jQuery and Selectors
  - Select elements by tag name, class, id, or attribute
  - Examples: `$("p")`, `$(".class")`, `$("#id")`, `$("[attribute]")`
  - Use multiple selectors: `$("p, .class, #id")`
  - Hierarchy selectors: `$("parent > child")`, `$("ancestor descendant")`
- jQuery and Events
  - Handle user interactions with event methods
  - Common events: `click`, `dblclick`, `mouseenter`, `mouseleave`, `keypress`, `submit`
  - Attach event handlers using `$(selector).event(function() { ... })`
  - Use `on()` method for multiple events or dynamic elements
- jQuery Methods
  - Manipulate HTML elements with various methods
  - Examples: `text()`, `html()`, `val()`, `attr()`, `css()`, `addClass()`, `removeClass()`
  - Traverse the DOM with methods like `parent()`, `children()`, `siblings()`, `find()`
  - Chain methods for concise code: `$(selector).method1().method2()`
- DOM Manipulation
  - Create, insert, and remove elements
  - Methods: `append()`, `prepend()`, `after()`, `before()`, `remove()`, `empty()`
  - Clone elements with `clone()`
  - Replace elements with `replaceWith()` or `replaceAll()`
- Application - Todo List
  - Build a functional todo list application using jQuery
  - Create an input field and a button to add new tasks
  - Display tasks in a list with checkboxes and delete buttons
  - Use event handlers to toggle task completion and remove tasks
  - Implement localStorage to persist tasks across browser sessions

## Video lectures
1. [05.00 - jQuery](https://youtu.be/a9GYacHesEA)
2. [05.01 - Getting started with jQuery](https://youtu.be/B1LPaoqrTfE)
3. [05.02 - jQuery syntax](https://youtu.be/lP9y1USYSQ4)
4. [05.03 - jQuery and selectors](https://youtu.be/2LE18ArmWf8)
5. [05.04 - jQuery and events](https://youtu.be/bphOf0O_r8k)
6. [05.05 - jQuery methods](https://youtu.be/_8A8vn-Q8M4)
7. [05.06 - DOM manipulation](https://youtu.be/EO4b4Alce4Y)
8. [05.07 - Application - todo list](https://youtu.be/CdZ4I9f_Sl0)

## Resources
- Introduction to jQuery and Getting Started
  - W3Schools jQuery Tutorial: https://www.w3schools.com/jquery/
  - Codecademy's Learn jQuery Course: https://www.codecademy.com/learn/learn-jquery
  - jQuery Fundamentals (Book): http://jqfundamentals.com/
- jQuery Syntax and Selectors
  - jQuery Documentation - Selecting Elements: https://api.jquery.com/category/selectors/
  - jQuery Selectors (Tutorialspoint): https://www.tutorialspoint.com/jquery/jquery-selectors.htm
  - jQuery Selectors (OSS Blog): https://oss.maxcdn.com/libs/jquery/2.1.3/jquery.min.js
- jQuery Events
  - jQuery Documentation - Events: https://api.jquery.com/category/events/
  - jQuery Event Methods (W3Schools): https://www.w3schools.com/jquery/jquery_events.asp
  - Introduction to jQuery Events (DigitalOcean): https://www.digitalocean.com/community/tutorials/introduction-to-jquery-events
- jQuery Methods and DOM Manipulation
  - jQuery Documentation - Manipulation: https://api.jquery.com/category/manipulation/
  - jQuery HTML/CSS Methods (W3Schools): https://www.w3schools.com/jquery/jquery_dom_get.asp
  - jQuery DOM Manipulation (Tutorialspoint): https://www.tutorialspoint.com/jquery/jquery-dom.htm
- Todo List Application
 - Building a Todo List with jQuery (OpenClassrooms): https://openclassrooms.com/en/courses/3523231-building-a-to-do-list-with-jquery
 - Creating a Simple Todo List with jQuery (Teachable Machine): https://teachablemachine.withgoogle.com/blog/creating-a-simple-todo-list-with-jquery
- Additional Resources:
  - FreeCodeCamp's jQuery Tutorials: https://www.freecodecamp.org/learn/front-end-libraries/jquery/
  - edX's "HTML5 and CSS Fundamentals" Course (includes jQuery): https://www.edx.org/course/html5-and-css-fundamentals
  - Khan Academy's jQuery Course: https://www.khanacademy.org/computing/computer-programming/html-js-jquery