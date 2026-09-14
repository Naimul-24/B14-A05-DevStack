# 🧱 DevStack Builder

A responsive technology stack builder where developers can explore technologies and create their own stack.

## Technologies
- HTML5, CSS3, JavaScript ES6+
- JSON data loading with Fetch API
- Responsive CSS Grid and Flexbox

## Features
1. Browse and search 10 modern technologies.
2. Add and remove technologies from a personal stack.
3. Responsive gradient-themed interface with loading state.

## React Questions

### 1. What is JSX?
JSX is a syntax that lets us write HTML-like UI inside JavaScript. React uses it to describe what the interface should look like.

### 2. Props vs state
Props are data passed from a parent to a child. State is data managed inside a component that can change over time.

### 3. What does useState do?
`useState` stores changing data in a React component, such as the selected technology list.

### 4. What does useEffect do?
`useEffect` runs side effects such as fetching JSON data after a component renders.

### 5. Why does map need a key?
A unique key helps React identify each list item and update only what changed.

### 6. What is conditional rendering?
Conditional rendering means showing different UI based on a condition. For example, the empty stack message appears when no technology is selected.

### 7. Parent and child communication
A parent passes data to a child through props. A child can send information back by calling a callback function received through props.

## Run locally
Open `index.html` with a local server, such as VS Code Live Server, so that `data.json` can be fetched.
