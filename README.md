State: The data that represents the current state of your application. It's stored in a single object called the store.
Actions: Plain JavaScript objects that describe the changes you want to make to the state. They're like commands or requests.
Reducers: Pure functions that take the current state and an action as input and return a new state. They're responsible for updating the state based on the action.
Store: The central object that holds the application's state. It dispatches actions and calls reducers to update the state.


Dispatch

Dispatch is a function used to send actions to the Redux store. When you dispatch an action, it triggers the appropriate reducer to update the state.


useSelector

useSelector is a React hook provided by react-redux that allows you to access the current state of a Redux store within a functional component. It takes a selector function as an argument, which defines how to extract the desired part of the state.
