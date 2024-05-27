# Todo List Application with React Hooks

This is a simple Todo List application built with React that demonstrates the usage of various React hooks for state management, performance optimization, and code organization.

## Features

- Add, delete, and toggle completion of todos.
- Filter todos by status: All, Active, and Completed.
- State management using `useContext` and `useReducer`.
- Performance optimizations using `useCallback` and `useMemo`.
- Custom hooks for managing form input and local storage.

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/ayaandhaqane

Navigate to the project directory:

2. Navigate to the project directory:
    cd Building-a-Todo-List-Application-with-React-Hooks

3. Install the dependencies:
   npm  install

## Usage

1. Start the development server:
    npm run dev

2. Open your browser and navigate to http://localhost:5173 to see the application in action.



## Project Structure

src/components/TodoProvider/TodoContext.js: Context provider to manage the state of todos.
src/components/TodoForm.js: Component to add new todos.
src/components/TodoList.js: Component to display the list of todos.
src/components/TodoItem.js: Component to display individual todo items.
src/components/TodoFilter.js: Component to filter todos based on their status.
src/hooks/useFormInput.js: Custom hook for managing form input.
src/hooks/useLocalStorage.js: Custom hook for managing todos in local storage.

## Components

- **TodoProvider**
Provides the state and dispatch function for managing todos using useContext and useReducer.

- **TodoForm**
Allows users to add new todos. Uses useFormInput custom hook for managing input state.

**TodoList**
Displays the list of todos. Uses useMemo to memoize the filtered list of todos based on the current filter.

**TodoItem**
Displays individual todo items. Uses useCallback for event handlers to prevent unnecessary re-renders.

**TodoFilter**
Provides buttons to filter todos by their status (All, Active, Completed). Updates the filter state in the context.

**Custom Hooks**

useLocalStorage
Manages the persistence of todos in local storage, providing the initial state and a function to update the state in local storage.

## Contributing
Contributions are welcome! Please feel free to submit a pull request or open an issue if you have any suggestions or improvements.

## License
This project is licensed under the MIT License. See the LICENSE file for more details.



### Explanation

- **Features**: Lists the main features of the application.
- **Installation**: Provides steps to clone the repository, navigate to the project directory, and install dependencies.
- **Usage**: Describes how to start the development server and access the application.
- **Project Structure**: Describes the key components and their locations in the project.
- **Components**: Provides detailed descriptions of each component and their purposes.
- **Custom Hooks**: Describes the custom hooks used in the application.
- **Contributing**: Encourages contributions and provides guidance.
- **License**: Specifies the project's license.

Feel free to modify the README to fit your specific needs and project details.









