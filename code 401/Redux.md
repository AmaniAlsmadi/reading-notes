# Readings: Redux Basic

- **Redux:** is a pattern and library for managing and updating application state, using events called "actions".
- Redux helps you manage "global" state - state that is needed across many parts of your application.

**Why Should I Use Redux?**

- The patterns and tools provided by Redux make it easier to understand when, where, why, and how the state in your application is being updated, and how your application logic will behave when those changes occur. 

**When Should I Use Redux?**

    - You have large amounts of application state that are needed in many places in the app
    - The app state is updated frequently over time
    - The logic to update that state may be complex
    - The app has a medium or large-sized codebase, and might be worked on by many people.

### **Not all apps need Redux. Take some time to think about the kind of app you're building, and decide what tools would be best to help solve the problems you're working on.**


**Libraries and Tools**

 - React-Redux
 - Redux Toolkit
 - Redux DevTools Extension


**Terms and Concepts**
- **Immutable State:** means we do not overwrite state, we replace it with a new copy with the shallow changes we make in any small operation.
        -Redux expects that all state updates are done immutably
- **Time Travel in Redux:**allows you to visit previous state (since state is immutable you can access previous iterations).
- **Action:** is an event that describes something that happened in the application.
- **Action creator:** is a function that creates and returns an action object.
- **Reducer:** The function that actually updates the state.
- **Dispatch:** Method that sends an action, using the observer pattern, we are signaling to components subscribed to that action that they should fire the internal corresponding logic.


# SUMMARY [from(redux.js.org)](https://redux.js.org/tutorials/essentials/part-1-overview-concepts#why-should-i-use-redux)
- Redux is a library for managing global application state
  - Redux is typically used with the React-Redux library for integrating Redux and React together
  - Redux Toolkit is the recommended way to write Redux logic
- Redux uses a "one-way data flow" app structure
  - State describes the condition of the app at a point in time, and UI renders based on that state
  - When something happens in the app:
     - The UI dispatches an action
     - The store runs the reducers, and the state is updated based on what occurred
     - The store notifies the UI that the state has changed
 - The UI re-renders based on the new state
- Redux uses several types of code
  - Actions are plain objects with a type field, and describe "what happened" in the app
  - Reducers are functions that calculate a new state value based on previous state + an action
  - A Redux store runs the root reducer whenever an action is dispatched