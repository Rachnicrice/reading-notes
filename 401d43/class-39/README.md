# Readings: Redux - Additional Topics
-------------------------------------------------

### Review, Research, and Discussion

1. What’s the best practice for “pre-loading” data into the store (on application start) in a Redux application?
  Fire off the async action in the component lifecycle, usually on componentWillMount.

2. When using a thunk/async action that dispatches the actual action, which do you export from your reducer? 
  The async action.

### Vocabulary Terms

middleware - software the operates between an os, database or applications.

thunk -  redux middleware that allows you to call an action creator that return a function.
