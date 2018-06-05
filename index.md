## Web Dev Mastery

We run web dev projects on a regular basis.  We normally do a server-less stack using firebase, firebase functions, react, and sass.  Part of the process is that we train students to become better developers by doing meaningful real-world projects.  

So every time we get together to start knocking out new goals there is a healthy mix of seasoned developers and complete rookies.  This page is aimed at giving helpful practice no matter where on the spectrum you lie.  

Treat them like repeatable exercises which you can do with different tools, faster over time, with better engineering, or a new paradigm.  These are the deliverables which are most common and likely to show up on any particular day of a sprint.

# The Tasks:

* Javascript Basics
  * Level 1: Save values into a variables
  * Level 2: Create functions in several different ways
  * Level 3: Check the Type of a variable
  * Level 4: Create an array of values
  * Use for loops in several ways
  * Level 5: Use map, filter, and reduce
  * Level 6: Learn the word `this` and learn how to use `bind`
  * Level 7: Grab a subarray
  * Level 8: Sort an array
  * Level 9: Grab a substring
  * Level 10: Use `join`
  * Level 11: Convert strings to numbers and back

* Objects in Javascript
  * Level 0: Design the characteristics of a user (name, id, email, etc)
  * Level 1: Store those characteristics in a JSON object
  * Level 2: Create a user class and make several instances of users
  * Level 3: Give the class a method, call it on the instances
  * Level 4: Use prototypes to give the parent class a method which all instances can now use
  * Level 5: Pass a user instance into a function and change an attribute, check the mutation of the original object
  * Level 5: Make a copy of a user which you can edit without changing the original copy
  * Use `Object.keys()`

* Interactive Web Basics
  * Level 1: Show some basic tags on screen (h1-h6, p, div, span)
  * Level 2: Use CSS selectors to change their colors to salmon
  * Level 3: Use vanilla javascript and CSS selectors to change the text of a particular tag via Javascript
  * Level 4: Create an event listener and change the text when a particular tag is clicked
  * Level 5: Create input tags of various types
  * Level 6: Read the value of a particular input tag and render it on screen in a different tag
  * Level 7: Create an input for each attribute of a user object and on the click of a button create a user object with the desired attributes

* Render an array of objects
  * Level 1: For each object in an array of objects (hard-coded if you'd like) show information from that object on screen
  * Level 2: Make each object render as it's own class/component/template
  * Level 3: When a user clicks a particular object change the data for that object and show change on screen
  * Level 4: Let a user add an object to the array
  * Level 5: Let a user delete an object from the array
  * Level 6: 'save' and 'load' the array of objects into localStorage
  * Level 7: 'save' and 'load' the array of objects into firebase
  * Level 8: Use 'bind' to never have any identifying info in your DOM
  * Level 9: On any change to the object save the new state

* React App Basics
  * Level 1: Generate a boilerplate react app and host locally using `npm start`
  * Level 2: Build a static version using `npm run build`
  * Level 3: Use a third-party tool in the app `npm install --save firebase` and `import firebase from 'firebase'`
  * Level 4: Edit a render function to show 'Hello World!' on screen
  * Level 5: Make a simple component in it's own file and use it in the main App render
  * Level 6: Pass values from the App screen to the component via `props`
  * Level 7: Have the component render values from those props and have the App change the values every 2 seconds
  * Level 8: Inside the component have an internal counter which keeps track of how many seconds the component has existed
  * Level 9: Everytime the counter is increased use `setState` to save the new value in the state of the component (and render that value)
  * Level 10: Use URL routing to make several pages one each for `/path1`, `/path2/:variablehere`, and `/path2/:variablehere/profile`
  * Level 11: Read the variable values from the URL
  * Level 12: Add a button to the component, when clicked report the click to the higher level App 

* Coordination of on-screen components
  * Level 1: Have several components show on the same screen (like a list of comments, a comment count, and a navigation component)
  * Level 2: When one component updates have the others also update (think of the best ways to do this)
  * Level 3: Implement a pub/sub pattern so that you can broadcast from one class to any registered observers
  * Level 4: Use a 'store' and 'singleton' pattern to coordinate data across several routes of the app

* Authenticate a user using oAuth
  * Level 1: Get a user's uid from google via firebase
  * Level 2: Detect logged-in status and show relevant info and actions on screen
  * Level 3: Perform redirects based on current authentication state
  * White-label custom domains
  * Use many service providers
  
* Communicate with a firebase backend
  * Level 0: Start a firebase project and get the config details
  * Level 1: Use javascript to connect with firebase
  * Recognize that the database is really just JSON
  * Level 2: Set an `on('value')` callback and display data from the firebase
  * Level 3: Use Javascript to write to a particular path in the db
  * Level 4: Use `push` to create a uuid/array style object
  * Level 5: After pushing a few items to a particular key read that key and convert the values into an array
  * Level 6: Render an array of objects from the db on screen, edit it through the firebase GUI and see the change on screen
  * Level 7: Have each object be a component
  * Level 8: When that component detects a change push it to the database

* Hosting a site
  * Level 1: Use the firebase CLI to initialize a project and connect it to an existing firebase project
  * Level 2: Use `firebase deploy --only hosting` to push the website static folder
  * Level 3: Connect a domain name via the GUI

* Setup Firebase functions / RESTful APis
  * Level 0: Play with nodejs and express
  * Level 1: Use the CLI to setup a basic `onWrite` listener on a particular key
  * Level 2: Make a write and check the logs
  * Level 3: Read the data which was written and process it in the function
  * Level 4: Delete the data which triggered the function call (be careful to check for null data as the function might get called twice)
  * Level 5: Push the data into three other locations in the DB
  * Level 6: Setup a REST API trigger which reacts to http requests (uses express)
  * Level 7: Make an 'AJAX' request from client-side javascript to the firebase server
  
## Mini Lectures:

**Setting up SASS/SCSS**
<iframe src="https://player.vimeo.com/video/273346382?title=0&byline=0&portrait=0" width="640" height="360" frameborder="0" webkitallowfullscreen mozallowfullscreen allowfullscreen></iframe>

**Firebase CRUD 101**
<iframe src="https://player.vimeo.com/video/273433235?title=0&byline=0&portrait=0" width="640" height="400" frameborder="0" webkitallowfullscreen mozallowfullscreen allowfullscreen></iframe>
