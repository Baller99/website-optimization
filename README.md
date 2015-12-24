## Website Performance Optimization portfolio project

Navigate to views file
Click on pizza.html

Part 1: Optimize PageSpeed Insights score for index.html

Inlined CSS directly to index.html
Minifed css files provided by Pagespeed Insights
Optimized style.css delivery by making it to inline CSS in index.html.

References:

Website Performance Optimization Course

Part 2: Optimize FPS in pizza.html

Changed "querySelector"/"querySelectorAll" to getElementsByClassName and GetElementsbyId.
The function for scrolling pizzas was simplified by creating a new local variable call constantArray. The repeating values for phase was then stored into the constantArray variable.
Phase variable was declared outside of for loop to prevent it from being created each time the loop executes.
Declared elem element outside the for loop to prevent it from being created each time the loop executes.
Created new variable called movingPizzas and stored document.getElementById('movingPizzas1').
Created a new variable named top that handles document.body.scrollTop outside the "for" loop to prevent from being called each time.
Added backface-visibility: hidden to .mover class
Created len to hold the length outside "for" loops.

Pizza resize slider bar:

Removed determineDx function.
Updated changePizzaSizes function by changing newWidth values and added break statements.
Moved variables outside loops to prevent constant calling or creation.
Changed 'querySelector' to 'getElementsByClassName'. 



