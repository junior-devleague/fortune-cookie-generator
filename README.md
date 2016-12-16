## Fortune Cookie Generator
In this assignment students explore the native tools provided in Javascript to
navigate and affect the DOM. To practice these techniques, we will create a
Fortune Cookie Generator app that will show you a fortune you might find
in a fortune cookie.

Feel free to have fun with this, and there are lots of ways to stretch in this
assignment. If done right, this could be a fun portfolio piece.

## Objective
To create a simple working application accessing **HTML Elements** with the DOM and using **JavaScript Logic** and **Events** to create a button on a web page and when the user clicks on that button, they will receive a visual indicator that they clicked the button.

## Prerequisites 
In order to complete this project students must have the following:
- Basic understanding of HTML structures and HTML attributes. 
- Basic understanding of JavaScript and DOM.

## Your Challenge
To complete the base level of this assignment, you must fulfill the following
requirements:

* Set up your project file structure through the command line.
* Create a "Make My Fortune!" button in your `html` structure.
* Create a box with the id `fortune-cookie-text`.
* Create a box with the id `previous-fortunes`.
* Add an `onclick` attribute to the button so it executes the `generateFortuneCookie` function when it is clicked.
* In the `app.js` create the logic to display a fortune:
    * Select the `fortune-cookie-text` element.
    * Append the current text in the `fortune-cookie-text` element as a list item (`li`) within the `previous-fortunes` list.
    * Create an array called `fortunesList` that includes fortunes.
    * Select a random fortune cookie saying from the `fortunesList` Array using a `for loop`.
    * Replace the `innerText` of the `fortune-cookie-text` element with the data you selected from `fortunesList`.
* Make sure a fortune is generated each time the user clicks the button.

## Stretch Goals
This assignment allows for a large number of possible stretch goals. You are encouraged to stretch in additional ways if you can think of fun/interesting things to try. Here are some ideas:

* It's currently possible to randomly select the same fortune twice in a row. Can you think of a way to check if the new saying is the same as the previous saying and prevent it from showing up? Can you think of a way to keep track of all the sayings that have been used and prevent a saying from being repeated until the entire list has been exhausted?
* This page is begging for some cute visuals. Use CSS to style the elements in the HTML. Feel free to add or rearrange HTML elements to fit your vision.
* You could show additional statistics on the page, such as how many fortunes have been generated. Add those in an appealing way.
* What if people want to generate fortunes for their whole table? Why not allow somebody to generate multiple fortunes at the same time? How would you change the code and HTML to support that?

##Resources
http://www.w3schools.com/jsref/jsref_random.asp
http://www.w3schools.com/jsref/tryit.asp?filename=tryjsref_node_appendchild
