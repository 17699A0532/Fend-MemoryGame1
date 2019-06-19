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
### project - cloning
## I followed the below steps to complete this Project.
+ After gone through the instructions, I got a GitHub link about the skeleton project which was provided by
**udacity** in rubric structure.
+ After downloaded the zip file and I extracted that file and placed that file into a new folder.
- While extracting the downloaded project from GitHub, I identified the files.
1. `css/app.css`
2. `img/geometry2.png`
3. `js/app.js`
4. `index.html`(root file)
5. `readme.md` files
+ While seeing the `app.js` file, I came to one conclusion that the `app.js`file require some modifications.
+ Based on our needs , some modifications are done in `app.css`.
+ In memory game, shuffling the cards is a main task. This shuffling function was taken from
`stack over flow` website.
+ All cards are placed in an array and named it as `childList`.
+ when the window is loaded, the shuffle function will be triggered.
+ A spread operator is used by me to convert Html collection into an array.
+ After this , I set the `childList` array as a parameter in `shuffle` function. By doing this ,
I will get a new array everytime.
+ When we click on the card it should show the card. so for this I added a EventListener to the card
and named it as `show card`.
+ In `show card` function, I gave a timer and when I click on the card the timer countdown starts.
+ In storing the card parameter , if two cards are clicked it is one move.
+ There will be 3 stars initially. if the moves exceed to 12 or equal to 12,then one star will be disappear.
if the moves exceeds to exceed to 18.
+ For displaying the output ,I added a pop-up message by using `sweetalert` function.
+ For that I used `sweetalert2` function.
+ Finally, the memory game will be finished after displaying the pop-up message.
