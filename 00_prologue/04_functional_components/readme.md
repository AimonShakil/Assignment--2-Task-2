## Adding Functional Components 

This is a power of react that we can create/ add more functional components to react that are.  reusable. 

In Index. Js we have import App component as App is injected in DOM, we will going to do the same thing make a component and import it into App.Js as app.js is a  parent of all the other component tree.

Ctl + Alt + R  rafce   (creates a generic Functional Component)
It had already Header name as that of a File in a file Header.js in src and will import this in app component 

Delete logo import and header in return and put <Header / > custom element in JSX return, so we have created a separate functional component and imported that component. 

Copy that handle function and logic in Content and Import it in app component.

We encapsulated logics in 3 components and App is a parent component we have imported at the components and then will be able to put them inside a layout of JSX.
