# React 19 useEffect Performance Issue

This repository demonstrates a common performance issue in React 19 related to the `useEffect` hook.  The provided `MyComponent` exhibits unnecessary re-renders due to the effect running on every state change, even when the dependency array is not specified correctly.

The `bug.jsx` file shows the problematic implementation. The solution, shown in `bugSolution.jsx`, demonstrates how to use the dependency array effectively to control when the effect runs.

## Setup

1. Clone this repository
2. Navigate to the directory: `cd react-useEffect-performance`
3. Install dependencies: `npm install`
4. Run the app: `npm start`