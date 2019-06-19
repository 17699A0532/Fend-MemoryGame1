# Memory Game Project

## Table of Contents

* [Instructions](#instructions)
* [Contributing](#contributing)

## Instructions

The starter project has some HTML and CSS styling to display a static version of the Memory Game project. You'll need to convert this project from a static project to an interactive one. This will require modifying the HTML and CSS files, but primarily the JavaScript file.

To get started, open `js/app.js` and start building out the app's functionality

For specific, detailed instructions, look at the project instructions in the [Udacity Classroom](https://classroom.udacity.com/me).

## Contributing

This repository is the starter code for _all_ Udacity students. Therefore, we most likely will not accept pull requests.

For details, check out [CONTRIBUTING.md](CONTRIBUTING.md).
---------
## I followed the below steps to complete this Project

## cloning of the Project
+ After gone through the instructions, I got a GitHub link about the skeleton project which was provided by **udacity** in rubric structure.
+ After extracting the downloaded project from GitHub, I came to understand that most of the
modifications has to be done in `app.js`.
+ observed `shuffle` function which was provided by stackoverflow in `app.js`. And created an array for listing all the cards named it as `childList`.
+ I used spread operator(`[...]`) to convert HTMLcollection into array
+ I got new shuffled array After setting the `childList` array as parameter in `shuffle` function.
+ Added a `click` EventListener to each with in function named `showCard`.
+ I concentrated on timer function, added timer function(`startTimer`) definition in `showcard` function.
+ I understand that timer function not working properly.so I took variable and assigned a boolean.
+ Then time will be caluculated using `startTimer` function.
+ moves if(moves>=12) starRating=2
+ moves if(moves>=18) starRating=1
+ we used sweetalert to give the popup of the game.
### code modification
1. code is used for reloading the game  `document.location.refresh`;
