[Back to the main page](https://github.com/NicholasCaporusso/education-oer-full-stack-development)

# 04 - Advanced JavaScript
JavaScript is a versatile programming language that plays a crucial role in web development. It enables developers to create interactive and dynamic user interfaces by manipulating the Document Object Model (DOM) and handling events. Understanding the browser environment, DOM manipulation techniques, and event handling is essential for building responsive and engaging web applications.

The browser environment consists of the window object, which represents the browser window, and the document object, which represents the web page loaded in the window. The DOM is a tree-like structure that represents the HTML elements of a web page. JavaScript provides various methods and properties to access and manipulate DOM elements, allowing developers to dynamically update the content and structure of a web page.

DOM manipulation involves accessing and modifying elements using JavaScript. This can be achieved by using methods like getElementById(), querySelector(), and querySelectorAll() to select elements based on their IDs, classes, or other attributes. Once an element is selected, its properties can be modified, such as changing its text content, adding or removing classes, or modifying its attributes. Elements can also be created dynamically using createElement() and inserted into the DOM using appendChild() or insertBefore().

Event handling is another crucial aspect of JavaScript programming. Events are actions or occurrences that happen in the browser, such as a user clicking a button, submitting a form, or pressing a key. JavaScript allows developers to attach event listeners to DOM elements using the addEventListener() method. Event listeners listen for specific events and execute corresponding functions or code blocks when those events occur. This enables interactivity and responsiveness in web applications.

JavaScript provides powerful array and object manipulation capabilities. Arrays are ordered collections of values that can be of any data type. JavaScript offers various array methods like forEach(), map(), filter(), and reduce() to iterate over arrays and perform operations on their elements. Objects, on the other hand, are unordered collections of key-value pairs. They can be used to represent complex data structures and can be manipulated using methods like Object.keys(), Object.values(), and Object.entries().

Pagination is a common feature in web applications that deal with large datasets. It involves dividing data into smaller, more manageable chunks and displaying them on separate pages. Pagination improves performance and user experience by loading data incrementally instead of loading everything at once. Implementing pagination in JavaScript typically involves fetching data from a server, updating the UI to display the current page of data, and handling user interactions to navigate between pages.


## Module contents and class plan
- Events and UI interaction
  - Introduction to events and user interaction in web development
  - Importance of handling user actions and updating the UI accordingly
  - Overview of event-driven programming in JavaScript
- The browser environment
  - Understanding the browser environment and its components
  - The Document Object Model (DOM) and its structure
  - Accessing and manipulating elements using JavaScript
  - The window object and its properties
  - The document object and its methods
- Node properties and classes
  - Introduction to DOM nodes and their properties
  - Accessing node properties such as nodeType, nodeName, and nodeValue
  - Traversing the DOM tree using parentNode, childNodes, and siblings
  - Working with element classes using classList
  - Adding, removing, and toggling classes dynamically
- Modifying the document
  - Creating and inserting elements using createElement() and appendChild()
  - Modifying element attributes using setAttribute() and getAttribute()
  - Changing element content using textContent and innerHTML
  - Removing elements using removeChild() and remove()
  - Cloning elements using cloneNode()
- Event listeners
  - Understanding event listeners and their usage
  - Attaching event listeners using addEventListener()
  - Different types of events (e.g., click, submit, keypress)
  - Event object and its properties (e.g., target, preventDefault())
  - Removing event listeners using removeEventListener()
  - Event delegation and its benefits
- More on arrays
  - Revisiting array methods and their usage
  - Iterating over arrays using forEach(), map(), and reduce()
  - Filtering arrays using filter()
  - Sorting arrays using sort()
  - Searching arrays using find() and findIndex()
  - Flattening arrays using flat() and flatMap()
- More on objects
  - Revisiting object properties and methods
  - Object destructuring and its benefits
  - Object spreading and merging using the spread operator
  - Object.entries(), Object.keys(), and Object.values()
  - Working with nested objects and accessing properties
  - Object immutability and creating copies using Object.assign() and the spread operator
- Pagination demos
  - Introduction to pagination and its importance in web development
  - Implementing pagination in a web application
  - Fetching and displaying data in chunks
  - Updating the UI based on the current page
  - Handling user interactions (e.g., next page, previous page)
  - Best practices for pagination (e.g., URL parameters, caching)
  - Real-world examples and demos of pagination in action

## Video lectures
1. [04.00 - Events and UI interaction](https://youtu.be/5NDFwimo7JQ)
2. [04.01 - The browser environment](https://youtu.be/lH1Dl7aacQ4)
3. [04.02 - Node properties and classes](https://youtu.be/k76v253-CeU)
4. [04.03 - Modifying the document](https://youtu.be/DobaXSG1-w4)
5. [04.04 - Event listeners](https://youtu.be/dIt5BQqEizE)
6. [04.05 - More on arrays](https://youtu.be/UHJKkIiyKDk)
7. [04.06 - More on objects](https://youtu.be/UnKqUHI7Hlk)
8. [04.07 - Pagination demos](https://youtu.be/ZdNk_HLNRNU)

## Resources
- Mozilla Developer Network (MDN) Web Docs
  - Events: https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Building_blocks/Events
  - The DOM: https://developer.mozilla.org/en-US/docs/Web/API/Document_Object_Model
  - Manipulating documents: https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Client-side_web_APIs/Manipulating_documents
  - Arrays: https://developer.mozilla.org/en-US/docs/Learn/JavaScript/First_steps/Arrays
  - Objects: https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Objects
- freeCodeCamp
  - Introduction to the DOM: https://www.freecodecamp.org/learn/javascript-algorithms-and-data-structures/intermediate-javascript-calorie-counter/introduction-to-the-dom
  - JavaScript DOM manipulation: https://www.freecodecamp.org/learn/javascript-algorithms-and-data-structures/intermediate-javascript-calorie-counter/
  - JavaScript events: https://www.freecodecamp.org/learn/javascript-algorithms-and-data-structures/intermediate-javascript-calorie-counter/events
  - JavaScript arrays: https://www.freecodecamp.org/learn/javascript-algorithms-and-data-structures/basic-javascript/store-multiple-values-in-one-variable-using-javascript-arrays
  - JavaScript objects: https://www.freecodecamp.org/learn/javascript-algorithms-and-data-structures/basic-javascript/build-javascript-objects
- W3Schools
  - JavaScript events: https://www.w3schools.com/js/js_events.asp
  - DOM manipulation: https://www.w3schools.com/js/js_htmldom.asp
  - JavaScript arrays: https://www.w3schools.com/js/js_arrays.asp
  - JavaScript objects: https://www.w3schools.com/js/js_objects.asp
- The Odin Project
  - DOM manipulation and events: https://www.theodinproject.com/paths/full-stack-javascript/courses/javascript/lessons/dom-manipulation-and-events
  - Objects and object constructors: https://www.theodinproject.com/paths/full-stack-javascript/courses/javascript/lessons/objects-and-object-constructors