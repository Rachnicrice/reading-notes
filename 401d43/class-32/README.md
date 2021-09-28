# Readings: Context API - Behaviors
-------------------------------------------------

### Review, Research, and Discussion

1. When you have multiple contexts, what component type should you use (class/function) and why?
  I would say functional components, but not 100% sure on this.

2. What are some good use cases for using the Context API for global state?
  Storing general application data that will be used for multiple different components, ie. user display preferences, cart on a shopping platform etc.

3. How can you best test context?
  Don't mock context in testing and make sure it renders as expected. (BDD).

### Vocabulary Terms

context - A place to store props (like the Redux store).

useContext() - A react hook used to pull context into a component.

static context - I assume this is the same as Java, so static context means that there is only one context and it is shared across all instances of a component.

### Preview

1. Which 3 things had you heard about previously and now have better clarity on?
  - useContext()
  - 
  - 
2. Which 3 things are you hoping to learn more about in the upcoming lecture/demo?
  - static context
  - testing context
  - 
3. What are you most excited about trying to implement or see how it works?
  - Looking forward to combining auth and context.