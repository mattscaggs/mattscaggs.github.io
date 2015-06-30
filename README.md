# Udacity FE Web Dev P4

Index.html optimizations
========================
based on page speed insights feedback:
* optimized images for faster download
* added async to google analytics scripting to prevent render blocking
* added media print to print.css to prevent render blocking for screen viewing
* changed to web font loader and made async
* minified css
* inlined style from style.css to prevent render blocking

Outcome 
-------
93 mobile,  95desktop
http://mattscaggs.github.io/ 

Main.js optimizations
=====================
* reduced the number of pizzas calculated by accounting for users screen and rendering only pizzas needed, vs 200
* declared variables outside for loops  
* shifted some calculations outside for loops

Outcome 
-------
page scrolls @ 60 FPS as measured w/ dev tools

References
==========
Course material and lectures, plus: https://github.com/udacity/fend-office-hours/tree/master/Web%20Optimization/Effective%20Optimizations%20for%2060%20FPS
