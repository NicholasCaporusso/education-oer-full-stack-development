[Back to the main page](https://github.com/NicholasCaporusso/education-oer-full-stack-development)

# MongoDB
NodeJS and MongoDB are popular technologies used in modern web development for building scalable and efficient server-side applications. NodeJS is a JavaScript runtime built on Chrome's V8 JavaScript engine, allowing developers to use JavaScript on the server-side. MongoDB is a NoSQL database that provides a flexible and scalable solution for storing and retrieving data.

To get started with NodeJS and MongoDB, you need to set up your development environment. Install NodeJS on your system and make sure you have access to the Node Package Manager (npm). MongoDB can be installed locally or you can use a cloud-based service like MongoDB Atlas. Once the environment is set up, you can create a new NodeJS project and install the required dependencies, including the MongoDB driver.

To connect your NodeJS application to MongoDB, you need to use the MongoDB driver. The driver provides a set of APIs to interact with the database. You can establish a connection to MongoDB using a connection string that specifies the database host, port, and authentication credentials. Once the connection is established, you can perform database operations.

CRUD stands for Create, Read, Update, and Delete, which are the four basic operations performed on data in a database. MongoDB provides methods to perform these operations:
- Create: Insert new documents into a collection using `insertOne()` or `insertMany()` methods.
- Read: Retrieve documents from a collection using `find()` or `findOne()` methods. You can also apply query operators to filter the results based on specific conditions.
- Update: Modify existing documents in a collection using `updateOne()` or `updateMany()` methods. You can use update operators like `$set`, `$inc`, `$push`, etc., to specify the changes to be made.
- Delete: Remove documents from a collection using `deleteOne()` or `deleteMany()` methods based on the specified criteria.

MongoDB Atlas is a fully-managed cloud database service provided by MongoDB. It offers a convenient way to host and manage MongoDB databases in the cloud. With MongoDB Atlas, you can create clusters, configure database users and network access, and connect your NodeJS application securely. MongoDB Atlas provides features like automatic scaling, backup and restore, monitoring, and performance optimization.

MongoDB is a document-oriented database, which means it stores data in flexible, JSON-like documents. Data modeling in MongoDB involves designing the structure of your documents and collections based on your application's requirements. You can nest documents, use arrays, and leverage the flexibility of the document model.

Querying data in MongoDB is done using query operators and projection. Query operators allow you to specify conditions to match documents, such as equality, comparison, logical operators, and more. Projection lets you specify which fields to include or exclude from the result set. You can also sort and limit the results.

NodeJS has several popular web frameworks like Express, Koa, and NestJS that make it easier to build web applications. These frameworks provide abstractions and utilities for handling routes, middleware, and database integration. They often have plugins or libraries that simplify working with MongoDB, such as Mongoose, an Object Data Modeling (ODM) library for MongoDB and NodeJS.

## Module contents and class plan
- NodeJS and MongoDB
  - Introduction to NodeJS and its advantages for server-side development
  - Overview of MongoDB, a NoSQL database
  - Setting up NodeJS and MongoDB environment
  - Connecting NodeJS application with MongoDB using the MongoDB driver
  - Basic MongoDB commands for database operations
- CRUD Operations with MongoDB
  - Understanding CRUD (Create, Read, Update, Delete) operations
  - Creating a new document using `insertOne()` and `insertMany()`
  - Reading documents using `find()`, `findOne()`, and query operators
  - Updating documents using `updateOne()`, `updateMany()`, and `$set` operator
  - Deleting documents using `deleteOne()` and `deleteMany()`
  - Using projection to specify fields to return in the result
  - Sorting and limiting the result set
- Working with MongoDB Atlas
  - Introduction to MongoDB Atlas, a fully-managed cloud database service
  - Setting up a MongoDB Atlas account and creating a new cluster
  - Configuring database user and network access
  - Connecting NodeJS application to MongoDB Atlas using connection string
  - Performing CRUD operations on MongoDB Atlas
  - Importing and exporting data using MongoDB Atlas tools
  - Monitoring and performance optimization with MongoDB Atlas

## Video lectures
TBD


## Resources
- MongoDB University
  - M001: MongoDB Basics: https://university.mongodb.com/courses/M001/about
  - M220JS: MongoDB for JavaScript Developers: https://university.mongodb.com/courses/M220JS/about
  - M320: Data Modeling: https://university.mongodb.com/courses/M320/about
- freeCodeCamp - MongoDB and Mongoose Courses
  - MongoDB Tutorial - CRUD Operations: https://www.youtube.com/watch?v=-56x56UppqQ
  - MongoDB Tutorial for Beginners: https://www.youtube.com/watch?v=CyTWPr_WwdI
- The Odin Project - NodeJS and MongoDB
  - Introduction to MongoDB: https://www.theodinproject.com/courses/nodejs/lessons/introduction-to-mongodb
  - CRUD Operations with MongoDB: https://www.theodinproject.com/courses/nodejs/lessons/crud-operations-with-mongodb
- Codecademy - Learn Node.js Course
  - Covers MongoDB integration with Node.js: https://www.codecademy.com/learn/learn-node-js
- MongoDB Official Documentation
  - Getting Started: https://docs.mongodb.com/manual/tutorial/getting-started/
  - CRUD Operations: https://docs.mongodb.com/manual/tutorial/query-documents/
  - MongoDB Atlas: https://docs.atlas.mongodb.com/getting-started/
- Node.js Official Documentation
  - MongoDB Driver: https://nodejs.org/en/docs/guides/getting-started-with-mongodb/
- W3Schools - MongoDB Tutorial
  - MongoDB Tutorial for beginners: https://www.w3schools.com/mongodb/
- Tutorials Point - MongoDB Tutorial
  - MongoDB Tutorial: https://www.tutorialspoint.com/mongodb/index.htm
- Introduction to MongoDB - edX Course
  - Free course on MongoDB basics: https://www.edx.org/course/introduction-to-mongodb
- MongoDB Crash Course - YouTube Tutorial
  - Crash course on MongoDB for beginners: https://www.youtube.com/watch?v=-56x56UppqQ