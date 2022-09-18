1. What is React?
--> React is a library of JavaScript for front-end. React is mainly used for building user interfaces based on UI components. React introduced/developed and maintained by Meta (Facebook) and a community of individual developers and companies. It is free and open-source JavaScript library. Main aim of React is to allow developers to easily create fast user interfaces for websites and applications.

2. Who made React?
--> React was originally created by Jordan Walke and then it is maintained by Meta (formerly Facebook) and a community of individual developers and companies.

3. What is Babel?
--> Babel is a JavaScript transcompiler which is open-source and that can translate markup or programming languages into pure JavaScript. and also used to convert ECMAScript 2015+ code into backwards-compatible JavaScript code that can be run by older JavaScript engines. It allows web developers to take advantage of the newest features of the language. React uses Babel to convert JSX (JavaScript XML) into JavaScript. 

4. How does Babel convert html code in React into valid code?
--> Babel is a tool that is used to convert source code into another source code that is of the same level. That is why it is also known as a source-to-source compiler. Both the codes are equivalent in nature, considering the fact that one works with the specific version of the browser and one doesn’t.
To convert html code in React valid code inside babel their are three main stages. 
Stage-1 Parsing :- Babel takes the source code and parses it into a abstract representation of the code. This abstract representation is called AST ( Abstract Syntax Tree). An AST is a tree representation of the abstract syntactic structure of source code. Each node of the tree denotes a construct occurring in the source code.
Stage-2 Transformation:- Here Babel takes the AST from the last step and manipulates it accordingly such that the resultant AST represents a browser suppported code. This stage is taken care by a Babel plugin/preset. Presets are just simply an array of plugins that make it easier to run a whole a set of transforms without specifying each one manually.
Stage-3 Code Generation:- In this stage, the transformed new AST in the previous step is turned into its source code which is browser supported. By this way babel works internally to convert HTML code in React valid code.

5. What is ReactDOM used for? Write an example?
--> 
