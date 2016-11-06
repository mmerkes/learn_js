# learn_js
A collection of resources for learning JavaScript

- [General JS Problems](#general-js-problems)
- [Front End Mini Projects](#front-end-mini-projects)

<a name="general-js-problems"/>
## General JS Problems

- [Sudoku Solver](#sudoku-solver)
- [Spell Checker](#spell-checker)

<a name="sudoku-solver"/>
### Write a Sudoku Solver
Write a method that takes a 2D array sudoku board and returns the solution.

#### Requirements
1. Should solve any standard 9x9 sudoku puzzle.
2. Solution should take less than a minute run for ANY difficulty puzzle. Single digit milliseconds is reasonable.
3. Write tests to validate your solution. You should use a sudoku board of different difficulties, i.e. easy, medium, hard, diabolical.

#### Bonus
1. Write a method that can solve a sudoku puzzle of any size.
2. Figure out the Big O notation for your solution.

<a name="spell-checker"/>
### Write a Spell Checker
Write a method that will take a string, and return spelling suggestions.
TODO: Add requirements

<a name="front-end-mini-projects"/>
## Front End Mini Projects

- [States Filter](#states-filter)
- [Five Star Widget](#five-star-widget)
- [Accordion](#accordion)
- [Timeline](#timeline)

<a name="states-filter"/>
### States Filter
Create an HTML page with an input box and a filtered of US states.

#### Requirements
1. By default, the page should have an empty input box and a list of 50 states.
2. When user types into the input box, the list should only display matching states.
3. If no states match the input, display something indicating to the user that no results were found.

#### Bonus
1. Add an x button inside of the input box that clears the input when clicked.
2. Display states in a table and allow the user to change the sorting.
3. Write the filter in a generic, reusable way that would work for any array of strings.

<a name="five-star-widget"/>
### Write a 5 Star Widget
Write HTML, CSS, and JS for a five star widget.

#### Requirements
1. First Step: Create a static five star widget with gold stars and greyed unselected stars. No Interaction.
2. User can click on a star to select a rating.
3. Component should be easily reusable in multiple places.

#### Bonus
1. When user hovers over a star, it should display as though she selected it, and return to its original state when mouse leaves.
2. Allow setting half star increments
3. Turn into a reusable widget for a front end framework (i.e. An AngularJS directive)

<a name="accordion"/>
### Accordion
Create an accordion that allows the user to open and close content.

#### Requirements
1. When a user clicks on a title, content should open underneath it.
2. Accordion should be able to handle any number of items.

#### Bonus
1. Write the accordion as a reusable component.
2. Make the accordion dynamically take a JavaScript array of objects with content and generate the accordion on the fly.
3. Should be able to add/remove content from the accordion.
4. Turn into a reusable widget for a front end framework (i.e. An AngularJS directive)
5. Allow the accordion to take an option to only should one opened content at a time.
6. Allow the user to resize the content.

<a name="timeline"/>
### Timeline
Create a timeline widget that displays a time period and content.

#### Requirements
1. Create a horizontal timeline that displays time periods at a fixed distance.
2. Display some sort of content, a picture or text, at each mark on the timeline.

#### Bonus
1. When the user hovers over content, display a tooltip with more information.
2. Write the timeline as a reusable widget.
3. Allow the timeline to take an image as the marker for each point on a timeline.
4. Allow the developer to choose different styles for the timeline, i.e. different markers, fixed vs. proportional distance between points, or whatever you find useful or interesting.
5. Turn into a reusable widget for a front end framework (i.e. An AngularJS directive)
