## How to open this website
In order to view this website, download this repository and open index.html in the main directory.

## Optimization made to ~/index.html
By Google PageSpeed, we are better loading the CSS into the Head section of the HTML, those style sections were minified. Beyond that the HTML now has a *cache-control* and *expires* Meta in their Head section. The GoogleFont was removed. The expiration date is set for 1 year from 11/21/2017.
Also the Google Analytics were moved to the end of the HTML.
PageSpeed for Mobile is 93/100
PageSpeed for Desktop is 96/100

## Optimization made to ~/views/pizza.html
Just like the ~/index.html the CSS is now in the body of the HTML Head section, those style sections were minified. Like the previous HTML this page also has a *cache-control* and *expires* Meta in their Head section. The expiration date is set for 1 year from 11/21/2017.
PageSpeed for Mobile is 95/100
PageSpeed for Desktop is 92/100

## Optimization made to ~/views/js/main.js
Two parts of the JavaScript were changed.
At line 451 the *changePizzaSizes* function were rearranged to use one Pizza size and apply it to all Pizza elements in the page.
At line 515 the *var* scrollTop and phase were moved out of the for loop.

## Others optimizations
Those images were resized and/or compressed for bandwidth saving:
~/img/profilepic.jpg
~/views/images/pizzeria.jpg
~/img/project-2048.jpg (This was originally an external image)
~/img/project-mobile.jpg (This was originally an external image)
~/img/project-webperf.jpg (This was originally an external image)
~/views/images/pizza.jpg
