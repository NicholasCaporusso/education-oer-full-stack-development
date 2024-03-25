[Back to the main page](https://github.com/NicholasCaporusso/education-oer-full-stack-development)

# 06 - Working with RESTful APIs
RESTful APIs (Representational State Transfer Application Programming Interfaces) have become a fundamental component of modern web development, enabling seamless communication between clients and servers. In a client-server architecture, clients (such as web browsers) send requests to servers, which process the requests and send back responses. This communication is typically facilitated by the HTTP (Hypertext Transfer Protocol), which defines a set of rules for data exchange.

To develop and test RESTful APIs effectively, developers rely on various tools like Postman, cURL, and Insomnia. These tools allow developers to send HTTP requests, view responses, and debug API endpoints easily.

One of the key aspects of RESTful APIs is the use of JSON (JavaScript Object Notation) for data exchange. JSON is a lightweight, human-readable format that represents data as key-value pairs and arrays. It has become the de facto standard for transmitting data between clients and servers due to its simplicity and compatibility with various programming languages.

Asynchronous JavaScript And XML (AJAX) is a technique that enables web pages to update content dynamically without requiring a full page refresh. AJAX relies on the XMLHttpRequest (XHR) object to send asynchronous requests to the server and retrieve data in the background. This allows for a more responsive and interactive user experience.

HTTP requests are at the core of client-server communication. RESTful APIs typically utilize different HTTP methods to perform CRUD (Create, Read, Update, Delete) operations on resources. The most common HTTP methods are GET (retrieve data), POST (create a new resource), PUT (update an existing resource), and DELETE (remove a resource). Each request includes headers and an optional request body, which contains data sent to the server.

Working with JSON data is a crucial skill for developers working with RESTful APIs. Retrieving JSON data from an API endpoint, parsing it, and manipulating it using JavaScript are common tasks. Developers need to be familiar with JSON syntax, data structures, and techniques for handling JSON data effectively.

To simplify the process of making asynchronous requests to APIs, developers often use libraries like jQuery and Axios. jQuery provides a set of AJAX methods (such as $.ajax, $.get, and $.post) that abstract away the complexities of the XMLHttpRequest object. Axios is a popular JavaScript library that offers a more modern and promise-based approach to making HTTP requests. Both libraries simplify the process of sending requests, handling responses, and dealing with errors.

## Module contents and class plan
- Client-server communication
  - Introduction to client-server architecture
  - Explanation of how clients (e.g., web browsers) communicate with servers
  - Overview of HTTP protocol and its role in client-server communication
  - Discussion of request-response cycle and how data is exchanged between client and server
- Useful tools
  - Introduction to Postman, a popular tool for testing and developing APIs
  - Demonstration of how to use Postman to send HTTP requests and view responses
  - Overview of other useful tools for API development, such as cURL and Insomnia
  - Discussion of the importance of using tools to test and debug APIs
- JavaScript Object Notation (JSON)
  - Explanation of what JSON is and its role in data exchange between client and server
  - Overview of JSON syntax and structure, including objects, arrays, and data types
  - Demonstration of how to create and parse JSON data using JavaScript
  - Discussion of the advantages of using JSON over other data formats, such as XML
- Asynchronous JavaScript And XML (AJAX)
  - Introduction to AJAX and its role in creating dynamic web pages
  - Explanation of how AJAX allows web pages to update content without refreshing the entire page
  - Overview of the XMLHttpRequest (XHR) object and how it is used to make asynchronous requests to the server
  - Demonstration of how to use AJAX to retrieve data from a server and update the web page dynamically
- HTTP requests
  - Overview of the different types of HTTP requests (GET, POST, PUT, DELETE, etc.)
  - Explanation of the purpose and usage of each type of request
  - Discussion of the structure of an HTTP request, including headers and request body
  - Demonstration of how to send HTTP requests using JavaScript and AJAX
- Working with JSON (practice)
  - Hands-on exercise to practice working with JSON data
  - Demonstration of how to retrieve JSON data from an API endpoint using AJAX
  - Practice parsing and manipulating JSON data using JavaScript
  - Discussion of common challenges and best practices when working with JSON data
- jQuery (and Axios) Asynchronous APIs
  - Introduction to jQuery and its role in simplifying AJAX requests
  - Overview of jQuery's AJAX methods ($.ajax, $.get, $.post, etc.) and how to use them
  - Demonstration of how to use jQuery to make asynchronous requests to an API endpoint
  - Introduction to Axios, a popular JavaScript library for making HTTP requests
  - Comparison of jQuery and Axios and their respective advantages and use cases
  - Practice using both jQuery and Axios to make asynchronous requests to an API and handle responses

  
## Video lectures
1. [06.00 - Client-server communication](https://youtu.be/Le0SLa351NY)
2. [06.01 - Useful tools](https://youtu.be/DxfZpdjuJa0)
3. [06.02 - JavaScript Object Notation](https://youtu.be/vDA-m6Y91wA)
4. [06.03 - Asynchronous Javascript And XML](https://youtu.be/yuqmYD-VdKM)
5. [06.04 - HTTP requests](https://youtu.be/3hBD4OhvoyI)
6. [06.05 - Working with JSON (practice)](https://youtu.be/Q4xVYs4F9Js)
7. [06.06 - jQuery (and Axios) Asynchronous APIs](https://youtu.be/lkLfOmNSqxs)

## Resources
- Client-server communication:
  - MDN Web Docs: Client-Server Overview (https://developer.mozilla.org/en-US/docs/Learn/Server-side/First_steps/Client-Server_overview)
  - Coursera: Client-Server Communication (https://www.coursera.org/lecture/web-development/client-server-communication-bfk0r)
  - Khan Academy: HTTP and HTML (https://www.khanacademy.org/computing/computers-and-internet/xcae6f4a7ff015e7d:the-internet/xcae6f4a7ff015e7d:web-protocols/a/http-and-html)
- Useful tools:
  - Postman Learning Center (https://learning.postman.com/)
  - Coursera: Postman: The Complete Guide - REST API Testing (https://www.coursera.org/learn/postman-rest-api-testing)
  - freeCodeCamp: Learn API Testing with Postman (https://www.freecodecamp.org/news/learn-api-testing-with-postman/)
- JavaScript Object Notation (JSON):
  - MDN Web Docs: Working with JSON (https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Objects/JSON)
  - Codecademy: Learn JSON (https://www.codecademy.com/learn/learn-json)
  - freeCodeCamp: JavaScript Algorithms and Data Structures Certification - JSON APIs and AJAX (https://www.freecodecamp.org/learn/javascript-algorithms-and-data-structures/json-apis-and-ajax/)
- Asynchronous JavaScript And XML (AJAX):
  - MDN Web Docs: AJAX (https://developer.mozilla.org/en-US/docs/Web/Guide/AJAX)
  - Codecademy: Learn AJAX (https://www.codecademy.com/learn/learn-ajax)
  - Udacity: Intro to AJAX (https://www.udacity.com/course/intro-to-ajax--ud110)
- HTTP requests:
  - MDN Web Docs: HTTP (https://developer.mozilla.org/en-US/docs/Web/HTTP)
  - Codecademy: Learn HTTP (https://www.codecademy.com/learn/learn-http)
  - freeCodeCamp: APIs and Microservices Certification - Basic Node and Express (https://www.freecodecamp.org/learn/apis-and-microservices/basic-node-and-express/)
- Working with JSON (practice):
  - JSONPlaceholder: Free Fake REST API (https://jsonplaceholder.typicode.com/)
  - Public APIs: A collective list of free APIs for use in software and web development (https://github.com/public-apis/public-apis)
- jQuery (and Axios) Asynchronous APIs:
  - jQuery Learning Center: Ajax (https://learn.jquery.com/ajax/)
  - Codecademy: Learn jQuery (https://www.codecademy.com/learn/learn-jquery)
  - Axios Documentation (https://axios-http.com/docs/intro)
  - Udemy: Axios Crash Course (https://www.udemy.com/course/axios-crash-course/)