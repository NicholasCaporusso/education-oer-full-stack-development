[Back to the main page](https://github.com/NicholasCaporusso/education-oer-full-stack-development)

# 08 - Routing with Express
Express.js is a popular web application framework for Node.js that simplifies the process of building server-side applications. It provides a robust set of features for creating APIs, handling HTTP requests, and managing routes.

To begin with Express, you need to have Node.js installed on your system. Create a new project directory and initialize a package.json file using `npm init`. Install Express by running `npm install express`. Set up a basic Express server by requiring the Express module, creating an instance of the Express application, defining routes, and starting the server.

Express allows you to serve static files, such as HTML, CSS, images, and client-side JavaScript, directly from your server. Use the `express.static` middleware to specify the directory where your static files are located. Express will automatically serve these files when requested by the client.

Routing is a fundamental concept in Express. It allows you to define how your application responds to client requests based on the URL and HTTP method. Express provides a simple and intuitive way to define routes using the `app.get()`, `app.post()`, `app.put()`, `app.delete()`, and other HTTP method functions. You can define route handlers that receive the request and send the appropriate response. Express also supports route parameters, query strings, and modular organization of routes using the Express Router.

Middleware functions are a key feature of Express. They sit between the request and the response, allowing you to modify the request or response objects, perform additional processing, or terminate the request-response cycle. Express middleware can be classified into application-level, router-level, and error-handling middleware. You can write custom middleware functions or use third-party middleware packages for tasks such as logging, authentication, parsing request bodies, and handling errors.

Express has a rich ecosystem of plugins, extensions, and middleware that enhance its functionality. Some popular packages include `body-parser` for parsing request bodies, `morgan` for logging HTTP requests, `cookie-parser` for handling cookies, `express-session` for managing user sessions, and `helmet` for adding security headers. These packages can be easily integrated into your Express application using `npm install`.

When building Express applications, follow best practices to ensure maintainability, scalability, and security. Organize your code into modular routes and controllers, use environment variables for configuration, handle errors gracefully, and implement proper authentication and authorization mechanisms. Additionally, consider using a template engine like EJS or Pug for rendering dynamic views, and follow security best practices to protect your application from common vulnerabilities.

## Module contents and class plan
- Server-side programming with Express
  - Introduction to server-side programming
  - Overview of Express.js framework
  - Advantages of using Express for server-side development
  - Setting up a basic Express server
- Getting started with Express
  - Installing Node.js and Express
  - Creating a new Express project
  - The basic structure of an Express application
  - Configuring package.json and installing dependencies
  - Writing your first Express server
  - Running the server and testing with a web browser
- Working with static files
  - Serving static files with Express
  - Using the express.static middleware
  - Configuring static file paths
  - Serving static files from multiple directories
  - Best practices for organizing static files
- Routing
  - Understanding routing in Express
  - Defining routes for different HTTP methods (GET, POST, PUT, DELETE)
  - Creating route handlers
  - Parsing request parameters and query strings
  - Sending responses (JSON, HTML, etc.)
  - Organizing routes using the Express Router
- Express middleware
  - Understanding middleware in Express
  - Types of middleware (application-level, router-level, error-handling)
  - Writing custom middleware functions
  - Using third-party middleware packages
  - Common middleware use cases (logging, authentication, error handling)
  - Configuring middleware order and execution

## Video lectures
1. [08.00 - Server-side programming with Express](https://youtu.be/XIgj3pi8Jno)
2. [08.01 - Getting started with Express](https://youtu.be/1BYSFk734Pg)
3. [08.02 - Working with static files](https://youtu.be/Qp0LHZ5oBV8)
4. [08.03 - Routing](https://youtu.be/cGVMheKfHMM)
5. [08.04 - Express middleware](https://youtu.be/8jEDpWw1r14)

## Resources
- Mozilla Developer Network (MDN) - Express/Node.js
  - Getting started with Express: https://developer.mozilla.org/en-US/docs/Learn/Server-side/Express_Nodejs/Introduction
  - Serving static files in Express: https://developer.mozilla.org/en-US/docs/Learn/Server-side/Express_Nodejs/Displaying_data/Serving_static_files_in_Express
- freeCodeCamp - Node.js and Express.js Course
  - YouTube playlist: https://www.youtube.com/watch?v=Oe421EPjeBE
  - Includes tutorials on Express basics, routing, middleware, and more
- The Odin Project - NodeJS
  - Introduction to Express: https://www.theodinproject.com/courses/nodejs/lessons/introduction-to-express
  - Covers Express setup, routing, and middleware
- Codecademy - Learn Express
  - Interactive course on Express: https://www.codecademy.com/learn/learn-express
  - Covers Express basics, routing, and middleware
- Express.js official documentation
  - Getting started guide: https://expressjs.com/en/starter/installing.html
  - Routing: https://expressjs.com/en/guide/routing.html
  - Using middleware: https://expressjs.com/en/guide/using-middleware.html
- Node.js official documentation
  - Guide: https://nodejs.org/en/docs/guides/
  - Includes tutorials on getting started with Node.js and Express
- OpenJS Foundation - Express.js Learning Path
  - A curated list of resources to learn Express: https://openjsf.org/express-learning-path/
- Web.dev - Express.js Tutorial
  - A beginner-friendly tutorial on Express: https://web.dev/learn/express/