#### React 7 
------------------------
#### Redux , Redux-Thunk
------------------------
# State Management 
## Here's a quick summary about the redux and thunk concepts

Store: holds the state of your redux application

Dispatch: a function provided by redux to allow you to send actions to your redux state/reducers.

Payloads: The contents/message of an action. Compare it to the message of an email.

Type: The type of action being sent. Compare it to the subject of an email.

Actions: You telling redux to do something. Compare it to the email itself.

Connect: A function provided by redux which allows you to connect your react (or other framework/language) components to the redux state.

Thunk: Lib for managing async operations in redux. Another lib is redux sagas. included in your project with applyMiddleware(thunk), you can start dispatching actions asynchronously.

Reducers: Reducers defines/updates your state and responds to actions being sent to redux.

-----------------------------------------------------------------------------------------------------------------------

This App was applied from a tutorial .

UI -->> we used this lib @material-ui .

### Redux Async Data Flow 
https://redux.js.org/tutorials/fundamentals/part-6-async-logic


### Using React Hooks
useState, useEffect, and useReducer, etc.
https://dev.to/workshub/state-management-battle-in-react-2021-hooks-redux-and-recoil-2am0