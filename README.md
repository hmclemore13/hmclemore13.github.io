INSTALLATION:

1. Download the ZIP file and unzip the folder called: "frontend-nanodegree-mobile-portfolio-master.zip"
2. Right click on index.html and select open with
    Safari
    Google Chrome
    Firefox
    Internet Explorer
3. Check out the optimazations for the index.html page down below this section.
4. Click on the fourth link of the page titled: "Cam's Pizzeria". This will take you to the main page for the optimization project. (pizza.html is the file name)
5. Check out the optimazations for the pizza.html page down below this section.
6. Close your browser to quit


OPTIMIZATIONS:

index.html

1. I inlined the style.css in the header
2. I Used Web Font Loader to load the font asynchronously
3. I added a media query to only access css/print.css  when the user prints the page
4. I optimized two images:
    profilepic.jpg and pizzeria.jpg
5. I changed the google-analytics and js/perfmatters.js scripts to asyncronous


pizza.html

1. I inlined the style.css in the header
2. I inlined the bootstrap-grid.css in the header


views/js/main.js

1. I removed the determineDx function
2. I modified the changePizzaSizes function with a newWidth variable and
   changed the slider value to a percentage width
3. I moved the variable, randomPizzas, outside of the for loop
4. I moved the variable, pizzasDiv, outside of the for loop
5. I changed the function updatePosition
6. I moved the variables from the "function updatePositions" outside of the for loop
7. I replaced querySelectorAll with getElementsByClassName
8. I added the variable phaseArray so the for loop will iterate through the array of phases
9. I added a row variable using a dynamic value that's based on screen height
This way the number of rows are always correct regardless of the screen height
10. I created the variable, movingPizzas, and placed it outside of the for loop
