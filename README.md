# React Todo App with API

1. Short Project Description:
   Experience productivity redefined with our React Todo App with API integration. This feature-packed application not only allows you to manage your to-dos efficiently but also boasts advanced functionalities for seamless task handling.

2. Project Links:

   - [DEMO LINK](https://baraban2003.github.io/react_todo-app-with-api/)

3. Key Features:
   Toggling Todo Status
   Effortlessly toggle the completed status of your todos with intuitive interactions:

- Gracefully cover todos with a loader overlay during API response wait times.
- Instantly reflect status changes on API success.
- Receive a user-friendly Unable to update a todo notification in case of API errors.

Toggle the completed status of all todos with the toggleAll checkbox:

- Dynamically update the toggleAll button with an active class only if all todos are completed.
- One-click toggling changes the status for all todos, mimicking individual updates.
- Efficiently manage API requests, sending updates only for todos with changed statuses.

Renaming a Todo
Easily edit todo titles with a few simple actions:

- Activate the edit form on double-click, replacing the title and remove button.
- Save changes seamlessly on form submission (press Enter) or when the field loses focus (onBlur).
- Cancel editing on Esc key keyup event or if the new title is the same as the old one.
- Delete the todo if the new title is empty, replicating the x button's functionality.
- Display a loader during API response wait times for title changes.
- Update the todo title on success and notify users of errors with Unable to update a todo or deletion error messages.

Technologies Used:
Revolutionize your development experience with the latest technologies:

- React v18.2.0
- React DOM v18.2.0
- Classnames
- Node-sass
- TypeScript

4. Manual for Starting the Project (Using Webpack):

- Clone the repository to your local machine.
- Navigate to the project directory using the command line.
- Install project dependencies using npm install.
- Run the development server with npm start.
- Access the application in your browser at http://localhost:3000.
- Get ready to streamline your task management with our cutting-edge React Todo App!