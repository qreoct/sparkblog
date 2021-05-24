---
title: "Starting Out"
date: 2021-05-17T13:27:30+08:00
draft: true
---

## Create React App

```bash
npx create-react-app spark
```

### Dependencies

```bash
# for navigation and state
npm install react-router-dom
npm install redux react-redux redux-thunk redux-devtools-extension

# icons for app
npm i --save @fortawesome/fontawesome-svg-core
npm install --save @fortawesome/free-solid-svg-icons

# environment variables (development purposes)
npm install dotenv

```

## Linters and Testing
ESLint is a linting tool for identifying and enforcing code style in JavaScript.

```bash
npm install eslint --save-dev
```

`.eslintrc.js` file is a config file for ESLint.

- added `"sourceType": "module"` to eslint config 
- We use 2 spaces for indentation

## `index.html`

Setup meta tags for Facebook Open Graph

## Directory structure

### Frontend

```
node_modules // dependencies
public // html elements
build // compiled frontend
src // source code
- assets // static assets like images, logos
- components // React Components
  - Component.jsx
- pages // pages of the app
  - Page.jsx
- styles // css files
- actions // Redux actions
- reducers // Redux reducers
- services // Backend requests
- utils // miscellaneous scrips
.eslintrc.js
.gitignore
package-lock.json
package.json
README.md
```

### Backend
