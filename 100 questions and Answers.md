
**100+ Node.js interview questions** covering various topics, from basics to advanced concepts.
---
 
## **Basic Node.js Questions**  
1. What is Node.js?  
1. Definition & Key Features
Node.js is an open-source (free and publicly available) and cross-platform (runs on Windows, macOS, and Linux) JavaScript runtime environment that allows JavaScript to execute outside the browser.
Built on Google’s V8 engine, it compiles JavaScript to machine code for fast execution.
It enables full-stack JavaScript development, allowing developers to use JavaScript for both frontend and backend.
2. Architecture & Performance
Single-Threaded, Event-Driven Model (Node.js uses a single thread to handle multiple requests simultaneously without waiting for one to finish before moving to the next, thanks to its event-driven architecture). It is powered by libuv, a C++ library that enables non-blocking I/O operations.
Non-Blocking I/O: Unlike traditional servers that wait for tasks to complete, Node.js delegates tasks (like database queries, file operations) and moves to the next request.
Event Loop Mechanism: The event loop listens for completed tasks and executes callback functions when data is ready, making it highly efficient.
3. Modular & Scalable Development
Uses CommonJS modules (require() & module.exports) for modularity.
Supports npm (Node Package Manager), providing access to a vast ecosystem of libraries.
Best suited for microservices architecture, breaking applications into independent services for better scalability.
4. Common Use Cases
a) Real-Time Applications
Chat Applications (WhatsApp Web, Slack) use WebSockets for instant messaging.
Live Streaming (Netflix, YouTube Live) transmits chunked data for smooth playback.
Stock Market & Multiplayer Games require real-time data updates using WebSockets.
b) Microservices & Serverless Applications
Microservices (Netflix, Uber) split applications into smaller, independent services for scalability.
Serverless Functions (AWS Lambda, Google Cloud Functions) execute code without managing servers.
c) IoT (Internet of Things)
Smart Homes (Alexa, Google Nest) process sensor data efficiently.
Wearable Tech (Fitbit, Apple Watch) requires lightweight, fast backend communication.
Industrial IoT monitors factory equipment and sensors in real time.
---
2. What are the key features of Node.js?  
3. How does Node.js differ from JavaScript in the browser?  
4. What is the role of V8 in Node.js?  
5. Explain the event-driven architecture in Node.js.  
6. What is the difference between asynchronous and synchronous programming in Node.js?  
7. What is the difference between Node.js and other backend technologies like Java or Python?  
8. What is NPM (Node Package Manager)?  
9. How do you install packages using NPM?  
10. What is the difference between dependencies and devDependencies in package.json?  
 
---
 
## **Node.js Modules & Require System**  
11. What are Node.js modules?  
12. What are CommonJS and ES modules?  
13. How do you create and export a module in Node.js?  
14. What is the difference between `require` and `import` in Node.js?  
15. What is the purpose of `module.exports` and `exports`?  
16. What are built-in modules in Node.js?  
17. Explain how you would use the `fs` module to read a file in Node.js.  
18. How do you handle module caching in Node.js?  
19. What is the difference between global and local modules in Node.js?  
20. How do you create a custom module in Node.js?  
 
---
 
## **Event Loop & Asynchronous Programming**  
21. What is the event loop in Node.js?  
22. How does the event loop work in Node.js?  
23. What is the difference between process.nextTick() and setImmediate()?  
24. What is callback hell, and how do you avoid it?  
25. What is the purpose of Promises in Node.js?  
26. How does async/await work in Node.js?  
27. What is the difference between blocking and non-blocking code?  
28. What is an event emitter in Node.js?  
29. How do you handle errors in asynchronous code in Node.js?  
30. What are Streams in Node.js?  
 
---
 
## **File System & Path Module**  
31. How do you read and write files in Node.js using the fs module?  
32. What are the different ways to read files asynchronously in Node.js?  
33. How do you check if a file exists in Node.js?  
34. What is the difference between synchronous and asynchronous file operations?  
35. How do you create and delete files in Node.js?  
36. How do you work with directories in Node.js?  
37. What is the purpose of the path module in Node.js?  
38. How do you get the current directory in Node.js?  
39. How do you join paths safely in Node.js?  
40. What is the difference between __dirname and process.cwd()?  
 
---
 
## **Networking & HTTP Server**  
41. How do you create an HTTP server in Node.js?  
42. What is the difference between HTTP and HTTPS in Node.js?  
43. What is the purpose of the http module in Node.js?  
44. How do you handle request and response in a Node.js server?  
45. How do you implement middleware in Node.js?  
46. What are the commonly used HTTP status codes in Node.js?  
47. What is CORS, and how do you handle it in Node.js?  
48. How do you parse incoming request data in Node.js?  
49. What are different ways to handle routing in Node.js?  
50. How do you create a REST API in Node.js?  
 
---
 
## **Express.js & Middleware**  
51. What is Express.js?  
52. What are the benefits of using Express.js?  
53. How do you install and set up Express.js?  
54. What are middleware functions in Express.js?  
55. What is the difference between app.use() and app.get()?  
56. How do you handle errors in Express.js?  
57. What is body-parser, and why is it used?  
58. How do you define and use routes in Express.js?  
59. What is the difference between req.params and req.query?  
60. How do you implement authentication in Express.js?  
 
---
 
## **Database Integration**  
61. What are the commonly used databases with Node.js?  
62. How do you connect Node.js to MongoDB?  
63. What is Mongoose, and how is it used?  
64. What is the difference between SQL and NoSQL databases?  
65. How do you use MySQL with Node.js?  
66. What is Sequelize, and how does it work?  
67. What are database migrations in Node.js?  
68. How do you implement transactions in MongoDB and MySQL?  
69. How do you handle database connection pooling in Node.js?  
70. What is the difference between relational and non-relational databases?  
 
---
 
## **Authentication & Security**  
71. What are different authentication strategies in Node.js?  
72. How do you implement JWT authentication in Node.js?  
73. How do you hash passwords in Node.js?  
74. What are the security best practices for Node.js applications?  
75. How do you prevent SQL injection in Node.js?  
76. How do you prevent Cross-Site Scripting (XSS) in Node.js?  
77. How do you prevent Cross-Site Request Forgery (CSRF) in Node.js?  
78. What is Helmet.js, and why is it used?  
79. How do you implement OAuth in Node.js?  
80. How do you store session data securely in Node.js?  
 
---
 
## **Performance & Optimization**  
81. How do you optimize a Node.js application for performance?  
82. What is clustering in Node.js?  
83. How do you implement worker threads in Node.js?  
84. How do you use caching in Node.js?  
85. What is load balancing, and how do you implement it in Node.js?  
86. How do you handle high concurrency in Node.js?  
87. How do you prevent memory leaks in Node.js?  
88. How do you profile and monitor a Node.js application?  
89. What is PM2, and how is it used?  
90. What is the role of the Garbage Collector in Node.js?  
 
---
 
## **Testing & Debugging**  
91. How do you debug a Node.js application?  
92. What are some common debugging tools for Node.js?  
93. How do you write unit tests in Node.js?  
94. What is Mocha, and how is it used in testing?  
95. What is Jest, and how does it work?  
96. How do you mock dependencies in Node.js tests?  
97. What are integration tests in Node.js?  
98. How do you handle errors in Node.js unit tests?  
99. What is a test-driven development (TDD) approach in Node.js?  
100. How do you use Supertest for API testing in Node.js?
