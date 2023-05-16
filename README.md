# Getting Started with Create React App

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

## Available Scripts

In the project directory, you can run:

### `npm start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

The page will reload if you make edits.\
You will also see any lint errors in the console.

[Guide](https://blog.devgenius.io/eslint-prettier-typescript-and-react-in-2022-e5021ebca2b1)

###  Setup Project and Install Eslint
```bash
npx create-react-app boilerplate-react-typescript --template typescript
npm install eslint --save-dev
npx eslint --init
```

### Configure Eslint

```bash
? How would you like to use ESLint? …
To check syntax only
▸ To check syntax and find problems
To check syntax, find problems, and enforce code style
```

```bash
? What type of modules does your project use? …
▸ JavaScript modules (import/export)
CommonJS (require/exports)
None of these
```
```bash
? Which framework does your project use? …
▸ React
Vue.js
None of these
```
```bash
? Does your project use TypeScript? ‣ No / Yes
```
Chose Browser
```bash
? Where does your code run? … (Press <space> to select, <a> to toggle all, <i> to invert selection)
✔ Browser
✔ Node
```
```bash
? What format do you want your config file to be in? …
JavaScript
YAML
▸ JSON
```
```The config that you've selected requires the following dependencies:
eslint-plugin-react@latest @typescript-eslint/eslint-plugin@latest @typescript-eslint/parser@latest
? Would you like to install them now with npm? ‣ No / Yes
```

### Configure prettier

```bash
npm install -D prettier eslint-config-prettier eslint-plugin-prettier eslint-plugin-react-hooks
```