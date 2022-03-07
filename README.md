# React Demystified 🦄

## What is a React 🥴

https://github.com/destinio/react-basic

<img src="https://i.giphy.com/media/Yq2SKEsscV85lPRJdu/giphy.gif" width="400px" />

**A JavaScript library for building user interfaces**

> Is React a Library or a Framework?

**Library** 👇

**"React provides a declarative API so that you don’t have to worry about exactly what changes on every update."**

### Reconciliation

https://reactjs.org/docs/reconciliation.html

**We'll talk more about Frameworks letter.** 🤪

## ReactDOM though whats that things deal?? 🤷‍♂️

https://reactjs.org/docs/react-dom.html

**"If the React element was previously rendered into container, this will perform an update on it and only mutate the DOM as necessary to reflect the latest React element."**

**_more on DOM later..._**

## Getting set up 🛠

**So, let's see it in action...** 🔬

### OLD REACT ☠️

### Add the following to the end of your `index.html` `<head>` section

https://unpkg.com

```html
<script src="https://unpkg.com/react@17.0.2/umd/react.development.js"></script>
<script src="https://unpkg.com/react-dom@17.0.2/umd/react-dom.development.js"></script>
```

#### #ERROR >

`Uncaught SyntaxError: Unexpected token '<'`

A classic ☝️

This means you are trying to use JSX which is not part or react or JavaScript!!

## So what gives 🤔

### Babel

https://babeljs.io/

```html
<script src="https://unpkg.com/@babel/standalone/babel.min.js"></script>

<!-- Default <script type="text/javascript"> -->
<script type="text/babel">

```

### Other `<script>` types

https://developer.mozilla.org/en-US/docs/Web/HTML/Element/script

- `<script type="text/javascript">`
- `<script type="application/json">`
- `<script type="module">`

### DOM Elements vs React Elements

https://reactjs.org/docs/react-api.html#createelement

### The Virtual DOM vs real browser DOM

https://developer.mozilla.org/en-US/docs/Web/API/Document_Object_Model/Introduction

https://reactjs.org/docs/faq-internals.html#what-is-the-virtual-dom

"The virtual DOM (VDOM) is a programming concept where an ideal, or “virtual”, representation of a UI is kept in memory and synced with the “real” DOM by a library such as ReactDOM. **This process is called reconciliation.**"

## Other set up options 🪛

### On-line editors 🕸

- https://codepen.io/
- https://codesandbox.io/

## NODE Options

### Builders / **Frameworks**

#### parcel js

- https://parceljs.org/ and many other like it
  - https://parceljs.org/recipes/react/#typescript
  - https://parceljs.org/getting-started/webapp/#installation

#### Create React App

**How we do it at JHT**

https://create-react-app.dev/

##### TypeScript CRA

https://create-react-app.dev/docs/adding-typescript/

`npx create-react-app my-app --template typescript`

or

`yarn create react-app my-app --template typescript`

**Install the following dependencies if using TypeScript**

`npm install --save typescript @types/node @types/react @types/react-dom @types/jest`

#### React Frameworks

- https://nextjs.org/
- www.gatsbyjs.com
- https://remix.run/

## Resources

- https://reactjs.org/docs/getting-started.html#online-playgrounds
- https://github.com/enaqx/awesome-react

## Markdown Chrome tool

- https://chrome.google.com/webstore/detail/markdown-viewer/ckkdlimhmcjmikdlpkmbgfkaikojcbjk/related?hl=en-US
