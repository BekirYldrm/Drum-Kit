# About the project

* You can create your own music with a drum kit on this website.
* The aim of this project is to learn [event listeners](https://www.w3schools.com/js/js_htmldom_eventlistener.asp) and the [document object model](https://www.w3schools.com/js/js_htmldom.asp).

## Technologies and methods used in the project

* Basic JavaScript, HTML, CSS are used.

### Function key()

```document.addEventListener("keypress", key);
function key(event) {
    sounds(event.key);
    buttonAnimation(event.key);
} 
```

* You can find this code block in the index.js file. 
* This key function works as a callback function when the event listener of type keypress is triggered.
* It then calls the sounds and buttonAnimation functions.
* A number of conditions are checked in the sounds function. If these conditions are met, certain code blocks run.
* buttonAnimation function, animation classes are added to the HTML element where the event occurs.

## Requirements to run the project

* No modules or libraries are required to run this project because the site is a static site.