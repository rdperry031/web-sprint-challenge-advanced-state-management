# Interview Answers
Be prepared to demonstrate your understanding of this week's concepts by answering questions on the following topics. These will not be counted as a part of your sprint score but will be helpful for preparing you for your endorsement interview, and enhancing overall understanding.

1. What problem does the context API help solve?

Context allows values to be passed to different components without having to resort to prop drilling.

2. In your own words, describe `actions`, `reducers` and the `store` and their role in Redux. What does each piece do? Why is the store known as a 'single source of truth' in a redux application?

actions: objects that are used to send data to the store and change the state

reducers: functions that take an action and the current state and return a new state 

store: The store is a variable that takes in a reducer that represents the state of the entire application. The store is a 'single source of truth' in that each application only has one store.

3. What does `redux-thunk` allow us to do? How does it change our `action-creators`?

`redux-thunk` allows action creators to perform asynchronous API calls

4. What is your favorite state management system you've learned and this sprint? Please explain why!
