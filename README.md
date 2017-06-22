# Adhesive
A powerful HTML, CSS, and Javascript framework that enables mobile-first and responsive web development. It works on a 12 column grid system using css flexbox to align content. Adhesive provides a wide range of styling and sizing classes, as well as easily-embeddable animations created with Javascript and jQuery.

## The Grid System
![Alt text](https://www.rushu.rush.edu/sites/default/files/Rush-12-grid-thumb.png)

The Grid System is comprised of 12 columns on any screen size. I have created the grid to be customizable and adaptable to many different types of projects. The Grid System has four breakpoints; extra-small (default), small, medium, large, and extra-large. Adhesive is a mobile-first framework, and has been developed with that idea to the core.

### Rows and Columns
The row syntax is written as the following: ```<div class='row'>```. And columns ```<div class='col-1'>```. The number in the column class defines the amount of columns that container will span.

The rows only extend 80% of the screen on screens large and up. This can be overriden to extend the full screen by replacing the row class with the ```row-full``` class. ```<div class='row-full'>```

## Animations
Animations can be called easily in CSS by first defining the animation type (fade, slide, hide); then defining the speed (slow, medium, fast); the defining the event tigger (onload, onready, onscroll, onhover, onclick).

Here's an example: ```<div class='fade-slow-onready'>```

The ```onload``` event triggers when the DOM is loaded and ready. The ```onready``` event triggers when the page has loaded including images, fonts, etc. The ```onscroll``` event triggers when the bottom of the viewport touches the element. The ```onhover``` and ```onclick``` are self-explanatory.
