# Readings: Redux - Asynchronous Actions
-------------------------------------------------

### Review, Research, and Discussion

1. How granular should your reducers be?
  "Reducer functions should only depend on their state and action arguments" ~ https://redux.js.org/style-guide/style-guide

2. Pro or Con – multiple reducers can “fire” when a commonly named action is dispatched.
  I would say a pro, definitely.

3. Name a strategy for preventing the above.
  Name action in a reducer specific way if you only want it to trigger one reducer.

### Vocabulary Terms

store - Where state is kept and maintained in Redux.

combined reducers - The act of putting multiple reducers together into one giant switch case. This is what allows multiple reducers to respond to a commonly named action.

### Preview

1. Which 3 things had you heard about previously and now have better clarity on?
  - Common actions
  - Combined reducers
  - 
2. Which 3 things are you hoping to learn more about in the upcoming lecture/demo?
  - Granular (what does this term mean?)
  - Async actions
  - 
3. What are you most excited about trying to implement or see how it works?
  - Hooking up redux with a back end.