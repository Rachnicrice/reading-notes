# Readings: Redux - Combined Reducers
-------------------------------------------------

### Review, Research, and Discussion

1. Why choose Redux instead of the Context API for global state?
  You don't need to nest components.

2. What is the purpose of a reducer?
  To manage state in Redux.

3. What does an action contain?
  A type and a payload.

4. Why do we need to copy the state in a reducer?
  Because you should never directly modify state in Redux.

### Vocabulary Terms

immutable state - State that cannot be changed or modified.

time travel in redux - Tracking all changes made to state.

action creator - A function that formats and returns an action object.

reducer - A pure function that takes in state, action and returns a new state.

dispatch - A function of the redux store which dispatches an action.

### Preview

1. Which 3 things had you heard about previously and now have better clarity on?
  - dispatch
  - reducer
  - 
2. Which 3 things are you hoping to learn more about in the upcoming lecture/demo?
  - time travel debugging
  - 
  - 
3. What are you most excited about trying to implement or see how it works?
  - Combining reducers and chaining actions!