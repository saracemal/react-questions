react-questions
Here is where I will be answering React questions to help me in my endeavors, but also as a study guide to assist me in interviews! 
<br>
<br>
1. What is React?
React is an open-source Javascript library developed and maintained by Google, created in 2013. React helps create quickly responsive and dynamic web applications (React Native for mobile applications). React is built on using components to organize and allows for flexibility when creating the architecture for the project.

2. React vs Angular?

3. What is JSX?
JSX is a new "dialect" of Javascript code that will embed HTML elements into JS code. It is a "syntax extension", meaning it will not be read as Javascript and be displayed to the DOM. The file has to get complied by a JSX compiler and translate it to regular JS. At the moment, there are no browsers that have a built in compiler, so you need to have a transformer like Babel that can do it for you. JSX can be treated as a JS expression, meaning it can be saved to a variable, passed to a function, stored in an array, etc. You can also add attributes to it, similar to HTML, and it has the ability to be nested. 
<br>
** class and for are reserved words in JS, so class becomes className and for becomes htmlFor for React.
** in order to write JS logic inside of a JSX element, you must wrap it in curly braces.


4. What are stateless components?
They are functions that render the DOM solely based on the properties assigned to them. There is no need for internal state and the output of the component will strictly be the output of the function. 

5. What is the virtual DOM? 
For starters: DOM stands for Document Object Model, made up of HTML text, whose elements become nodes in the DOM. 
