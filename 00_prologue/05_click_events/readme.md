## Click Events

React response to many event types, we specifically look at click event types.

### Calling a simple Function from Click: 

Inserted an arrow function that logs a message into a JSX in button on click injected function name.

1.	Function HandleNameChange   Invoked immediately its called once, make a function & inside JSX we add button element put click it Text, when we call this function we need reference to the function on click then comes JS Expression in JS and we use reference of Function Name, that’s how we call a simple function a button Click. If first button we use reference of handleclick and don’t put Operator, if we put operator it call out immediately

2.	But if we want to pass a Parameters like handleclick, we pass a parameter name into function also in JSX we need to pass a parameter, we need an anonymous function here () => {handleClick(“dave”)}, so there are opertors in this function but this will not called immediately as it is after an anonymous function, so when anonymous function called it calls handleClick function. We also get access to event object when we click.

3.	Now handleClick3 passing a element e not using temp literals writing directly, in JSX we put e in first operators and also passing it to handle click 3 (e). In console we get full event object logged here having several keys and properties interested here in target as target is button now in console log reference target so in console we get event target which is button element itself with text click it 
Double Click Event: react listens to double click as well in paragraph on code.

## Component Reusability - Props & Props Drilling

Props is short of properties and properties hold data & prop drilling allows us to pass data from parent component to child component. 

In Header component we want to add props, Now what we want is that as Content and Footer are siblings and we want to show some number of items data on a Footer this is just not simply possible we have to pass those functions to Parent Component.
Here we are drilling our props to content JS to Parent App,  now we go to content ts and Destructure what we are receiving , items in Properties 
Items , handleCheck, handleDelete.

Example:
Now passing a function to OnClick , it a very unique method , OnClick expects to pass a function complete onClick {() => onClick}
Whereas {set color} is a reference, but giving function like this we can not pass a parameters and directly executing {setOnclick} gives the return value when function will run. 
Also writing like this {setColor ()} on click gets a return value. X
So what we will be doing here is a writing a callback function here and what it does is that it will call a function with in a function.

