# Express REST API
-------------------------------------------------

### Review, Research, and Discussion

1. Name 3 real world use cases where you’d want to change the request with custom middleware
  - For auth purposes (check if user is authenticated)
  - To add data to the req that is not sent by the user (ex. timestamp)
  - Could be used to transform data in the request to a common format for the server

2. True or false: The route handler is middleware? True

3. In what ways can a middleware function end the process and send data to the browser? By sending a response or next('with data in the parameters').

4. At what point in the request lifecycle can you “inject” middleware? Before the route logic is executed.
 
5. What can cause express to error with “Request headers sent twice, cannot start a second response” If you have multiple separate res.send() or res.status() calls in the same function.


### Document the following Vocabulary Terms

Middleware - Software that can modify requests and/or execute operations before a route is reached.
Request Object - An object sent by the client which contains all information related to the request (method, query, url, body, etc.)
Response Object - An object sent by the server which contains all information related to the processing/completion of the original request aka the server's 'response'.
Application Middleware - Middleware run at the application level of a server (i.e. before all routes)
Routing Middleware - Middleware run at the route level (i.e. before specific routes)
Test Driven Development - A software development process where test cases are written before software is fully developed. (Red <- tests failing, Green <- tests passing, Refactor <- refactor code for any failing tests).
Behavioral Testing - Behavior-driven development combines the general techniques and principles of TDD with ideas from domain-driven design and object-oriented analysis and design to provide software development and management teams with shared tools and a shared process to collaborate on software development. (Credit: https://en.wikipedia.org/wiki/Behavior-driven_development)


### Preview

1. Which 3 things had you heard about previously and now have better clarity on?
  - Test Driven Development
  - Middleware terms
  - Express
2. Which 3 things are you hoping to learn more about in the upcoming lecture/demo?
  - Behavioral Testing
  - OOP in Javascript
  - More middleware use cases
3. What are you most excited about trying to implement or see how it works?
  - More application middleware, I want to figure out how to mock middleware in server testing. (Tried this today and failed lol. Will try again tomorrow).