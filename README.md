# Demo React Project

A tiny Create React App sandbox with one class component and one function
component.

## What it does

- `Buy` is a function component that renders a label with the background
  color it gets from props.
- `Hello` is a class component that shows state, lifecycle and list rendering:
  - it starts red and turns yellow when clicked;
  - 2 seconds after mounting, it sets a counter from 0 to 10 and takes the
    parent's color;
  - it renders a three-item list from state;
  - it logs `render` and `componentDidMount` to the console.

## Stack

React 17 and Create React App 4 (`react-scripts` 4.0.3).

## Getting started

```bash
npm install
npm start       # dev server on http://localhost:3000
npm run build   # production build in build/
```

`react-scripts` 4 runs on webpack 4, which fails on Node 17+ with
`ERR_OSSL_EVP_UNSUPPORTED`. Use Node 16, or set
`NODE_OPTIONS=--openssl-legacy-provider`.

## Context

Practice project, October 2021.
