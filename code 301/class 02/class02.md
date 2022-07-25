# Read

1. Based off the diagram, what happens first, the ‘render’ or the ‘componentDidMount’?
-render
2. What is the very first thing to happen in the lifecycle of React?
- static getDerivedStateFromProps()
3. Put the following things in the order that they happen: componentDidMount, render, constructor, componentWillUnmount, React Updates
1.	constructor 
2.	render
3.	React Updates
4.	componentDidMount
5.	componentWillUnmount


4. What does componentDidMount do?
- invoked immediately after a component is mounted. If you need to load anything using a network request or initialize the DOM, it should go here.

# Video

1.	What types of things can you pass in the props?
- props can be any JavaScript data type from integers over objects to arrays.

2.	What is the big difference between props and state?
- Props are used to pass data from one component to another. The state is a local data storage that is local to the component only and cannot be passed to other components.

3.	When do we re-render our application?
- React schedules a render every time the state of a component changes.

4. What are some examples of things that we could store in state?
- data that matters to application 
