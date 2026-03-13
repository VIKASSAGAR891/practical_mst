# React API User List

This project is a simple React application that fetches user data from a public API and displays it in a list. It demonstrates the use of React hooks for handling state and side effects, as well as basic API integration.

## API Used
https://jsonplaceholder.typicode.com/users

The application retrieves user information from this API and displays the name and email of each user.

## Folder Structure

src/
│
├── components/
│   └── Users.jsx
│
├── App.jsx
└── main.jsx

## How It Works

1. The application starts from `main.jsx`, which renders the root component `App`.
2. `App.jsx` loads the `Users` component.
3. The `Users` component uses the `useEffect` hook to fetch data from the API when the component loads.
4. The fetched data is stored using the `useState` hook.
5. The user data is displayed dynamically using the `map()` function.

## React Concepts Used

- Functional Components
- useState Hook
- useEffect Hook
- API Calls using fetch
- Dynamic Rendering using map()

## Features

- Fetches user data from an external API
- Stores API data in React state
- Dynamically renders a list of users
- Simple and modular component structure

## Possible Improvements

- Add loading state while fetching data
- Implement error handling for API requests
- Move API logic to a separate service file
- Improve UI with styling or component libraries

## How to Run the Project

Install dependencies:

npm install

Start the development server:

npm run dev
