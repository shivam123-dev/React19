# Introduction to ReactJS

Reactjs is a js library used for building user interfaces and single page applications.
Created by Jordan Walke at Facebook
Most popular Js library for frontend development.

# History of ReactJs

Reactjs began as an internal tool for dynamic facebook components.
Created in 2011 but remained private initially.
Reactjs was open-sourced by Jordan Walke and Tom Occhino at JSconfUS 2013.
Reactjs was firstly used in NewsReed on FB.
Released with the belief that its success at fb could benefit others.
Initially faced criticism for combining JS and HTML in a single file.
It was widely hated and criticized because of its combination of JS and HTML in single file.
It slowly gained traction and blew up in adoption.

# Is Reactjs a Library or Framework?

React is not a framework. React is a JS library for building user interfaces.
It is also known as ReactJS and React.js
React knows only one thing that is to create an awesome UI.

## React is all about your components

## React is Declarative.

# Why Reactjs?

React is declarative because it describes what the UI should look like rather than how to achieve it. This makes the code easier
to read and maintain, as it is more focused on the end result rather than the steps involved in getting here.

Ex:

function MyComponent( {name} ) {
    return <div>Hello, {name}!</div>;  // -> React - Declarative
}

function MyComponent(name) {
    const element  = document.createElement('div);   // Create a new div element
    element.textContent = `Hello, ${name}!`;         // Set text content manually           // -> JS - Imperative
    return element;                                  // Return the created element
}

Here, we are manually creating elements, setting their properties, setting their properties, and appending them to the DOM.

Note: Impertive means to tell program each and every steps whereas Declarative means just to give command, the code will handle the
procedures.

# Working of React

1. We create the components
2. These components when combined together are called instances.
3. These instances are then converted to React Elements (where Reconcilation happens) by Babel.
4. Now, it converts to DOM element.
5. Which then gets converted to Final UI (which gets rendered).

Note: Till point 2. user performs rest steps React takes care.

# Why Reactjs over Vanilla JS ?

Oppose to Vanilla JS, React has a concept called <b>components</b> which combines all HTML, CSS and JavaScript by features instead
of separating HTML, CSS and JavaScript completely.
ReactJS manages updating the DOM or Document Object Model with the components written by us.

# Why ReactJS ?

React is the most popular JS library for building user interfaces.
Component-Based Architecture
Declarative UI
Rich Ecosystem - npm packages
Strong community support - Online/Github

# Package.json

Contains all the details or configuration regarding the project. It includes name, version, description, scripts and dependencies used in the project.

<b>"scripts"</b> here includes all the scripts present in the project.