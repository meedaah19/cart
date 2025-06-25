Redux is a state management. Redux is here to help us with aoo wide state, state that is affecting the entire app.
It helps us to avoid prop drilling.

Redux Toolkit enables you to write predictable and testable code to make your app work as expected.
You can't use both redux and react context in the same component.

npm install @reduxjs/toolkit is used to install redux toolkit

For redux to work, we have a center store, subscribe to the store, so whenever things change in the store, your component will get notice.

Reducer function is responsible for making changes in the store, and updating the store.

Action is use to dispatch and forward info from component to reducer function.

redux.createStore is use to create store

A reducer function should have an input that has an old state(current state) and dispatched action to give us new state. It must be a pure function. It must pure side-effect, synchronous function.

The subscriber function will be subcribe by using store.getState().

To subcribe to the store will use store.subscribe(subscriber function).

We also have store.dispatch that has a type object.