# React static list of TODOs
- Replace `<your_account>` with your Github username in the [DEMO LINK](https://<your_account>.github.io/react_static-list-of-todos/)
- Follow the [React task guideline](https://github.com/mate-academy/react_task-guideline#react-tasks-guideline)

## Task
By using [todos.js](./src/api/todos.js) and [users.js](./src/api/users.js) as
modules to your React application, create and display a list of all the TODO
items. Alongside each item display information about the user it belongs to.

Create and use three components: `TodoList` (for the whole list), `TodoItem`
(for a single TODO item), and `User` (for displaying information about a user).
`TodoList` should display a list of `TodoItem`s; each `TodoItem` must display
the basic info about an item as well as the `User` the item belongs to. You can
choose yourself what exact information you want to present and how.

1. Create a `preparedTodos` array of `todos` with a `user` property added to each `todo`. Place it in the `App.js`
1. Create a component `TodoList` accepting an array of `preparedTodos` and displaying them as a list
1. Create a component `Todo` accepting a `todo` object and displaying its name, `completed` status and `User`
1. Create a component `User` accepting a `user` object and displaying its name with some styling