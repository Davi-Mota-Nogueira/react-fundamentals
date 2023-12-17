# React Foundations to operate Next.js (some important notes)

## Building blocks of a web application

### There are a few things you need to consider when building modern applications. Such as:

- User Interface - how users will consume and interact with your application.
- Routing - how users navigate between different parts of your application.
- Data Fetching - where your data lives and how to get it.
- Rendering - when and where you render static or dynamic content.
- Integrations - what third-party services you use (for CMS, auth, payments, etc.) and how you connect to them.
- Infrastructure - where you deploy, store, and run your application code (serverless, CDN, edge, etc.).
- Performance - how to optimize your application for end-users.
- Scalability - how your application adapts as your team, data, and traffic grow.
- Developer Experience - your team's experience building and maintaining your application.

## Essential JavaScript for React

- Functions and Arrow Functions
- Objects
- Arrays and array methods
- Destructuring
- Template literals
- Ternary Operators
- ES Modules and Import / Export Syntax

## React core concepts

- Components
- Props
- State

### Components
The web visualization can be broken down to smaller pieces called **Components** to make the big picture;
This *modularity* is good to change individuals **Components** by itself;
They are also written in JavaScript;

### Props 
In JavaScript you can make a function that accepts arguments to work with, in React you can call these arguments **Props**;
The **Props** is treated lika an object, so it has some inside values;

### Hooks and State
React has a set of functions called **Hooks**, and it can add logic to the *components* such as **State**;
Using 'React.useState()' returns an array with two items:
- First one is the **State** *value*; (value)
- Second one is a funtion to *update* the *value*. (setValue)

## After the Core Concepts

### Turning index.html to index.js or index.jsx
After downloading node and npm, you install via npm the following packages:
- react
- react-dom
- next
Then you takeout the part in index.html that uses babel and html tags not inside JavaScript functions,
and thus transforming the file from html to js.
