# CSS Background Image Display Error

This repository demonstrates a subtle CSS error where a missing semicolon prevents a background image from displaying correctly.  The bug is in `bug.css`, and the solution is in `bugSolution.css`. The error is a common oversight, and this example serves as a reminder to pay close attention to detail when working with CSS.

The error occurs because of a missing semicolon after the `background-size` property in `bug.css`. This causes the CSS parser to interpret `background-position` incorrectly. This results in the background image not being displayed. 

## Setup

To run this example, create two files named `bug.css` and `bugSolution.css` and copy the contents from their respective files in this repository.   Then, include these stylesheets in your HTML to observe the differences and see the solution in action.