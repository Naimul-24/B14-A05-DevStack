# 🧱 DevStack Builder

A responsive Dev Stack Builder website for exploring modern technologies and creating a personal development stack. The project follows the Programming Hero A-5 requirements with a gradient brand theme, technology cards, search/filtering, stack management, responsive navigation, loading state, and toast-style feedback.

## ✨ Features

- Sticky responsive navbar with mobile hamburger menu.
- Hero section with shared orange → pink → violet gradient theme.
- 10 technology records loaded from `data.json` using the Fetch API.
- Search technologies by name, category, or description.
- Filter technologies by category.
- Add/remove technologies without duplicates.
- Remove all selected technologies at once.
- Loading state and success/warning feedback messages.
- Responsive layout for mobile, tablet, and desktop.
- Footer with Product, Company, and Legal link groups.

## 🛠️ Technologies

- HTML5
- CSS3, CSS Grid, Flexbox
- JavaScript ES6+
- JSON and Fetch API
- Git and GitHub

## 🚀 Run locally

Use VS Code Live Server or any local HTTP server. Opening `index.html` directly may block loading `data.json` in some browsers.

## React Questions

### 1. What is JSX, and why is it used in React?
JSX is a syntax that lets developers write HTML-like UI inside JavaScript. It makes React interfaces easier to read and organize.

### 2. What is the difference between props and state?
Props are values passed from a parent component to a child. State is data managed by a component that can change and trigger a UI update.

### 3. What does `useState` do?
`useState` stores changing values inside a React component. In a React version of this project, it would manage the selected technology stack and search text.

### 4. What does `useEffect` do?
`useEffect` runs side effects after rendering, such as loading `data.json` when the application starts.

### 5. Why does every `.map()` item need a unique `key`?
A unique key helps React recognize each item, track changes, and update lists efficiently.

### 6. What is conditional rendering?
Conditional rendering means showing UI based on a condition. For example, the empty stack message is shown only when no technology is selected.

### 7. How does parent-child communication work?
A parent passes data to a child through props. The child can communicate back by calling a callback function passed by the parent.

## 📌 Note

This repository contains a complete functional static implementation of the assignment UI. The data, interactions, responsive layout, loading state, and feedback behavior are included. A React/Vite migration with the official `react-toastify` package can be added if the instructor strictly requires a React runtime rather than a JavaScript implementation.
