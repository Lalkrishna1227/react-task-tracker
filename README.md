# React Task Tracker

A small, focused task tracker built with React and TypeScript to demonstrate clean component structure, hooks-based state management, and persistence without a backend.

## Features

- Add, complete, and delete tasks
- Filter tasks by All / Active / Completed
- Sort tasks by newest
- Tasks persist in localStorage between sessions
- Fully typed with TypeScript interfaces

## Tech Stack

React 18, TypeScript, Create React App, CSS

## Getting Started

```
npm install
npm start
```

The app runs at http://localhost:3000.

## Project Structure

```
src/
  App.tsx      Main component: state, handlers, rendering
  App.css      Styling
  index.tsx    App entry point
```

## Why this project

Built to demonstrate end-to-end ownership of a small front-end feature: component design, state management with hooks, TypeScript typing, and a simple persistence layer. These are the same patterns used to build larger production UIs.
