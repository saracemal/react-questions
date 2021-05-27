react-questions
Here is where I will be answering React questions to help me in my endeavors, but also as a study guide to assist me in interviews! 
<br>
<br>
1. What is React?
React is an open-source Javascript library developed and maintained by Google, created in 2013. React helps create quickly responsive and dynamic web applications (React Native for mobile applications). React is built on using components to organize and allows for flexibility when creating the architecture for the project.

React disadvantages?
It is just a library, not a full blown language or framework. It can be difficult for novice programmers to understand if they don't have a good understanding of javascript and HTML, considering that JSX requires you to know both.  

2. React vs Angular? 
React uses the virtual DOM, where Angular uses the full DOM.
React uses server side rendering, where angular uses client-side rendering. 
React is created and maintained by Facebook, where Angular is by Google. 

3. What is JSX?
JSX is a new "dialect" of Javascript code that will embed HTML elements into JS code. It is a "syntax extension", meaning it will not be read as Javascript and be displayed to the DOM. The file has to get complied by a JSX compiler and translate it to regular JS. At the moment, there are no browsers that have a built in compiler, so you need to have a transformer like Babel that can do it for you. JSX can be treated as a JS expression, meaning it can be saved to a variable, passed to a function, stored in an array, etc. You can also add attributes to it, similar to HTML, and it has the ability to be nested. 
<br>
** class and for are reserved words in JS, so class becomes className and for becomes htmlFor for React.
** in order to write JS logic inside of a JSX element, you must wrap it in curly braces.


4. What are stateless components?
They are functions that render the DOM solely based on the properties assigned to them. There is no need for internal state and the output of the component will strictly be the output of the function. 

5. What is the virtual DOM? 
For starters: DOM stands for Document Object Model, made up of HTML text, whose elements become nodes in the DOM. 

6. What is a React component? A small, reusable chunk of code that is responsible for obe job (usually rendering HTML). 

7. What are props?
Props are a shorthand for "properties", and they are immutable components passed through from parent to child and they help render data. 

8. What is state?
State is a mutable data source within a react component that helps create dynamic and interactive components. 

9. What are refs in React?
Refs are used for storing the reference of element or component returned by the component render() configuration function.
When should you use refs?

10. What is the differences between an element or a component in React? 
A react element is a representation of some sort of user interface, and it describes what you want displayed on the screen. A component is a function that can accept input but also return a React element. 

11. What is the significance of keys in React?
Keys are helpful in identifying the individual elements you want displayed on the virtual DOM. Keys help React optimize the rendering, as well as only making React reorder keys instead of rerendering them. It's important to use the index as keys within a DOM element instead of id, to help further optimize this rendering. 
