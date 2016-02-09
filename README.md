## Web Optimisation Udacity Nanodegree Project

To run the application, simply visit: [http://addedsteve.github.io/](http://addedsteve.github.io/)

## Optimising index.html

The load speed of the index web page was slowed greatly by render-blocking css and unnecessary calls to exterior files and sites. It was further slowed by a lack of optimising the smallness of html, css, and js files along with images being used on the page. Steps taking to resolve these issues were:

1. Move CSS from within the styles.css file and place this directly inside the html file.
2. Remove the call to exterior Google fonts page.
3. Employ Gulp to perform minifying on css, html, and js files.
4. Use tinypng and photoshop to massivle reduce the size of the images used in index.html

## Optimising main.js
The Pizzaria page was partially constructed and fully animated using main.js but the script was not fully optimised leading to slow page rendering and performance during scrolling. Steps taken to improve this were:

1. Replace all instances of querySelector with a faster JS method of getElementByID or getElementsByClassName.
2. Ensure that any variables which remain constant during the life of a 'for' loop are assigned just once before the loop executes.
3. Combine 2 switch functions into 1 switch function which does the same job for both initial seperate functions.
4. Optimise the size of the PNG pizza image file.