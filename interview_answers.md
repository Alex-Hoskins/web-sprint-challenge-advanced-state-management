# Interview Answers
Be prepared to demonstrate your understanding of this week's concepts by answering questions on the following topics. These will not be counted as a part of your sprint score but will be helpful for preparing you for your endorsement interview, and enhancing overall understanding.

1. What problem does the context API help solve?

    Context API solves the communication problem, as it it a tool that can specifically communicate state easily to a lot of components.

2. In your own words, describe `actions`, `reducers` and the `store` and their role in Redux. What does each piece do? Why is the store known as a 'single source of truth' in a redux application?

    Actions are functions that can be invoked which will produce a digestible object for a reducer. There can also be asynchronous actions that trigger a variety of other actions. 

    Reducers manage and manipulate the state of the application. Functions that are going to change state should be within the reducer. The is the data bank for the application where our global state can live.

    The store is a communication tool that allows components to have access to state and functions like dispatch.

3. What does `redux-thunk` allow us to do? How does it change our `action-creators`?

    Thunk allows us to have asynchronous actions and allows our actions to be more versatile. Within our actions file we can now manage a variety of actions.

4. What is your favorite state management system you've learned and this sprint? Please explain why!

    I enjoy using redux as it is a whole system that works together. I have the most experience using these tools so for now it is a matter of comfort. However, I like the simplicity the at context api brings to the communication system and can see myself making a switch to that once I am more familiar with the tool.