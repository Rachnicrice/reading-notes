# Readings: Component Lifecycle / useEffect() Hook
-------------------------------------------------

### Review, Research, and Discussion

1. Why do we not need more .html pages in a multi-page React app?
  Because React is used to build single-page applications (i.e. changes are rendered dynamically to the same page).

2. If we wanted a component to show up on every page, where would we put it and why?
  - Outside the <BrowserRouter/>
  - Inside the <BrowserRouter />, outside a <Route />
  - Inside a <Route />
  Had touble finding a clear answer on this one.

3. What does routing do with the components that were rendered when a new route is requested?
  It mounts them to the DOM. (This is totally a guess).

4. What does props.children contain?
  Any child elements defined within a component. 

5. How do useState() and this.setState() differ?
  useState() is a state hook and can be used in functional components. this.setState() can only be used in class components.


### Vocabulary Terms

State Hook - A hook that lets you add React state to functional components.

Mounting and Un-Mounting - Adding and removing elements from the DOM.

### Preview

1. Which 3 things had you heard about previously and now have better clarity on?
  - SPA
  - State Hooks
  - Mounting/Un-Mounting
2. Which 3 things are you hoping to learn more about in the upcoming lecture/demo?
  - props.children
  - nesting components
  - React Routing
3. What are you most excited about trying to implement or see how it works?
  - Passing info to nested components.