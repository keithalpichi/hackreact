# HackReact Workshop

A workshop demo-ing HackReact- a to-do list app for Hackreactor students. Presented on March 2nd and 4th, 2017 by [Keith Alpichi](https://linkedin/in/keithalpichi)

## Prerequisites
- React syntax
- ES6
- Unidirectional (one-way) data flow

## Learning Outcomes
- Solidifying understanding and use of ES6
- How to build a React SPA app from scratch
- React and it's functional declarative paradigm
- Debugging with React DevTools
- State vs. Props
- Introduction to `localStorage`
- Introduction to lifecycle methods
- Introduction Babel (transpiler) & Webpack (module bundler)
- Introduction to Redux and how it makes managing/editing application state easier
 - Possible workshop in the future?

## Workshop Outline
- Introduction to the HackReact app
- Produce mental model of application
- Install dependencies
- Start with one large parent component to render static content
- Add in children components to do the same
- Add in state in parent component
- Pass down state as props to appropriate child components
- Add in functions to alter the state in parent
- Pass down these functions as props to appropriate child components
- Refactor, refactor, refactor!

## Live Demo
- Fork this repo to your Github account
- Clone your forked repo
- Run `npm install`
- Start the development server with `npm run dev`

## Starting a React Project From Scratch
- Create a directory and change into it
- Run `npm init` and follow directions or `npm init -y` to use defaults
- Create necessary directories for project
- Add a `.gitignore` and include any files/folders you don't want version controlled
- Add `dependencies` and/or `devDependencies` to `package.json`
 - `react` for React
 - `react-dom` for rendering React to the DOM
 - All `babel-*` packages for transpiling ES6 to ES5 (see `package.json` for full list)
 - `webpack` for module bundling
 - `webpack-dev-server`- a dev server where builds are saved in-memory. The server will re-compile on file change eliminating the use of hard-refreshes.
- Create and configure a `webpack.config.js` according to the Webpack documentation
- Add necessary scripts into `package.json` under the `scripts` key to utilize installed packages. Scripts to consider:
 - `build`- to compile
 - `test`- to test (you'll have to install testing libraries. Jest is popular in the React community)
 - `dev`- run the webpack-dev-server
 - `start`- to run production server (you'll need to implement a web server using something like Express)

## Where to go from here?
- Implement build process to transpile and bundle into the `build` directory for production
- Implement localStorage
- Play around with the lifecycle methods by logging to the console.
- Refactor using Redux
- Implement functionality for user registration and session sign-in and sign-out so user can save his/her notes.
