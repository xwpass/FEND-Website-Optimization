## Website Performance Optimization portfolio project

## About
The first objective for the project is to optimize a [portfolio homepage site](http://xwpass.github.io/FEND-Website-Optimization/), by making the `index.html` to achieves a  `PageSpeed` socre of at least 90 for Mobile and Desktop.
The second objective for the project is to optimize `views/js/main.js` to make `views/pizza/html` render with a consistent frame-rate at 60fps when scrolling. Time to resize pizzas is less than 5 ms using the pizza size slider on the `views/pizza.html` page. Resize time is shown in the browser developer tools.

## How to Run

Click the download button.
Copy the `.zip` file to the folder where you want the application.
Uncompress the `.zip` file.
Open the `index.html` file with your favorite browser.

Live version:http://xwpass.github.io/FEND-Website-Optimization/

## Improvements
1. index.html
 - inline css.
 - add media print css file.
 - async js files.
 - scale down over-sized images.

2. main.js
 - replaced `querySelector` with `getElementById`.
 - replaced `querySelectorAll` with `getElementsByClassName`.
 - optimized `updatePositions` function.
 - optimized `changePizzaSizes` function.

## Reference
[PageSpeed Insights](https://developers.google.com/speed/pagespeed/insights/)
