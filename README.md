# React useEffect Infinite Loop Bug

This repository demonstrates a common error in React applications: creating an infinite loop within the `useEffect` hook.  The incorrect usage of `setCount(count + 1)` inside the `useEffect` hook without proper dependency management leads to a continuous state update, resulting in an infinite rendering cycle and potentially crashing the application. The solution involves correctly managing dependencies and using functional updates to avoid this issue.

## How to Reproduce

1. Clone this repository.
2. Run `npm install` to install dependencies.
3. Run `npm start` to start the development server.
4. Observe the console for errors and the component's behavior.