# Readings: Data Modeling
-------------------------------------------------

### Review, Research, and Discussion

1. Write the following steps in the correct order:  
Ask the client if they want to sign in via a third party
Redirect to a third party authentication endpoint
Receive authorization code
Make a request to the access token endpoint
Receive access token
Register your application to get a client_id and client_secret
Make a request to a third-party API endpoint


2. What can you do with an authorization code?  
  Use it to verify a client and exchange it for the correct access token.

3. What can you do with an access token?  
  Use it to make API requests on behalf of a user and access specific parts of user data.

4. What’s a benefit of using OAuth instead of your own basic authentication?  
  You can authorize multiple applications without having to give away password data.


### Vocabulary Terms

Client ID - (CID) A unique identifier for a browser–device pair

Client Secret - A key used by the OAuth Client to authenticate to the authorization server. It is known only to the OAuth Client and the Authorization Server.

Authentication Endpoint -  Where devices make a request to be authenticated.

Access Token Endpoint - Where apps make a request to get an access token for a user. 

API Endpoint - Where requests to access resources are sent.

Authorization Code - A code that authorizes its user to perform certain actions.

Access Token - A token that contains the security credentials for a login session and identifies the user.

### Preview

1. Which 3 things had you heard about previously and now have better clarity on?
  - OAuth
  - Tokens
  - CID
2. Which 3 things are you hoping to learn more about in the upcoming lecture/demo?
  - OAuth implementation
  - JWTs
  - JWT Security Vulnerabilities
3. What are you most excited about trying to implement or see how it works?
  - Idk if I'd say I'm excited about it but it's probably useful to know how to implement OAuth is js.