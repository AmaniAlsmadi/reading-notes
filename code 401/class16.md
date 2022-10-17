# Advanced State with Reducers

1. How can we ensure that an effect hook runs only once?

   pass an empty array as an argument to the useEffect hook

   ```javascript
   useEffect(() => {
     callBackFunction();
   }, []);
   ```

2. Can useState() update more than one state variable at the same time?

   No, actually,useState replaces the whole object instead of updating and it will re-render the component every time you call it.


3. Is useState() synchronous?

   No,  useState is an asynchronous hook

## Vocabulary Terms

- State Hook: useState is a Hook that lets you add React state to function components.

- Component Lifecycle: The lifecycle of a component is the series of methods that are invoked in different stages of the component's existence.

- useEffect(): The Effect Hook, `useEffect`, adds the ability to perform side effects from a function component. It serves the same purpose as `componentDidMount`, `componentDidUpdate`, and `componentWillUnmount` in React classes, but unified into a single API.

- Reducer: A reducer is a function that determines changes to a state. It uses the action it receives to determine this change. and re-render the component every time you call it.