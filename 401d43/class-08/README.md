# Readings: Access Control (ACL)
-------------------------------------------------

### Review, Research, and Discussion

1. When is Basic Authorization used vs. Bearer Authorization?
  Basic authorization is used when a user first signs in to an application. Bearer authorization is used throughout the application session or when using cross-service applications.

2. What does the JSON Web Token package do?
  Handles all things to do with JWT web tokens.

3. What considerations should we make when creating and storing a SECRET?
  Rotate secrets frequently, establish a circle of trust, encrypt the data, automate password creation etc.

### Vocabulary Terms

encryption - the process of securing digital data using one or more mathematical algorithms/techniques.

token - an object which information identifing the session, user, access or any combination of these things.

bearer - ther client who owns the token

secret - a key which can be shared between a client and server

JSON Web Token - A standard for creating data whose payload holds JSON that asserts some number of claims.

### Preview

1. Which 3 things had you heard about previously and now have better clarity on?
  - JSON Web Token
  - token/bearer
  - 
2. Which 3 things are you hoping to learn more about in the upcoming lecture/demo?
  - RBAC
  - 
  - 
3. What are you most excited about trying to implement or see how it works?
  - Role-based access control