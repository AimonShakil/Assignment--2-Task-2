## App and JSX

App component is injected in DOM in Index.JS
We will be modifying these components, will be exploring app component which is the default component created by a new react project also going to explore JSX and what do we do within it. Modern react uses functional components. 
We will import that component form app file as each component have its own file. 
So going to App.js and we make changes, local dev server changes we will make automatic updates as will change this file.

## Component: 
Component is a function and this app function is returning JSX (stands for JS in XML) which is Js, we can add more JS into it as a variable, it resembles html  but is not. We wrote div, img, but some of the attributes are different also src, href and target attributes aswell. Here just referring to src value we are referring to Logo variable that pulled in Logo from a Lexical scope (also import up)  & pulled into img tag as a value for source & image is displayed in a component.  Also JSX allows us to put JS expression in to the code as well.
JSX provide template for the component layout, also JSX renders data as a text that displays as we provide a text string as either type of data which is renders as a text  like <p> html </p>.

## JavaScript Expression:
If we want to inject Element <p> {“Dave”} </P> putting dave as a string, now we get dave rendered to page as a string, Array [1,2,3] and {2} , they all rendered on page as a string and by removing curly braces it will be rendered as a html,  Curly braces says its a JS expression but “objects are not valid as a react child “ {{a: 2, b: 23}} X so no objects can be rendered to page also Boolean can also not rendered to page. Name variable can be put in and get value.

## Comments:
// shift Alt + A for Comments in JSX



