1. What problem does the context API help solve?

        The Context API can wrap the entire app and data can be retrieved from the context object instead of needing to have props passed down from parent component to child component.

2. In your own words, describe `actions`, `reducers` and the `store` and their role in Redux. What does each piece do? Why is the store known as a 'single source of truth' in a redux application?

        Actions allow us to change the state in redux and reducers actually complete the logic of the action that we are declaring. The store is the data or state of the data at the current moment in time. 

        The store is known as the single source of truth so that as actions are run and the reducer completes the logic of those actions, we know exactly what the current state is of our data by looking at the redux store.

3. What is the difference between Application state and Component state? When would be a good time to use one over the other?

        Application State deals with the data for our entire application, like loading an API when a webpage loads so that the data is available from the initial state. Component state is just describing data that is used by a component within the application. 

        Like our todo list app, the toggling of completed tasks is just changing the state of the todo list component, not the entire app. Having multiple components that need to access the same data makes sense to have global application state as opposed to local component state like the todo list.

4. Describe `redux-thunk`, what does it allow us to do? How does it change our `action-creators`?

        Redux thunk allows our action creators to run asynchronously as the default redux action creators are synchronous.

5. What is your favorite state management system you've learned and this sprint? Please explain why!

        Redux to me seems that it will be very useful as the size of our applications grow. It may seem tedious now, but I think that it will be helpful in the long run to management our state.
