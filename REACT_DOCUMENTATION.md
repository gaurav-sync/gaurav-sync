# REACT DOCUMENTATION

## Index
1. [What is React?](https://github.com/gauravsapkal/gauravsapkal/edit/main/REACT_DOCUMENTATION.md#1-what-is-react)
2. [Who made React?](https://github.com/gauravsapkal/gauravsapkal/edit/main/REACT_DOCUMENTATION.md#2-who-made-react)
3. [What is Babel?](https://github.com/gauravsapkal/gauravsapkal/edit/main/REACT_DOCUMENTATION.md#3-what-is-babel)
4. [How does Babel convert html code in React into valid code?](https://github.com/gauravsapkal/gauravsapkal/edit/main/REACT_DOCUMENTATION.md#4-how-does-babel-convert-html-code-in-react-into-valid-code)
5. [What is ReactDOM used for? Write an example?](https://github.com/gauravsapkal/gauravsapkal/edit/main/REACT_DOCUMENTATION.md#5-what-is-reactdom-used-for-write-an-example)
6. [What are the packages that you need to import for react to work with?](https://github.com/gauravsapkal/gauravsapkal/edit/main/REACT_DOCUMENTATION.md#6-what-are-the-packages-that-you-need-to-import-for-react-to-work-with)
7. [How do you add react to a web application?](https://github.com/gauravsapkal/gauravsapkal/edit/main/REACT_DOCUMENTATION.md#7-how-do-you-add-react-to-a-web-application)
8. [What is React.createElement?](https://github.com/gauravsapkal/gauravsapkal/edit/main/REACT_DOCUMENTATION.md#8-what-is-reactcreateelement)
9. [What are the three properties that createElement accept?](https://github.com/gauravsapkal/gauravsapkal/edit/main/REACT_DOCUMENTATION.md#9-what-are-the-three-properties-that-createelement-accept)
10. [What is the meaning of render and root?](https://github.com/gauravsapkal/gauravsapkal/edit/main/REACT_DOCUMENTATION.md#10-what-is-the-meaning-of-render-and-root)
<hr/>

### 1. What is React?
--> React is a library of JavaScript for front-end. React is mainly used for building user interfaces based on UI components. React introduced/developed and maintained by Meta (Facebook) and a community of individual developers and companies. It is free and open-source JavaScript library. Main aim of React is to allow developers to easily create fast user interfaces for websites and applications.
<hr/>

### 2. Who made React?
--> React was originally created by Jordan Walke and then it is maintained by Meta (formerly Facebook) and a community of individual developers and companies.
<hr/>

### 3. What is Babel?
--> Babel is a JavaScript transcompiler which is open-source and that can translate markup or programming languages into pure JavaScript. and also used to convert ECMAScript 2015+ code into backwards-compatible JavaScript code that can be run by older JavaScript engines. It allows web developers to take advantage of the newest features of the language. React uses Babel to convert JSX (JavaScript XML) into JavaScript. 
<hr/>

### 4. How does Babel convert html code in React into valid code?
--> Babel is a tool that is used to convert source code into another source code that is of the same level. That is why it is also known as a source-to-source compiler. Both the codes are equivalent in nature, considering the fact that one works with the specific version of the browser and one doesn’t.
To convert html code in React valid code inside babel their are three main stages. 
Stage-1 Parsing :- Babel takes the source code and parses it into a abstract representation of the code. This abstract representation is called AST ( Abstract Syntax Tree). An AST is a tree representation of the abstract syntactic structure of source code. Each node of the tree denotes a construct occurring in the source code.
Stage-2 Transformation:- Here Babel takes the AST from the last step and manipulates it accordingly such that the resultant AST represents a browser suppported code. This stage is taken care by a Babel plugin/preset. Presets are just simply an array of plugins that make it easier to run a whole a set of transforms without specifying each one manually.
Stage-3 Code Generation:- In this stage, the transformed new AST in the previous step is turned into its source code which is browser supported. By this way babel works internally to convert HTML code in React valid code.
<hr/>

### 5. What is ReactDOM used for? Write an example?
--> ReactDOM is a package that is able to provide DOM specific methods that can be used at the top level of a any web app to enable an efficient way of managing DOM elements of the web page. ReactDOM provides the developers with an API which developers can able to acess for better perrformance. The React virtual DOM is a programming concept where an ideal, or “virtual”, representation of a UI is kept in memory and synced with the “real” DOM by a library such as ReactDOM. This process is called reconciliation. virtual DOM is more of a pattern than a specific technology. Let's take example of your home if you want to make certain change in your home, you will first see map of your home then according to that map you will change only that part which is required to change, you don"t distroy your whole home and create new home for some changes. Same as this example without using react whole previous dom get distroyed and new dom get created for any changes , but in react only the required changes get rendered with the help of virtual dom and that get reflected in master dom by this way changes made get rendered in dom without destroying it and with less processing. This is an example of react dom.
<hr/>

### 6. What are the packages that you need to import for react to work with?
--> a. firstly we need to install npm and NodeJS
    b. create react application using npx create-react-app my-react-app
    c. import react using import React from 'React'
    d. import react DOM from CDN <script src="https://unpkg.com/react-dom@18/umd/react-dom.development.js" crossorigin></script>
    e. import babel from CDN using <script src="https://unpkg.com/@babel/standalone/babel.min.js"></script>
    f. import react DOM using import ReactDOM from 'react-dom/client'
    g. import react from CDN <script src="https://unpkg.com/react@18/umd/react.development.js" crossorigin></script>
    these packages need to import for react to work.
<hr/>

### 7. How do you add react to a web application?
--> a. Add a DOM Container to the HTML
    b. Add the Script Tags
       i. <script src="https://unpkg.com/react@18/umd/react.development.js" crossorigin></script>
       ii. <script src="https://unpkg.com/react-dom@18/umd/react-dom.development.js" crossorigin>
       iii. <script src="https://unpkg.com/babel-standalone@6/babel.min.js"></script>
    c. Create a React Component
    d. start working in React components.
<hr/>
  
### 8. What is React.createElement?
--> React.createElement( type, [props], [... children] ) Create and return a new React element of the given type. The type argument can be either a tag name string (such as 'div' or 'span' ), a React component type (a class or a function), or a React fragment type.
<hr/>
  
### 9. What are the three properties that createElement accept?
--> type: the type of the HTML element (h1,p,button).
    props: properties of the object({style:{size:10px}} or Eventhandlers, classNames,etc).
    children: anything that need to be displayed on the screen.
<hr/>
  
### 10. What is the meaning of render and root?
--> render:- React injects HTML to the web page by using a function called render(). The purpose of the function is to display the specified HTML code inside the specified HTML element. In the render() method, we can read props and state and return our JSX code to the root component of our app.
  root:- The root node is the HTML element where you want to display the result. It is like a container for content managed by React.
