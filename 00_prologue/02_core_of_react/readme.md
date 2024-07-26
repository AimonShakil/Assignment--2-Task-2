## Project Structure | Inner Engineering: 
## Foundation Rules: 

### Foundation Rule: 
	Goal is to look into how React is being inject in HTML. we have to inject JS into HTML and have to call scripts there is no way other than to insert JS in script tag of HTML and manipulate. We should be getting basic idea from where react is coming how and at which point is being injected and now application is ready.

### SPA: Single Page Applications:
	In src Folder there is a main page called Index.html,  this is only page which is loaded that why called SPA (single page application). All work will be done in this HTML file as foundation will remain same as we have one page and all work will be done in this this is a main page foundation will remain same as all elements like images sliders tags or whatever is coming through DOM. With DOM manipulation we can make disappear sliders and can add buttons change their text, so all it is manipulation. when we move from one page to another actually DOM manipulates and makes new painting for second page and contact us that all work will be done here.

### SRC Folder:
	In Src folder Index. js is main entry file for JS, before that we had cleaned HTML with comments. To manipulate web DOM there are two libraries (react which is core foundational library  and React DOM is its implementation on web).

### DOM:
	Using react DOM, as in website we have DOM so react also makes its own DOM it is actually  a tree structure like top element tags etc so browser have its own DOM and react makes its own DOM called as a virtual DOM, they compares itself with main DOM and only tweaks main DOM with elements which are needed.

	So, we write React DOM as it makes its own DOM then we write create root, where to make root this is a methods and need to give HTML element as its is basic JS and searched element ID of which is root.  Thats how we took reference of virtual DOM and get element by ID and then stored in root variable. Then said root to render asks to take property of react <react.strict mode> (this strict mode is meant for development specific so we can do some optimization and good to use but even removing this does’t matter) and then render <App /> as there is no such tag in html.
JSX:
	This is biggest power reacts gives is JSX Power as through JS we can render our HTML elements and JSX almost seems like HTML through this means we can make our custom tags. Now where these customs tags coming from ?

### App:
	what is app, its just a function we write in app file which returns H1 tags and in last we have exported this function.

Interesting syntax by react, make a function Land return HTML and HTML will be rendered. Advantage is we have got Programming Capabilities in HTML which never exist so in bigger applications with complex UI this concept is Important.

### Dependencies:
	Now most important are react script in package Jason, they do background work goes to Index HTML and load index.JS into it. Proof can be seen through view page source as script defer static JS bundle also many things can be seen through inspect element all these added scripts in body added by JS Scripts.

	Learnt making a function and exporting (JSX file) into import and other file  to (APP.JSX) as we can return only one element give error and learn further, gives error that should enclosed in a wrapping tag if returning more than one element means we can export only one element.

	So there are many ways to return more than one elements(but can put many elements inside it) by just returning empty tag <> , </> in react it is called as fragment.
