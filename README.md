## Website Performance Optimization portfolio project
There are no additional steps required to run this site

####Part 1: Optimize PageSpeed Insights score for index.html

Optimizations:
1) Added media print to print.css
2) added async to analytics.js
3) created a thumbnail for pizzeria.jpg
4) update img src url for pizzeria.jpg
5) moved google fonts to the top of the head node
6) inlined javascript google font
7) inlined relavent style.css
8) left style.css file as is, but added media=handset for the smaller portrait @media style
9) Reduced img profile picture



####Part 2: Optimize Frames per Second in pizza.html

####To optimize views/pizza.html, you will need to modify views/js/main.js until your frames per second rate is 60 fps or higher. See comments in main.js. 

1) Changed paint pizzas from 200 to 35 (4 rows of 8 cols) 
2) moved the dx function call outside of the for loop. It only needs to be run once the value only changed when the slider is moved. 
3) added meta content to pizza.html
4) compressed pizza.jpg image
5) set document.queryselectorAll to 100 - console.log showed no change in this calculated variable
6) resized pizzaria.jpg -->> address huge image file that get resized much smaller.
8) Inlined minified style.css into pizza.html

