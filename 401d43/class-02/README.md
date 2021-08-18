# Readings: Express
-----------------------

### Review, Research, and Discussion

1. What’s the difference between PUT and PATCH?
   PUT uses the request URI to replace the resource, PATCH directly modifies the resource.

2. Provide links to 3 services or tools that allow you to “mock” an API for development like json-server
  - https://swagger.io/tools/swagger-inspector/
  - https://httpie.io/
  - https://www.postman.com/

3. Compare and contrast Swagger and APIDoc.js 1 Which HTTP status codes should be sent with each type of (un)successful API call?
  400 = Bad request.
  401 = Failed auth.
  404 = Page or user not found.


4. Compare and contrast SOAP and ReST

  |                     | SOAP         | REST                         |
  | :------------------ | :----------: | -----------:                 |
  |  What is it?        | A protocol   | A architectural pattern      |
  |  How does it work?  | uses service interfaces to expose its functionality to client applications  | uses Uniform Service locators to access to the components on the hardware device |
  |  Compatible with    | XML           | plain text, XML, HTML, JSON |

  credit(https://www.guru99.com/comparison-between-web-services.html)


### Vocabulary Terms

Web Server - Software + hardware that accepts requests via HTTP
Express - A framework for building servers and APIs
Routing - The process of selecting a path for traffic in a web server.
WRRC - Web Request Response Cycle


### Preview

1. Which 3 things had you heard about previously and now have better clarity on?
  - CI/CD
  - TDD
  - Node
2. Which 3 things are you hoping to learn more about in the upcoming lecture/demo?
  - NPM package maintenance (enterprise level npm?)
  - Sharing NPM packages publicly
  - Code coverage
3. What are you most excited about trying to implement or see how it works?
  - CI/CD can't wait to start having pipeline issues and figuring out how to debug them.