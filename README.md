We will have 4 components in this application, so let’s outline each one and its functionality:

App.js — It will be the parent component for the other 3. It will also contain the function that handles the API request and it will have a function that calls the API during the component’s initial render.
Header.js — A simple component that renders the app header and accepts a title prop
Movie.js — It renders each movie. The movie object is simply passed into it as props.
Search.js — Contains a form with the input element and the search button, contains functions that handle the input element and resets the field, and also contains a function that calls the search function which is passed as props to it.
