Gulp and NPM

Gulp tasks to automate the build and reloading of webserver to optimize the developer experience. You can also uglify and concatinate some of the code.
Uglify - the process by which code is shortened (by shortening variable and function names), removing comments, and line spaces removed. This results in less characters and smaller file sizes. Files that are smaller load faster. The browser doesn't need spaces, comments, or long variable names that humans need to process code. Uglification (also known as minification) optimizes the code for performance over readability.
Concatenate - the process of merging the code from multiple files into one file. This will clean up our markup in the index.html, so that the browser will only have to request one file when our page loads.

Install gulp globally.
run:
$ gulp build:js

Next install
$ npm install gulp gulp-uglify gulp-concat gulp-nodemon